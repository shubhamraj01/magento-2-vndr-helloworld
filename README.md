# Magento 2: `Hello world` module

### Features
    - controller
    - block
    - layout
    - template
    - custom page
    - custom link in footer
    - install with composer

### How to install

#### 1. Manual
Just copy this files in `../app/code/Vndr/Helloworld/`

#### 2. Via composer

Add to main `composer.json` in `repositories` section code below
```json
    {
        "type": "vcs",
        "url": "https://github.com/evgv/vndr-helloworld"
    }
```


Run
```shell
    composer require vndr/helloworld:dev-master
```
