# vAPI [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Check%20out%20vAPI%20on%20Github!&url=https://github.com/roottusk/vapi&via=vk_tushar&hashtags=apisecurity,apitop10,owasp)

[![Docker](https://img.shields.io/badge/docker-support-%2300D1D1)](https://github.com/roottusk/vapi#installation-docker) 
[![Build Status](https://www.travis-ci.com/roottusk/vapi.svg?branch=master)](https://www.travis-ci.com/roottusk/vapi)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blueviolet.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Version](https://img.shields.io/badge/version-v1.0-blue)](https://github.com/roottusk/vapi) 
[![PHP](https://img.shields.io/badge/php-7.4.7-orange)](https://github.com/roottusk/vapi)

<p align="center">
<img src="vapi_logo.png" >
</p>

vAPI is Vulnerable Adversely Programmed Interface which is Self-Hostable PHP Interface that mimics OWASP API Top 10 scenarios in the means of Exercises. 


# Requirements

* Apache Server 
* MySQL
* PostMan
* MITM Proxy

# Installation (Docker)

```bash
docker-compose up -d
```

# Installation (Traditional)

## Copying the Code

```bash
cd <your-hosting-directory>
```

```bash
git clone https://github.com/roottusk/vapi.git
```

## Setting Up Postman

- Import vAPI.postman_collection.json in Postman
- Import vAPI_ENV.postman_environment.json in Postman

## Setting up the Database

Import vapi.sql into MySQL Database

Configure the DB Credentials in the vapi/db/var.php


# Usage

Browse localhost/vapi for Documentation

