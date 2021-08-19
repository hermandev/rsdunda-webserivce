---
layout: default
title: Pasien
nav_order: 2
---

# Data Pasien 
{: .no_toc }

## GET All Data Pasien
* URL : ```http://BASE_URL/api/v1/pasien```
* Method : ```GET```
* Response:
```json
{
    "code": 200,
    "status": "Success",
    "data": [
        {
        "id": 1,
        "tgllahir": "2008-10-19",
        "nomr": "000000",
        "title": "AN",
        "nama": "MOH IRSAD MANGOPA",
        "tempat": "GORONTALO",
        ...
        }
    ]
}
```

## GET Pasien By NOMR
* URL : ```http://BASE_URL/api/v1/pasien/{NOMR}```
* Method : ```GET```
* Response : 
```json
{
    "code": 200,
    "status": "Success",
    "data": [
        {
        "id": 1,
        "tgllahir": "2008-10-19",
        "nomr": "000000",
        "title": "AN",
        "nama": "MOH IRSAD MANGOPA",
        "tempat": "GORONTALO",
        ...
        }
    ]
}
```
