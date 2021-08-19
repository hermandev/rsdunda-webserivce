---
layout: default
title: Bed
nav_order: 4
---

# Data Bed 
{: .no_toc }


## GET All Bed
* URL : ```http://BASE_URL/api/v1/bed```
* Method : ```GET```
* Response : 

```json
{
    "code": 200,
    "status": "Success",
    "data": [{
        "id": 1,
        "kodeBed": "B1",
        "noBed": "1",
        "kamar": {
            "id": 1,
            "kode": "KIRH-01",
            "namaKamar": "Kamar Irina H 1",
            "ruangan": {
                "id": 1,
                "ruangan": "Irina H Lantai 1",
                "unitLayanan": {
                "id": 2,
                "namaUnitLayanan": "Perawatan Penyakit Dalam",
                "status": "Y"
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
        },
        "status": "Terisi"
    }],
    ...
}
```


## GET Bed By Id
* URL : ```http://BASE_URL/api/v1/bed/{id}```
* Method : ```GET```
* Response : 

```json
{
    "code": 200,
    "status": "Success",
    "data": {
        "id": 1,
        "kodeBed": "B1",
        "noBed": "1",
        "kamar": {
            "id": 1,
            "kode": "KIRH-01",
            "namaKamar": "Kamar Irina H 1",
            "ruangan": {
                "id": 1,
                "ruangan": "Irina H Lantai 1",
                "unitLayanan": {
                "id": 2,
                "namaUnitLayanan": "Perawatan Penyakit Dalam",
                "status": "Y"
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
        },
        "status": "Terisi"
    }
}
```


