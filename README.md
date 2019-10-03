![alt-текст](https://pictures.s3.yandex.net/frontend-developer/dom_bom/logo.svg "Yandex Prakticum - Регулярные выражения");
# Form Validation - https://dmitriyshvanyk.github.io/form/
# version 1.0.0

# 1. Regex Имя
```^[А-ЯЁ][а-яё]*([-][А-ЯЁ][а-яё]*)*$```

# 2. Regex E-Mail
```^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{1,})+$```

# 3. Regex Телефон
```^[\+]?[7|8]{1,}?[(|\s]?[0-9]{3}?[)|-]?[\s]?[0-9]{3}?[-\s\.]?[0-9]{2}?[-\s\.]?[0-9]{2}$```

# 4. Regex Url сайта
```^[http://|https://]?[www.]?(([0-9]{1,3}?[\.]?[0-9]{1,3}?[\.]?[0-9]{1,3}?[\.]?[0-9]{1,3}?[\.])|([\w]{2,}?[\.]?[\w]{2,}))?([\:]?[0-9]{2,5})?[\#]{1}$```