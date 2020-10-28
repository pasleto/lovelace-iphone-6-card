<h1 align="center">
    Lovelace Apple iPhone 6 Card
</h1>

HA Lovelace Card for Apple iPhone 6 / 6s / 7 / 8 / SE 2020 using sensors data


<p align="center">
    <img src="https://raw.githubusercontent.com/pasleto/lovelace-iphone-6-card/master/example/card_example.png" alt="Example"/>
</p>

## Setup

Install using [HACS][hacs] using the following custom plugin repository ```https://github.com/pasleto/lovelace-iphone-6-card```
```yaml
resources:
  - url: /hacsfiles/lovelace-iphone-6-card/lovelace-iphone-6-card.js
    type: module
```

OR 

Manually add [lovelace-iphone-6-card.js] and [iphone_6.png]
to your `<config>/www/lovelace-iphone-6-card` folder and add the following to your `configuration.yaml` file:
```yaml
resources:
  - url: /local/lovelace-iphone-6-card/lovelace-iphone-6-card.js
    type: module
```


[hacs]: https://github.com/custom-components/hacs
[lovelace-iphone-6-card.js]: https://raw.githubusercontent.com/pasleto/lovelace-iphone-6-card/master/dist/lovelace-iphone-6-card.js
[iphone_6.png]: https://raw.githubusercontent.com/pasleto/lovelace-iphone-6-card/master/dist/iphone_6.png
