### Запуск приложения KeyValidator

### Материалы для тестирования
[Домашнее задание](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)

[Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

[Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
### Шаги для воспроизведения

- Открыть программу IDEA
- Завести новый проект
- Скопирповать переменную и вставить в IDEA
- Подставить ключ для проверки из списка
- Запустить метод Ctrl+Shift+F10

### При запуске java KeyValidator 
<pre><code>00000000-0000-0000-0000-000000000000
 00000000-0000-0000-0000-000000000001 </code></pre>
 Результат 
<pre><code> Result for 00000000-0000-0000-0000-000000000000: FAIL
Result for 00000000-0000-0000-0000-000000000001: FAIL </code></pre>

### Ошибка в Ключах для проверки
Валидные ключи:
<pre><code>8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 ОК
80b427f8-92cd-3aae-ba04-3927fbe17c6  FAIL
b295bc63-9f03-3b4b-af80-969b39f8c262 OK
387eedc6-12e9-3b32-9881-63b6b5e85317 FAIL
c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 OK </code></pre>

Не валидные ключи:

<pre><code>18252235-78e0-44a5-8720-556f0c7da17a FAIL
e66075b6-ddad-445e-baf6-161b3289522b FAIL
b6d53250-f07e-4352-a293-6102ddf7f1ca FAIL
c2bc778a-1cb9-46c6-b435-0489649d2a42 FAIL
2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 OK </code></pre>
