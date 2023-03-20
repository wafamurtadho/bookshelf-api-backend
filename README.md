# bookshelf-api-backend
Resful API dan Back-End pada Aplikasi Web Buku Catatan yang telah saya buat dan hasil submition projek tugas akhir pada kelas "Belajar membuat aplikasi Back-End untuk pemula" di Dicoding Academy. 

## Customize configuration

## Project Setup
```sh
npm init --y (instan installer)
```
```sh
npm install
```
```sh
npm install <name-packed>
```
## Install Nodemon 
```sh
npm install --save-dev nodemon
```
## Install  @hapi/hapi
```sh
npm i @hapi/hapin
```

## Install eslint
```sh
npm i eslint
```

## Install express & Configuration
```sh
npm i express
```

```sh
const express = require('express')
const app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
```

### Compile and Hot-Reload for Development

```sh
npm run start 'or' npm run dev
```


### Compile and Minify for Production

```sh
npm run build
```
