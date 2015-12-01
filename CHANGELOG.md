## 1.0.2 - 2015-11-30
* nice deprecations for api_version

## 1.0.1 - 2015-11-30
* no longer defines `Rails` when `recaptcha/rails` is required

## 1.0.0 - 2015-11-30
* remove api v1 support
* remove ssl_api_server_url, nonssl_api_server_url, change api_server_url to always need ssl option
* removed activesupport dependency for .to_query
* made flash and models both have descriptive errors

## 0.6.0 - 2015-11-19
* extract token module
* need to use `gem "recaptcha", require: "recaptcha/rails"` to get rails helpers installed

## 0.5.0 - 2015-11-18
* size option
* support disabling stoken
* support Rails.env

## 0.3.6 / 2012-01-07

* Many documentation changes
* Fixed deprecations in dependencies
* Protocol relative JS includes
* Fixes for options hash
* Fixes for failing tests

## 0.3.5 / 2012-05-02

* I18n for error messages
* Rails: delete flash keys if unused

## 0.3.4 / 2011-12-13

* Rails 3
* Remove jeweler

## 0.2.2 / 2009-09-14

* Add a timeout to the validator
* Give the documentation some love

## 0.2.1 / 2009-09-14

* Removed Ambethia namespace, and restructured classes a bit
* Added an example rails app in the example-rails branch

## 0.2.0 / 2009-09-12

* RecaptchaOptions AJAX API Fix
* Added 'cucumber' as a test environment to skip
* Ruby 1.9 compat fixes
* Added option :message => 'Custom error message' to verify_recaptcha
* Removed dependency on ActiveRecord constant
* Add I18n

## 0.1.0 / 2008-2-8

* 1 major enhancement
* Initial Gem Release
