# Changelog

## 0.1.4
* Fix msal-angular to transpile for IE11 compatibility: https://github.com/AzureAD/microsoft-authentication-library-for-js/pull/868
* Upgrade to msal-core version 0.2.2, namely including support for `storeAuthStateInCookie` for IE11.

## 0.1.3
* Fix msal-angular exports to properly support IE11: https://github.com/AzureAD/microsoft-authentication-library-for-js/pull/785
  * **Note**: Unfortunately, the fix above caused breakage with `aot` compiling, so `0.1.3` has been deprecated in npm. We recommend pinning to `0.1.2` while we work on a fix. See https://github.com/AzureAD/microsoft-authentication-library-for-js/issues/798

## 0.1.2
* AOT fix for protectedResourceMap issue  https://github.com/AzureAD/microsoft-authentication-library-for-js/issues/407

* Broadcast message returns object

## 0.1.1
* Fixed AOT issue https://github.com/AzureAD/microsoft-authentication-library-for-js/issues/386

* Upgraded to latest msal-core version 0.2.1


## 0.1.0
Preview Release

