# Руководство по стилю

## Общая информация

При написании текстов отталкивайтесь от задач пользователя, а не от функциональных возможностей программы. 

Экономьте время пользователей. Документация никогда не должна вызывать вопросов и трактоваться двусмысленно. 

## Упрощение

Избегайте слов которые перегружают текст. Если слово можно выбросить и смысл текста не поменяется — выбрасывайте.

| Правильно                                                    | Не правильно                                                 |
| :----------------------------------------------------------- | ------------------------------------------------------------ |
| Для авторизации перейдите в **Личный кабинет** и нажмите кнопку **Авторизация**. | Для авторизации в системе электронного документооборота ОГО-ЭДО, выполните переход в раздел **Личный кабинет** и осуществите нажатие на кнопку **Авторизация**. |

## Повелительное наклонение

Используйте повелительное наклонение. Руководите действиями пользователя. 

| Правильно                                                 | Не правильно                                                 |
| --------------------------------------------------------- | ------------------------------------------------------------ |
| В окне **Личный кабинет** нажмите кнопку **Авторизация**. | В окне **Личный кабинет** необходимо нажать кнопку **Авторизация**. |

## Действия

Составляйте текст придерживаясь принципа: **Задача → Действие → Результат**. 

### Задача

Задача указывается в самом начале. Задачей может быть отправка отчета, регистрация учетной записи, обновление статуса. Первая часть предложения (задача) должна отвечать на вопрос “Для чего делаем?”, например: для авторизации, для обновления статуса, для отправки отчета.

### Действие

Действие — это то, что должен выполнить пользователь для решения задачи. Действием является нажатие нажатие кнопки, переход на вкладку, указание данных. Например: 

> Нажмите кнопку **Войти**. Перейдите на вкладку **Заявки**. 

Чаще всего задача и действия описаны в одном предложении.

Для описания действий используйте принцип **Где → Что сделать → С чем**.

1. Где? — В разделе **Отчеты** (опционально, если не очевидно).
2. Что сделать? — **Нажмите**.
3. С чем? — Кнопку **Добавить**.

### Результат

Результат — это то, чем завершается действие пользователя. Результатом может быть открытие окна, отправка отчета, обновление статуса. Например:

> Для отправки отчета, в разделе **Отчеты** нажмите кнопку **Отправить**. Статус отчета изменится на *Отправлено*.

1. Для отправки отчета — задача.
2. В разделе **Отчеты** нажмите **Отправить** — действие, построенное по принципу **Где → Что сделать → С чем**.
3. Статус отчета изменится на *Отправлено* — результат.

## Текст

Разбивайте текст на абзацы. Каждый абзац должен нести определенный смысл. Не перегружайте абзац предложениями. 3-7 предложений в абзаце достаточно.

В начале каждого раздела включайте несколько абзацев с общим описанием. Раскройте в них все те вопросы, которые могут возникнуть у пользователя в процессе выполнения описанных действий. 

Избегайте сложных и длинных предложений. Лучше разбейте его на несколько простых и коротких. 

Не обращайтесь к пользователю на “Вы” . Но если пришлось, то пишите "вы" с маленькой буквы. Стараемся писать обезличено.

Не используйте синонимы в одном и том же документе. Если назвали чекбокс флажком или картинку изображением, то и называйте их так дальше по тексту. 

Избегайте пояснений в скобках. Либо вынесите текст отдельным приложением, либо добавьте его примечанием.

В качестве знака препинания используйте длинное тире "—". Для обозначения диапазонов используйте среднее тире "–". В сложных словах используйте дефис "-".

Не используйте букву “Ё”. Исключения: 

- Если буква есть в названии элемента интерфейса, например: 

> Нажмите кнопку **Вперёд**. 

- В именах собственных — “Семён”. 
- Отсутствие буквы изменяет смысл слова “Заём, осёл, совершённый”.

Не используйте капс (приписные буквы). Даже если в интерфейсе кнопка называется **ВПЕРЁД** — пишите **Вперёд**.

В конце предложения восклицательные знаки не ставятся. 

Фрагменты кода оформляйте моноширинным шрифтом.

```
пример моноширинного шрифта
```

“В случае если” заменяйте союзом “Если”.

Для построения порядка действия или пути в меню используйте стрелку `→` (ALT+26).

Названия клавиш и их комбинации указывайте большими буквами, например: CTRL+ALT+DEL.

## Заголовки

Используйте короткие заголовки. 1-3 слова - идеально, 3-5 слов - хорошо.

Заголовок должен передавать смысл раздела. Но не отражайте сразу весь смысл в заголовке. Лучшее место для этого — первый абзац раздела.

Выделяйте заголовок полужирным.

Не ставьте точку в конце заголовка. Если заголовок состоит из двух предложений, то они разделяются точкой, но конце второго предложения точка не ставится. Например:

> **Установка СКЗИ. Ручной способ**

Если после заголовка начинается список (маркированный или нумерованный), не ставьте двоеточие в конце списка.

## Элементы

Элементы для взаимодействия: кнопка, переключатель, вкладка, ссылка, поле, чекбокс. 

Выделяйте название элемента полужирным. Не используйте кавычки. Исключение — название части элемента в интерфейсе взято в кавычки. Например:

> В окне **Быстрое “Безбумажное” продление** нажмите кнопку **Отправить**.

Название элемента в тексте должно соответствовать названию элемента в программе. Название элемента не склоняется. 

Исключение — названия элементов в верхнем регистре. Если кнопка в программе называется **УДАЛИТЬ**, укажите её название тексте как **Удалить**.

Учитывайте пунктуацию Если кнопка в программе называется **Обзор…**, то в тексте укажите название с многоточием — **Обзор…**

Между “Нажмите на кнопку” и “Нажмите кнопку” нет разницы. Но “Нажмите кнопку” короче. Вариант “Нажмите [название элемента]” допустим. Но рекомендуется название и тип элемента. Тип элемента (кнопка, окно, вкладка) не указывается в следующих случаях:

- Описываете путь в меню. Пример: Перейдите **Все настройки → Добавить → Электронная подпись**.
- Название элемента неочевидно. Например, ссылка выглядит как кнопка или значок.

## Скриншоты

Каждый абзац с описанием действий желательно сопровождать скриншотом, на котором представлен порядок выполнения действий либо элементы для взаимодействия.

В конце предложения после которого будет расположен скриншот, ставьте двоеточие `:`.

Старайтесь уменьшить размер (ширину и высоту) скриншота, используя переключение программы или вкладки в оконный режим и изменение масштаба. Но при этом все важные элементы должны входить в область скриншота.

Добавьте границу между скриншотом и фоном страницы. Белое изображение сливается с белым фоном страницы. Можно добавить к скриншоту рамку или обозначить границы тенью.

Элементы скриншота выделяйте обводкой. Не используйте стрелки. Исключение — очень маленькие элементы, которые могут быть плохо заметны после обводки.

Для отображения на скриншоте последовательности действий используйте цифры. Не используйте указатели в виде стрелок. Когда элементы, на последовательность действий с которыми указывают стрелки, расположены в различных частях изображения, стрелки смотрятся некрасиво.

Формат изображения — `png`. Не используйте формат `gif` (анимация). Не встраивайте в страницу видео.

## Списки

В конце предложения, после которого будет начинаться список, ставьте двоеточие `:`.

### Нумерованный список

Где важен порядок действий и нужно показать их последовательность, используйте нумерованный список.

Каждую строку нумерованного списка начинайте с прописной (заглавной буквы). В конце ставьте точку. Данная рекомендация касается и остальных уровней списка (1.1, 1.1.1).

> Для отправки отчета:
>
> 1. Перейдите в раздел **Отчеты**.
> 2. Выделите нужный отчет.
> 3. Нажмите кнопку **Отправить**.

### Маркированный список

Где не важен порядок значений и действий, используйте маркированный список. Каждую строку маркированного списка начинайте с прописной (заглавной буквы). В конце ставьте точку.

> Для добавления сертификата воспользуйтесь одним из способов:
>
> - Перейдите в раздел **Настройки** и нажмите кнопку **Добавить сертификат**.
> - Откройте карточку абонента и нажмите кнопку Добавить сертификат.
> - В окне мастера подключения активируйте переключатель **Автоматически добавить сертификат после получения**.

Если вводная фраза и список составляют одно предложение (например, вместо списка можем перечислить значения через запятую), то используйте маркированный список. Каждую строку начинайте с маленькой (строчной) буквы, в конце строки ставьте точку с запятой `;`. В конце последней строки маркированного списка ставьте точку.

> Раздел Отчеты позволяет:
>
> - найти отчет;
> - загрузить отчет;
> - отправить отчет;
> - удалить отчет.

Если строка списка содержит значение, смысл которого может измениться от знака препинания, не используйте точки или точки с запятыми.

> Укажите один из адресов:
>
> - 192.168.12.1
> - 192.168.41.1:8080

## Ссылки

Не используйте слова “тут”, “там”, “здесь” и т.п. для ссылки. В качестве ссылки укажите название раздела.

| Правильно                                                    | Не правильно                                              |
| ------------------------------------------------------------ | --------------------------------------------------------- |
| Информация по установке СКЗИ представлена в разделе [Установка СКЗИ](). | Ознакомиться с порядком обработки заявки можно [здесь](). |

Ссылка на раздел не должна быть слишком длинной. Не более 5 слов. Не включайте в ссылку предлоги.

При добавлении ссылки в виде адреса не указывайте в названии ссылки протокол `http` / `https`.

| Правильно                                                 | Не правильно                                                 |
| --------------------------------------------------------- | ------------------------------------------------------------ |
| Информация по работе представлена на сайте [help.at.ru]() | Информация по работе представлена на сайте [https://help.at.ru]() |

По ссылке переходят либо ссылку нажимают.

Не включайте ссылку в кавычки.

