# Cash


![cash](https://source.unsplash.com/WVUrbhWtRNM/800x600)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Description](#-description)
- [How to use it](#-how-use-it)

## Description

This program displays the exchange rate for a desired currency. You can choose the amount and the currency you want to convert. It's a very useful tool to convert currencies


## How to use it

Firstly you need to install all the libraries
```sh
❯ cd /path/to/workspace/3-musketeers/cash
❯ npm i
```

Then launch the program
```sh
❯ node bin/index.js
```

If you want to choose a specific amount with a specific currency,you can write your command like this. Replace "amount" and "currency" with your values (ex: 100 JPY).
```sh
❯ node bin/index.js amount currency
```

You can also change the defaults currencies, in order to change the defaults currencies you need to modify constants.js and change the constant DEFAULT_TO_CURRENCIES

```javascript
const DEFAULT_TO_CURRENCIES = ['USD', 'EUR', 'GBP', 'JPY'];
```
Becomes
```javascript
const DEFAULT_TO_CURRENCIES = ['USD', 'EUR', 'CAD', 'BZD','MXN'];
```
