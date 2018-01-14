# Zend + Transifex + Travis

## Introduction

Example application of using Zend Framework in combination with Transifex and Travis to handle your translations.

To setup Travis, follow [the guide](https://docs.transifex.com/integrations/github#integrating-the-client-with-travis-ci) on Transifex's website.


## Deploy
To be able to use the translations stored on Transifex, you need to download all the translation files. This can be done with the following command:

```bash
./translate-helper sync
```

This command takes care of storing the `.po` files in the correct location and converting them to `.mo` files so that Zend Framework can use them.
