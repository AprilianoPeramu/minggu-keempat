# Bootstrapt

<p align='center'>
<img src="img/Bootsrap.png">
</p>

## Intro to Bootstrap
* __Bootstrap__ adalah Framework website yg gratis di gunakan oleh proggamer manapun atau kita bisa menyebutnya templet design website. Bootstrap pertama kali di rancang oleh Mark Otto dan Jacob Thornton yg dirilis pertama pada 19 agustus 2011. Untuk menggunakan Bootstrap ini kalian di wajibkan mempunyai basic coding seperti HTMl,CSS, dan JS. Boostrap ini memiliki keunggulan yaitu kita dapat mempersingkat waktu kerja dan proggamer tidak perlu bersusah payah karna di bootsrap kita bisa langsung style website semau kita dengan cara yg sangat mudah.

> ini adalah link styleschet atau css agar bisa menggunakan nya di html kalian harus menaruhnya di tag Head
```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
```
> ini adalah link javascript agar bisa menggunakan nya di html kalian harus menaruhnya di tag body.

```
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
```
> dan lagi kalian bisa mendownload Bootstrap dengan banyak cara, lalu di Bootstrap ada juga yg namnya colum bisa di cel di link di bawah.

[Selengkapnya Tentang Bootstrap!](https://getbootstrap.com/docs/5.0/getting-started/download/)

# React JS

<p align='center'>
<img src="img/react.png">
</p>

# Intro to React JS

* __React__ __JS__ adalah Framework view library javascript untuk membuat tampilan(User interface) pada website. React JS sendiri pertama kali di gunakan oleh Tim Engenieer Facebook, Facebook menggunakan react pada sisi Front-end. Ada beberapa Macam framework dan javascript adalah salah satu yg lebih unggul di antara yg lainnya seperti Vue dan Angular. Keunggulan React JS iyalah React itu cepat, React dapat menerapkan konsep modular javascript pada react js, React JS scable yg di mana dapat di gunakan pada aplikasi bersekala kecil hingga besar dan kompleks, dan terakhir React JS sangat popular.

## Instalasi dan cara menjalankannya React 

1. Install node JS
2. Install Create React App Library
 ```
npm install -g create-react-app
 ```
 3. Buka Terminal atau Command Prompt (CMD)
 4. Lakukan perintah pada terminal yang telah dibuka
 ```
npx create-react-app [name-project]

contoh:
npx create-react-app project-1
 ```
 5. Install library react-router
 ```
npm install react-router@5.3.3
 ```
 6. Buka folder proyek yang telah dibuat, kemudian jalankan Terminal / CMD pada folder tersebut.
 ```
npm run start / npm start
 ``` 
## Membuat UI Element 
```
// HelloWorld,js

import React from 'react';

function HelloWorld(){
    return (
        <h1>Hello World</h1>
    )
};

export default HelloWorld;

```
```
// membuat App.js dan mengimpor HelloWorld

import React from 'react'
import HelloWorld from './HelloWorld';

funciton App () {
    return (
        <div>
        <HelloWorld />
        </div>
    );
};


export default App;
```
* Sintaksis tag aneh ini bukanlah sebuah string ataupun HTML. Sintaksis ini di kenal dengan sebutan JSX, dan sintaksis ini adalah sebuah sintaksis ekstensi untuk JavaScript.

> note : setiap 1 jsx hanya bisa memiliki 1 parent element

[selengkapnya tentang React JS](https://docs.google.com/presentation/d/1MDf2dTlqr_gDnpyBsdRR_s3k8ugj6wUHQWo3UqV7sbA/edit#slide=id.g8a342b19c0_2_289)