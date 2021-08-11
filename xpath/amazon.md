# Targeting items in product page that are not cds dvds or books
```
//div[@id='bylineInfo_feature_div']//a[not(contains(@href,'books')) and not(contains(@href,'dvd')) and not(contains(@href,'cd'))]
```

# targeting text within product title in product page
```
//span[@id='productTitle']/text()[contains(translate(., 'ABCDEFGHIJKLMNOPQRSTUVWXYZÀÂÄÇÉÈÊËÎÏÙÛÜ' , 'abcdefghijklmnopqrstuvwxyzàâäçéèêëîïùûü'), 'text')]
```

# targeting an active category
```
//div[@class='a-section']//span[contains(@class,'a-text-bold')]/text()[.='Loisirs Créatifs']
```

# Checks if the price is below 10€
```
translate(translate(//span[@id='priceblock_saleprice'],translate(., '0123456789.,', ''), ''),',','.') < 10
```
