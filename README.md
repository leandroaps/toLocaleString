# toLocaleString
Convert numbers to local currency

## USAGE

``` convertNumbertoCurrency(102000.03, 'pt-BR', 'currency', 'BRL') ```

## CODE
```
const convertNumbertoCurrency = (value, locale, style, format) => {
    const currency = value.toLocaleString(locale, {
      style: style,
      currency: format,
    });

    return currency;
  };
  
```
