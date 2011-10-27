# Hatimeria - Symfony and ExtJS CMF

## Build for heavy javascript applications

This project provides

 * Translations of extjs components directly by symfony
 * Url in javascript generated by symfony backend
 * User switch
 * Backend interface for admin
 * Ajax login
 * Users list
 * Simple cms

Much more soon. (Newsletter, subscriptions, invoices, virtual currency, easy extension points for interfaces)

## Installation guide

Clone this repo.
Copy app/config/custom_example.yml to app/config/custom.yml (this file is used instead of parameters.ini)
Adjust parameters in custom.yml file.
Run php bin/vendors install from console.
Login with email from custom.yml and password: 'hatimeria'

## Developers tools (customized symfony related code):

* Fixtures
* Tests (unit and functional)
* Selenium (for heavy javascript based UI)
* Easy deploy
* Easy update (fixtures, vendors, schema, cache)
* Profiler catches fatal errors

## Screenshots

![Administration page](https://github.com/hatimeria/hatimeria/raw/master/app/Resources/doc/images/admin.png)