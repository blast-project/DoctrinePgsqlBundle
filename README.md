# BlastDoctrinePgsqlBundle
[![Version](https://img.shields.io/packagist/vpre/blast-project/DoctrinePgsqlBundle.svg)](https://packagist.org/packages/sylius/sylius)
[![Build Status](https://travis-ci.org/blast-project/DoctrinePgsqlBundle.svg?branch=master)](https://travis-ci.org/blast-project/DoctrinePgsqlBundle)
[![Coverage Status](https://coveralls.io/repos/github/blast-project/DoctrinePgsqlBundle/badge.svg?branch=master)](https://coveralls.io/github/blast-project/DoctrinePgsqlBundle?branch=master)
[![License](https://img.shields.io/github/license/blast-project/DoctrinePgsqlBundle.svg?style=flat-square)][license]



This bundle extends the Postgresql functionalities of Doctrine and Sonata projects

Features
========

For the moment, the only feature of this bundle is:

- replacing LIKE keyword by ILIKE (Postgresql specific) in sql queries in order to have case insensitive comparisons
- Substring function (regular expressions): "substring(field, regexp)" outputs "substring(field from regexp)". Postgresql specific
