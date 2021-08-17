---
layout: default
title: Home
nav_order: 1
description: ""
permalink: /
---

# Webservice SIMRS-DUNDA
{: .fs-9 }

WebService ini di bangun dengan salah satu Framework JAVA yaitu Spring Boot
{: .fs-6 .fw-300 }


## Cara Menggunakan

### Download Source

silahkan download source  [Disini](https://gitlab.com/rsdunda/simrs-dunda), pastikan system anda sudah terinstall JDK (Java Development Kit) versi 8 atau yang terbaru. download JDK [Disini](https://www.oracle.com/java/technologies/javase-downloads.html)

Setelah JDK sudah terinstall silahkah melakukan pengecekan versi JAVA yang sudah terinstall dengan perintah:
```yml
java -version
```

## Install Maven

Maven merupakan tools untuk mempermudah membangun dan mengelola Project JAVA. 

### Install Maven Di Windows

Untuk menginstall Maven silahkan download terlebih dahulu [disini](https://maven.apache.org/download.cgi). 
silahkan Extrak dan install seperti biasanya.

setelah terinstall silahkan ketik:
```yml
mvn -verison
```

perintah ini untuk menguji jika maven sudah berhasil terinstall di system anda.

### Install Maven Di Linux

Untuk menginstall Maven silahkan download terlebih dahulu [disini](https://maven.apache.org/download.cgi). 
setelah berhasil di download silahkan jalankan perintah: 
```bash
tar -xvf apache-maven-3.3.9-bin.tar.gz -C /usr/local/apache-maven/apache-maven-3.3.9
```

kemudian menambahkan Environment Path pada file ```~./bashrc``` dengan perintah: 

```bash
nano ~/.bashrc
```

kemudian copy/paste baris ini:
```bash
export M2_HOME=/usr/local/apache-maven/apache-maven-3.3.9
export M2=$M2_HOME/bin
export MAVEN_OPTS=-Xms256m -Xmx512m
export PATH=$M2:$PATH 
```

kemudian jalankan:
```bash
mvn -version
```
maka akan keluar seperti ini:
```bash
Apache Maven 3.6.3
Maven home: /usr/share/maven
Java version: 15.0.2, vendor: Oracle Corporation, runtime: /home/hermandev/.jdks/openjdk-15.0.2
Default locale: en_US, platform encoding: UTF-8
OS name: "linux", version: "5.8.0-63-generic", arch: "amd64", family: "unix"
```

## Menjalankan Aplikasi

Setelah Proses install JDK dan maven selesai, silahkan masuk ke dalam folder resource yang sudah di download tadi kemudian jalankan perintah: 
```bash
mvn clean package -DskipTest
```

setelah proses build dependency selesai, kemudian jalankan perintah:
```bash
mvn clean spring-boot:run
```

setelah berhasil dijalankan silahkan melakukan testing lewat [Postman](https://www.postman.com) atau [Insomnia](https://insomnia.rest)
