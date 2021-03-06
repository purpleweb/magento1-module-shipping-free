# ENGLISH

## Description

Shipping Module for Magento 1.x

Advanced Shipping extension for Magento is the solution that helps you to configurate shipping rates in a very flexible way.  
Indeed, with Advanced Shipping, you can set shipping rates using almost any variable available: destination, weight, price (including tax or excluding tax, before or after discount), quantity, categories, product attribute, item option, customer group, customer attribute, coupon code, Magento's custom variable, store id, date, etc…

## Extension features
- Can manage one shipping mode (unlimited in Advanced Shipping Pro) and unlimited shipping methods
- Multiple conditionnal delivery methods depending on what you want
- Shipping rates based on destination, weight, price (including tax or excluding tax, before or after discount), quantity
- Shipping rates based on customer group or customer attribute
- Shipping rates based on categories, product attribute, item option
- Shipping rates based on custom variable, coupon code, store id, date, etc…
- Shipping rates based on formulas combining any variable that you need
- Filtering postal codes using wildcards or regular expressions
- Configuration in JSON format (can be generated by scripts)
- Extension used in many countries over the world
- Easy-to-use documentation in english and in french

## Want to do more?

[Discover our add-ons for Advanced Shipping](https://en.store.owebia.com/)

## Documentation

[See the documentation](http://www.owebia.com/os2/en/doc)

## License

MIT License

Copyright (c) 2008-2017 Owebia

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.

## How to manually install the extension?

- Backup your store database and web directory
- Login to Magento backend
- Go to System > Tools > Compilations, if Compiler Status is Enabled, disable the compilation
- Uncompress the archive file, then copy the directory "app" in your Magento root directory
- Go to System > Cache Management. Click button Flush Magento Cache
- Logout from Magento backend and login again

## How to completely uninstall the extension ?
After having uninstalled the extension in Magento Connect Manager, some references remain in the database.  
To solve this problem, you must execute the following MySQL query:

    DELETE FROM `core_config_data` WHERE `path` LIKE 'carriers/owebiashipping_/%'

--------------------------

# FRANCAIS

## Vous voulez davantage de fonctionnalités ?

[Découvrez nos plugins pour Advanced Shipping](https://fr.store.owebia.com/)

## Documentation

[Voir la documentation](http://www.owebia.com/os2/fr/doc)

## Comment installer l'extension manuellement ?

- Faites une sauvegarde de votre boutique et de votre répertoire web
- Connectez-vous au panneau d'administration de Magento
- Allez dans Système > Outils > Compilation, désactiver le compilateur s'il est activé
- Décompresser l'archive, puis copier le répertoire "app" dans le répertoire racine de votre boutique Magento
- Allez dans Système > Gestion du cache. Cliquer sur le bouton Vider le cache de Magento
- Déconnectez-vous du panneau d'administration de Magento puis connectez-vous à nouveau

## Comment désinstaller complètement l’extension ?
Après avoir désinstallé l’extension depuis Magento Connect Manager, il reste encore des références dans la base de donnée.  
Pour solutionner ce problème, il faut exécuter la requête MySQL suivante :

    DELETE FROM `core_config_data` WHERE `path` LIKE 'carriers/owebiashipping_/%'
