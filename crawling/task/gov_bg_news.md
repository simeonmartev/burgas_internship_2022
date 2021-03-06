# ADP data colection task
version 1
## Requirements
- Upload your project on [github](https://github.com/).
- Use Python >=3.8.
- Create README.md documentation on how to install and run crawling script and API.

# Data Collection
Collect at least 20 articles from the [gov.bg](https://www.gov.bg/bg/prestsentar/novini).

## Requirements
- Use [Scrapy Framework](https://scrapy.org/).
- Create and implement [JSON Schema](https://json-schema.org/) validation for the crawled article.
- Use [sqlite3](https://www.sqlite.org/index.html) to store the data.
- Clean up the HTML from the body.
- Extract image links in separade data field
- Make sure that on a second run the spider don't make duplicates in the DB.

## Article information example
```
Date - 2022-06-15
URL - https://nbs.sk/en/news/nbs-warning-about-axe-capital-group-se/
Images - ["https://www.gov.bg/images/upload/13/768/1_1655285277.png", "https://www.gov.bg/images/upload/13/768/2.png"]
Title - Над 5600 украинци вече са започнали работа на трудов договор
Body - От началото на войната в България са влезли над 330 000 украинци. В пика на кризата в държавата бяха настанени над 115 000 души, а към днешна дата в България пребивават около 78 000 все още са в страната. Около половината от тях са настанени в държавни бази и хотели по новата хуманитарна програма.
Над 5600 са наетите на трудов договор украински граждани с временна закрила в България, което представлява над 15% от работоспособното население от бягащите от войната в Украйна. В тази бройка от над 5600 души не влизат наетите на граждански договори и тези в изпитателен срок и, въпреки това, това е най-високият процент интегрирани бежанци, който държавата е успявала да постигне в най-новата си история и то само в рамките на 3 месеца.
Наетите са разпределени в почти всички области на страната, в 20 сектора от икономиката в 9 различни професионални направления.
Работните сектори се разгръщат в следните посоки: от хотелиерство и ресторантьорство, административни и спомагателни дейности до строителство и професионални дейности и научни изследвания и IT. Още в началото на кризата IT секторът заяви, че се нуждае от около 30 000 кадри, а текстилната промишленост може да поеме около 20 000. В различните браншове вече има назначени украинци като ръководители, специалисти, техници, помощен и административен персонал, както и хора с професии, не изискващи специална квалификация.
 
Допълнителни мерки за заетост:
 
От 6 юни Агенцията по заетостта стартира програма, с която да подпомогне украинските бежанци с временна закрила у нас. По 356 лв. за 3 месеца ще бъдат предоставени за наеми и режийни разходи на украински граждани, които са започнали работа в България. Освен това държавата ще осигури на работодателите наемащи бежанци минимална работна заплата и осигуровки за същия срок. Парите са осигурени от ЕС по проект „Солидарност”, финансиран чрез Оперативна програма „Развитие на човешките ресурси” 2014-2020 г.
В периода на субсидираната заетост работодателите ще получават средства за възнаграждения на наетите украинци в размер на минималната работна заплата (710,00 лв.) и дължимите осигуровки за сметка на работодателите, както и стимули, покриващи разходите за всички дължими вноски за сметка на работодателя, съгласно изискванията на Кодекса на труда и Кодекса за социално осигуряване.
```