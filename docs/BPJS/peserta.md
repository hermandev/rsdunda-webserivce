---
layout: default
title: Peserta
parent: BPJS
nav_order: 1
---

# Peserta

## 1. Get data Peserta berdasarkan Nomor Kartu BPJS

* Url : ```http://{BASE_URL}/api/v1/bpjs/nokartu/{NOMOR_KARTU}```<br>
* Method : ```GET``` <br>
* Response : 
```json
{
    "metaData":{
        "code":"200",
        "message":"OK"
    },
    "response":{
        "peserta":{
            "cob":{
                "nmAsuransi":null,
                "noAsuransi":null,
                "tglTAT":null,
                "tglTMT":null
            },
            "hakKelas":{
                "keterangan":"KELAS I",
                "kode":"1"
            },
            "informasi":{
                "dinsos":null,
                "noSKTM":null,
                "prolanisPRB":null
            },
            "jenisPeserta":{
                "keterangan":"PEGAWAI SWASTA",
                "kode":"13"
            },
            "mr":{
                "noMR":null,
                "noTelepon":null
            },
            "nama":"TRI M",
            "nik":"3319022010810007",
            "noKartu":"0011336526592",
            "pisa":"1",
            "provUmum":{
                "kdProvider":"0138U020",
                "nmProvider":"KPRJ PALA MEDIKA"
            },
            "sex":"L",
            "statusPeserta":{
                "keterangan":"AKTIF",
                "kode":"0"
            },
            "tglCetakKartu":"2016-02-12",
            "tglLahir":"1981-10-10",
            "tglTAT":"2014-12-31",
            "tglTMT":"2008-10-01",
            "umur":{
                 "umurSaatPelayanan":"35 tahun ,1 bulan ,11 hari",
                 "umurSekarang":"35 tahun ,2 bulan ,10 hari"
            }
        }
    }
}
```


## 2. Get data Peserta berdasarkan NIK

* Url : ```http://{BASE_URL}/api/v1/bpjs/nik/{NIK}```<br>
* Method : ```GET``` <br>
* Response : 
```json
{
    "metaData":{
        "code":"200",
        "message":"OK"
    },
    "response":{
        "peserta":{
            "cob":{
                "nmAsuransi":null,
                "noAsuransi":null,
                "tglTAT":null,
                "tglTMT":null
            },
            "hakKelas":{
                "keterangan":"KELAS I",
                "kode":"1"
            },
            "informasi":{
                "dinsos":null,
                "noSKTM":null,
                "prolanisPRB":null
            },
            "jenisPeserta":{
                "keterangan":"PEGAWAI SWASTA",
                "kode":"13"
            },
            "mr":{
                "noMR":null,
                "noTelepon":null
            },
            "nama":"TRI M",
            "nik":"3319022010810007",
            "noKartu":"0011336526592",
            "pisa":"1",
            "provUmum":{
                "kdProvider":"0138U020",
                "nmProvider":"KPRJ PALA MEDIKA"
            },
            "sex":"L",
            "statusPeserta":{
                "keterangan":"AKTIF",
                "kode":"0"
            },
            "tglCetakKartu":"2016-02-12",
            "tglLahir":"1981-10-10",
            "tglTAT":"2014-12-31",
            "tglTMT":"2008-10-01",
            "umur":{
                 "umurSaatPelayanan":"35 tahun ,1 bulan ,11 hari",
                 "umurSekarang":"35 tahun ,2 bulan ,10 hari"
            }
        }
    }
}
```

