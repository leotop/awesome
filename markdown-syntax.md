Поддерживаются обычные html теги, возможно использовать смешанный стиль.

***Выделенный текст***

    *** bold ***

_Курсив_

      _rendered as italicized text_

#### Заголовки

      # h1 Heading
      ## h2 Heading
      ### h3 Heading
      #### h4 Heading
      ##### h5 Heading
      ###### h6 Heading
  
  Горизонтальные линии
  ***
  
    ___: three consecutive underscores
    ---: three consecutive dashes
    ***: three consecutive asterisks

Списки

      + Lorem ipsum dolor sit amet
      + Consectetur adipiscing elit
      + Integer molestie lorem at massa
      + Facilisis in pretium nisl aliquet
      + Nulla volutpat aliquam velit
        - Phasellus iaculis neque
        - Purus sodales ultricies
        - Vestibulum laoreet porttitor sem
        - Ac tristique libero volutpat at
      + Faucibus porta lacus fringilla vel
      + Aenean sit amet erat nunc
      + Eget porttitor lorem

Нумерованные списки

      1. Lorem ipsum dolor sit amet
      2. Consectetur adipiscing elit
      3. Integer molestie lorem at massa
      4. Facilisis in pretium nisl aliquet
      5. Nulla volutpat aliquam velit
      6. Faucibus porta lacus fringilla vel
      7. Aenean sit amet erat nunc
      8. Eget porttitor lorem

Код в строку, выделяется с двух сторон `апострофами`

In this example, `<section></section>` code

Обычный код, оформляется в виде отступа, размером в 4 пробела, от текста должны быть отделены пустыми строками

Блок кода, выделяется тремя опострофами, результат аналогичен пробелам

      ```code
      here
      ```

Таблицы - каждая ячейка отделена от других вертикальной чертой, строки разделены тире

```| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |
```

Простые ссылки преобразуется самоятотельно, ссылки с анкором формируются следующим образом

      [Assemble](http://assemble.io)
      [Upstage](https://github.com/upstage/ "Visit Upstage!")

