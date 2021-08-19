---
layout: default
title: Kamar
nav_order: 3
---

# Data Kamar 
{: .no_toc }

## GET All Kamar
* URL : ```http://BASE_URL/api/v1/kamar```
* Method : ```GET```
* Response :

```json
{
    "code": 200,
    "status": "Success",
    "data": [{
        "id": 1,
        "kode": "KIRH-01",
        "namaKamar": "Kamar Irina H 1",
        "ruangan": {
            "id": 1,
            "ruangan": "Irina H Lantai 1",
            "unitLayanan": {
            "id": 2,
            "namaUnitLayanan": "Perawatan Penyakit Dalam",
        },
        "status": "Y"
        },
        "kelas": {
            "id": 3,
            "kelas": "Kelas II",
            "tarif_inap": 75000,
            "idperbub": null,
            "status": "Y"
        },
        "status": "Y"
    }],
    ...

}
```



## GET Kamar By KODE
* URL : ```http://BASE_URL/api/v1/kamar/{kode}```
* Method : ```GET```
* Response : 
```json
{
    "code": 200,
    "status": "Success",
    "data": {
        "id": 1,
        "kode": "KIRH-01",
        "namaKamar": "Kamar Irina H 1",
        "ruangan": {
            "id": 1,
            "ruangan": "Irina H Lantai 1",
            "unitLayanan": {
            "id": 2,
            "namaUnitLayanan": "Perawatan Penyakit Dalam",
        },
        "status": "Y"
        },
        "kelas": {
            "id": 3,
            "kelas": "Kelas II",
            "tarif_inap": 75000,
            "idperbub": null,
            "status": "Y"
        },
        "status": "Y"
    }
}
```


