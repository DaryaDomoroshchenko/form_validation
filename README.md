# Практика работы с Git и применения регулярных выражений
## Яндекс.Практикум 
### Задача: освоить технологию Git и работу с командной строкой, а также попрактиковаться в написании сложных конструкций из регулярных выражений.
[Cсылка на рабочую версию формы тут >>](https://daryadomoroshchenko.github.io/form_validation/)   
По ссылке представлена форма, которая валидирует вводимые пользователем данные исходя из правил, перечисленных ниже.
### Имя:
* только кириллица;
* первая буква заглавная;
* можно ввести от 2 до 20 символов;
* возможна запись двойных имён — например Анна-Мария.
### Email:
* только латиница;
* «собака» `@` — обязательный символ;
* точка `.` — тоже обязательный символ;
* цифры, подчерк, тире — разрешённые символы.
### Телефон:
Шаблон для телефона должен находить номера в следующих форматах
* +7(925)900-90-90;
* +7(925) 900-90-90;
* +7 925-900-90-90;
* +79259009090;
* 89259009090.
### Адрес сайта:
Адрес сайта должен
* начинаться с `http://` или `https://`;
* затем `www.` — это необязательная группа;
* IP-адрес — 255.255.255.255 или доменное имя — stasbasov.ru;
* порт — тоже необязательная группа. Порт начинается с двоеточия, за которым идут от 2 до 5 цифр. Например: `:8080`;
* путь — последовательность из цифр, слешей и латинских букв, на конце которого может стоять решётка `#`.

Актуальная версия v0.0.8
