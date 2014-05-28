# Vagrant Development Setup

This is a vagrant development setup that I use for, well... development. It's an easy boilerplate to start from.

## Packages

- Ubuntu 14.04
- nginx
- PHP 5.5
- MySQL
- Mailcatcher
- n98-magerun
- modman

## Usage

This setup uses *xip.io* which is a domainname which always refers to the IP put as a subdomain.
In order to make your project accessible it needs to use one of the following directory structures:

    /vagrant/www/example/web
    /vagrant/www/example/public
    /vagrant/www/example

Then you can access it using the following URL: http://example.192.168.33.10.xip.io/

## MySQL

**User:** vagrant

**Password:** vagrant

## Mailcatcher

Mailcatcher is accessible at: http://192.168.33.10:1080/
