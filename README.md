## MOEX

Анализ тикеров российских акций и их годовой доходности. Анализ вдохновлен предположением Даниэля Канемана в книге "Думай медленно решай быстро" о зависимости доходности акций в первые годы выхода компании на IPO от понятности тикера. 

## Содержание 

| Название | Содержание | 
|----------------|----------------|
| Stocks.ipynb | Ноутбук формата .ipynb с детальным описанием проекта |
| requirements.txt | Требуемые библиотеки |


## Описание

Задачи: 
1. Определение зависимости между понятностью тикера [1] и ее годовой доходности

В работе был проведен анализ зависимости между ценами акций и названиями их тикеров. Группой из 3 добровольцев были выделены акции, тикеры которых были определены как интерпретируемые (понятные тикеры). Далее на основе исторических данных 39 российских акций Мосбиржи (2014-2020 гг.) была подсчитана ежегодная доходность акций в процентах. Средние значения годового прироста стоимости акций (понятные/непонятные) были сравнены между собой по годам изучения с помощью t-критерия Стьюдента. Данный критерий показал, что зависимость между понятностью тикера и его годовой доходностью не выявлена.

<img width="406" alt="Screenshot 2022-07-09 at 3 15 37 PM" src="https://user-images.githubusercontent.com/75318962/178105348-7343300b-14f2-42f3-9b6d-fdf5c514473c.png">

2. Рассмотрение зависимости положения первой буквы тикера в алфавите и ее годовой доходности

Для определения корреляции были использованы коэффициенты Спирмена и Кендалла. Ранжирование проводилось следующим образом: акции были отсортированы по алфавиту и по годовой доходности. Как с использованием коэффициента Спирмена, так и используя коэффициент Кендалла, корреляция была низка за каждый рассматриваемый год. Проведенный анализ говорит о том, что зависимость между расположением первой буквы тикера в алфавите и его годовой доходностью не выявлена. 

###                                                                   Зависимости

  Для настройки необходимых пакетов python для скрипта введите в командной строке:
  > pip install -r "requirements.txt"

  

###                                                                    Контакты


  **Telegram**: @sophi_nikol\
  **VK**: https://vk.com/nik_sophi\
  **Email**: nikolenko.sofiya@list.ru\

[1] - краткое название в биржевой информации котируемых инструментов (акций, облигаций, индексов)
