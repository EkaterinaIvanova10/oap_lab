<table style="width: 100%;">
  <tr>
    <td style="text-align: center; border: none;">
    Министерство образования и науки РФ<br>
Государственное бюджетное профессиональное образовательное учреждение Республики Марий Эл<br>
Йошкар-Олинский технологический колледж
</td>
  </tr>
  <tr>
    <td style="text-align: center; border: none; height: 15em;">
    <h2 style="font-size:3em;">Отчет</h2>
      <h3>по лабораторной работе<br><br> по дисциплине "Основы алгоритмизации и программирования"<br><br> Тема:<b> "Регулярные выражения"<b> </h3></td>
  </tr>
  <tr>
    <br><br><td style="text-align: right; border: none; height: 20em;">
      Разработал:<br/>
      Бастраков Сергей<br>
      Группа: И-21<br>
      Преподаватель:<br>
      Колесников Евгений Иванович
    </td>
  </tr>
  <tr>
    <td style="text-align: center; border: none; height: 5em;">
    г.Йошкар-Ола,<br> 2021</td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

# Цели и задачи:
1: Используя задания из лабораторной работы  "Регулярные выражения" исследовать принцип работы регулярных выражения.

2: Результат (исследуемый код и логи) оформить в отдельную ветку в репозитории и отчет о лабораторной работе.

# Краткий материал.

Регулярное выражение — это строка, задающая шаблон поиска подстрок в тексте. Одному шаблону может соответствовать много разных строчек.Регулярное выражение, или коротко «регулярка», состоит из обычных символов и специальных командных последовательностей. Работа с регулярками реализована во всех современных языках программирования. Однако существует несколько «диалектов», поэтому функционал регулярных выражений может различаться от языка к языку (реализация регулярных выражений в C# совместима с PERL).

# Что же я делал?

1) Находил валидное время в веденной пользователем строке:

```
  Regex RegexExpretion = new Regex(@"([0][1-9]|[1][0-9]|[2][0-3]):([0-5][0-9])");
```

2) Находил валидный цвет html в веденной пользователем строке:

```
 Regex RegexExpretion = new Regex(@"#([0-9]|[A-F]){6}");
```

3) Разобрал арифметическое выражение:

```
Regex RegexExpretion = new Regex(@"([-+]?(?:\d+(?:\.\d*)?|\.\d+)(?:[eE][-+]?\d+)?)([+]|[-]|[*][\/]?)([-+]?(?:\d+(?:\.\d*)?|\.\d+)(?:[eE][-+]?\d+)?)");
```

# Вывод 

 Используя задания из лабораторной работы  "Регулярные выражения" исследовал принцип работы регулярных выражения. Результат (исследуемый код и логи) оформил в отдельную ветку в репозитории и отчет о лабораторной работе.