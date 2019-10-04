![alt-текст](https://pictures.s3.yandex.net/frontend-developer/dom_bom/logo.svg "Yandex Prakticum - Регулярные выражения");
# Form Validation - https://dmitriyshvanyk.github.io/form/
## Version 1.0.2

## 1. Regex Имя
```^[А-ЯЁ][а-яё]*(-?[А-ЯЁ][а-яё]*)*$```
### [Test][1]
[1]: https://regex101.com/r/bLJqBH/1

## 2. Regex E-Mail
```^[a-z0-9]{1,}?[_-]?[a-z0-9]{1,}?\@[a-z0-9]{1,}?\-?[a-z0-9]{1,}?\.[a-z]{2,}$```
### [Test][2]
[2]: https://regex101.com/r/x3TZml/1

## 3. Regex Телефон
```^\+?[7|8]+?[(|\s]?[0-9]{3}?[)|-]?[\s]?[0-9]{3}?[-\s\.]?[0-9]{2}?[-\s\.]?[0-9]{2}$```

### [Test][3]
[3]: https://regex101.com/r/oQ3YG4/1

## 4. Regex Url сайта
```^((https?):\/\/)(www.)*(([a-z]{2,}?\.?[a-z]{2,})|((\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})?(\:\d{2,5})*))?(\/?[a-z0-9-]?\.?[a-z]{2,})*?[#]*$```
### [Test][4] 
[4]: https://regex101.com/r/182wxC/1