# Практическая работа №1

### Здесь я попробую законспектировать все известное о работе с GitHub

# Некоторые команды
1. pwd - текущая папка  
2. ls - содержание папки  
3. touch - создать файл  
4. mkdir - создать директорию  
5. cp - копировать  
6. mv - переместить и еще __БОЛЬШОЕ__ _множество_ других  

И можно ссылки на всякие полезные ресурсы тут давать [Яндекс](https:/www.ya.ru "Это поисковик!")

### Дальше еще сложнее, да? И как определиться с выбором профессии? 

Накоммитили, запушили, и хватит на сегодня. спасибо за внимание!

Хэш - это уникальный идентификатор коммита

Лог хранит в себе всю историю изменений

Команда HEAD - это последний коммит

```mermaid
graph LR;
untracked -- "git add" --> staged;
B-->C;
C-->D;
D-->B;
```