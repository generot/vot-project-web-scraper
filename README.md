# Website Scraper (WebScrp)

## Какво представлява уеб апликацията?
Апликацията предоставя услугата да се извлече цялото количество информация и снимки от подаден линк

## Какви технологии използваме?
* Javascript
* Go
* HTML + CSS

## Как Docker Swarm помага с високата наличност?
* Високодостъпната конфигурация на Docker Swarm гарантира, че при повреда на node услугите се предоставят отново на други налични node-ве. За да се постигне висока наличност, клъстерът Swarm трябва да има поне три мениджърски node-а. Броят на сривове, които клъстерът Swarm може да понесе, зависи от броя на мениджърските node-ове. Препоръчва се нечетен брой мениджъри, но не повече от 7, за да се избегнат проблеми с производителността. Мениджърските node-ове трябва да бъдат разпределени на отделни места, за да се избегне засягането им от един и същ срив.
* Docker Swarm осигурява балансиране на натоварването, което разпределя трафика между всички налични реплики на дадена услуга. Можете да конфигурирате баланса, като използвате входящи мрежи или външни балансьори на натоварването.
* DS е група от Docker хостове, които работят заедно, за да могат да предоставят високата достъпност и скалируемост
* Услугата в Docker Swarm е мащабируема работна единица, която може да бъде репликирана в множество хостове на Docker. За да постигне висока наличност, трябва да разположите поне две реплики на всяка услуга.


## Installation

```
cd <folder_dir>
server.exe
```


## Отбор
- Кристиан Милчев
- Мартин Карабонев
- Мартин Наков
- Михаил Василев
