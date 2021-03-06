---
layout: default
title: Overview
---

# Overview

[![Author](https://img.shields.io/badge/author-@colinodell-blue.svg?style=flat-square)](https://twitter.com/colinodell)
[![Latest Version](https://img.shields.io/packagist/v/league/commonmark.svg?style=flat-square)](https://packagist.org/packages/league/commonmark)
[![Total Downloads](https://img.shields.io/packagist/dt/league/commonmark.svg?style=flat-square)](https://packagist.org/packages/league/commonmark)
[![Software License](https://img.shields.io/badge/License-BSD--3-brightgreen.svg?style=flat-square)](LICENSE)
[![Build Status](https://img.shields.io/travis/thephpleague/commonmark/master.svg?style=flat-square)](https://travis-ci.org/thephpleague/commonmark)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/thephpleague/commonmark.svg?style=flat-square)](https://scrutinizer-ci.com/g/thephpleague/commonmark/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/thephpleague/commonmark.svg?style=flat-square)](https://scrutinizer-ci.com/g/thephpleague/commonmark)

{{ site.data.project.highlights.description }}

## Installation

This library can be installed via Composer:

~~~bash
composer require league/commonmark:^0.18
~~~

See the [installation](/0.18/installation/) section for more details.

## Basic Usage

Simply instantiate the converter and start converting some Markdown to HTML!

~~~php
<?php

use League\CommonMark\CommonMarkConverter;

$converter = new CommonMarkConverter();
echo $converter->convertToHtml('# Hello World!');

// <h1>Hello World!</h1>
~~~

<i class="fa fa-exclamation-triangle"></i>
**Important:** See the [basic usage](/0.18/basic-usage/) and [security](/0.18/security/) sections for important details.
