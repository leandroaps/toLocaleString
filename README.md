# toLocaleString
Convert numbers to local currency

## USAGE

``` convertNumbertoCurrency(102000.03, 'pt-BR', 'currency', 'BRL') ```

## CODE
```
const convertNumbertoCurrency = (value, locale, style, format) => {
  return value.toLocaleString(locale, {
    style: style,
    currency: format,
  });
};
  
```
