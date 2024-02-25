# Secure Coding: Security Libraries for Web Development

This repository contains a curated list of security libraries for various programming languages commonly used in web application and API development.

## Table of Contents

- [Golang](#golang)
- [Java](#java)
- [Node.js](#nodejs)
- [PHP](#php)
- [.NET](#net)
- [Ruby](#ruby)
- [Python](#python)

---

## Golang

- [authelia](https://github.com/authelia/authelia): Authelia is an open-source authentication and authorization server providing two-factor authentication and single sign-on (SSO) for your applications via a web portal. It acts as a companion for reverse proxies by allowing, denying, or redirecting requests.
- [casbin](https://github.com/casbin/casbin): An authorization library that supports access.
- [caswaf](https://github.com/casbin/caswaf): HTTP & OAuth Gateway and Web Application Firewall (WAF) based on ModSecurity.
- [coraza](https://github.com/corazawaf/coraza): OWASP Coraza WAF is a golang modsecurity compatible web application firewall library .
- [crypto](https://pkg.go.dev/crypto): Standard cryptographic functions for Go.
control models like ACL, RBAC, and ABAC.
- [go-password-validator](https://github.com/wagslane/go-password-validator): Validate the Strength of a Password in Go.
- [gorilla/csrf](https://github.com/gorilla/csrf): is a HTTP middleware library that provides cross-site request forgery (CSRF) protection.
- [jwt-go](https://github.com/golang-jwt/jwt): JSON Web Tokens (JWT) implementation for Go.
- [secure](https://github.com/unrolled/secure): HTTP middleware for Go that facilitates some quick security wins. 

## Java

- [apache shiro](https://shiro.apache.org/): A versatile security framework for Java applications, providing authentication, authorization, cryptography, and session management.
- [bouncy castle](https://www.bouncycastle.org/): A cryptographic library for Java that provides APIs for various cryptographic operations.
- [owasp java html sanitizer](https://owasp.org/www-project-java-html-sanitizer/): A library to help prevent Cross-Site Scripting (XSS) attacks.
- [spring security](https://spring.io/projects/spring-security): A powerful and highly customizable authentication and access control framework for Java applications.



## Node.js

- [bcrypt](https://www.npmjs.com/package/bcrypt): A library for hashing passwords in Node.js applications.
- [Helmet](https://github.com/helmetjs/helmet): A collection of middleware to help secure Express apps by setting various HTTP headers.
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken): JSON Web Token (JWT) implementation for Node.js.
- [node-rate-limiter-flexible](https://github.com/animir/node-rate-limiter-flexible): counts and limits number of actions by key and protects from DDoS and brute force attacks at any scale
- [passport](https://github.com/jaredhanson/passport): Passport is authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application. 
- [validator](https://github.com/validatorjs/validator.js): A library of string validators and sanitizers.

## PHP

- [HTML Purifier](https://github.com/ezyang/htmlpurifier): HTML Purifier is an HTML filtering solution that uses a unique combination of robust whitelists and aggressive parsing to ensure that not only are XSS attacks thwarted, but the resulting HTML is standards compliant.
- [Laravel Sanctum](https://github.com/laravel/sanctum): A simple package for API token authentication in Laravel PHP applications.
- [League/OAuth2-Server](https://github.com/thephpleague/oauth2-server): is a standards compliant implementation of an OAuth 2.0 authorization server written in PHP which makes working with OAuth 2.0 trivial.
- [paragonie/random_compat](https://github.com/paragonie/random_compat): A compatibility library providing random_bytes() and random_int() for older PHP versions.
- [Parsedown](https://github.com/erusev/parsedown): Parsedown is capable of escaping user-input within the HTML that it generates.
- [PHP Encryption](https://github.com/defuse/php-encryption): A PHP Secure Communications Library providing basic RSA, DSA, and SSH-2 functionality.
- [Security Component - Core](https://github.com/symfony/security-core): Security provides an infrastructure for sophisticated authorization systems, which makes it possible to easily separate the actual authorization logic from so called user providers that hold the users credentials.
- [Security Component - CSRF](https://github.com/symfony/security-csrf): The Security CSRF (cross-site request forgery) component provides a class CsrfTokenManager for generating and validating CSRF tokens.
- [Security Component - Guard](https://github.com/symfony/security-guard): The Guard component brings many layers of authentication together, making it much easier to create complex authentication systems where you have total control.

## .NET

- [Microsoft.AspNetCore.Cryptography.KeyDerivation](https://www.nuget.org/packages/Microsoft.AspNetCore.Cryptography.KeyDerivation/): Key derivation algorithms for ASP.NET Core.
- [Microsoft.AspNetCore.DataProtection](https://www.nuget.org/packages/Microsoft.AspNetCore.DataProtection/): Data protection APIs for protecting and unprotecting data.
- [NWebsec](https://docs.nwebsec.com/en/latest/): Middleware for ASP.NET applications to set security-related HTTP headers.

## Ruby

- [Devise](https://github.com/heartcombo/devise): A flexible authentication solution for Ruby on Rails.
- [sinatra/rack-protection](https://github.com/sinatra/sinatra/tree/main/rack-protection#readme): Middleware for protecting against common web attacks (XSS, CSRF, Clickjacking, Directory Traversal, Session Hijacking and IP Spoofing)
- [nokogiri](https://github.com/sparklemotion/nokogiri): Securely parses HTML and XML.
- [Bycrypt](https://rubygems.org/gems/bcrypt): bcrypt is a sophisticated and secure hash algorithm for hashing passwords

## Python

- [OWASP Python Security Project](https://owasp.org/www-project-python-security/): A collection of Python security-related tools and libraries.
- [django-allauth](https://github.com/pennersr/django-allauth): A Django authentication library providing support for various authentication methods, including social authentication.
- [cryptography](https://cryptography.io/en/latest/): A Python library providing cryptographic recipes and primitives.
