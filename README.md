<br/>
<p align="center">
  <a href="https://github.com/Lynnxha">
    <img src="https://raw.githubusercontent.com/ShaanCoding/ReadME-Generator/main/images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Lynn Rest API Project</h3>
</p>

### E-Perpus

Sebuah Project Rest API Sederhana Berbasis Javascript.

Rest Api ini bebas untuk dikembangkan lagi atau untuk bahan pembelajaran kalian bagi yang mau membuat sebuah Rest Api.

### Built With

I created this project using :

- [Javasript](https://www.javascript.com/)

### Installation

Clone Project

```
git clone https://github.com/your_username_/Project-Name.git
```

Install Module

```
npm install
```

### Running the Application

```
node index.js
```

### Endpoint-Api

| Menu                         | Endpoint                                                                                        |
| ---------------------------- | ----------------------------------------------------------------------------------------------- |
| Nulis                        | api/nulis?text=zahirganteng&apikey=MASUKIN_APIKEY                                               |
| Tiktok Downloader            | api/tiktod/?url=MASUKIN_URL&apikey=MASUKIN_APIKEY                                               |
| Tiktok Stalk                 | api/tiktod/stalk/?username=MASUKIN_URL&apikey=MASUKIN_APIKEY                                    |
| Random Quotes                | api/randomquote?apikey=MASUKIN_APIKEY                                                           |
| Info NPM                     | api/infonpm?query=zhirrr-api&hostname=zhirrr&apikey=MASUKAN_APIKEY                              |
| Short Link                   | api/short/tiny?url=google.com&apikey=MASUKAN_APIKEY                                             |
| Text Maker Glitch            | api/textmaker?text=halo&text2=hai&theme=glitch&apikey=MASUKIN_APIKEY                            |
| Text Maker Google Suggestion | api/textmaker?text=halo&text2=hai&text3=gwganteng&theme=google-suggestion&apikey=MASUKIN_APIKEY |
| Text Maker PUBG              | api/textmaker/game?text=halo&text2=hai&theme=pubg&apikey=MASUKIN_APIKEY                         |
| Text Maker BattleField       | api/textmaker/game?text=halo&text2=hai&theme=battlefield&apikey=MASUKIN_APIKEY                  |
| Text Maker Coffee Cup        | api/textmaker/senja?text=Zhirrr&theme=coffee-cup&apikey=MASUKIN_APIKEY                          |
| Text Maker Coffee Cup 2      | api/textmaker/senja?text=Zhirrr&theme=coffee-cup2&apikey=MASUKIN_APIKEY                         |

### Feature

| Menu              | API |
| ----------------- | --- |
| Nulis             | ✔️  |
| Tiktok Downloader | ✔️  |
| Tiktok Stalk      | ✔️  |
| Random Quotes     | ✔️  |
| Info NPM          | ✔️  |
| Short Link        | ✔️  |
| Text Maker        | ✔️  |
| Text Maker Game   | ✔️  |
| Text Maker Senja  | ✔️  |

### How to change Apikey

```js
if (apikeyInput != "MASUKKAN_NAMA_APIKEY")
  return res.json(loghandler.invalidKey);
```

    or

```js
if (apikey != "MASUKAN_NAMA_APIKEY") return res.json(loghandler.invalidKey);
```

### Authors

<a href="https://github.com/Lynnxha">
  <img src="https://github.com/Lynnxha.png?size=75" alt="Lynnxha" style="border-radius: 50%;">
</a>

### Support

<p><a href="https://www.buymeacoffee.com/lynnxha"> <img align="left" src="https://telegra.ph/file/3b2fb8ed33eb4b94b06f0.png" height="50" width="50" alt="lynnxha" /></a></p>

<p><a href="https://trakteer.id/keiashleych"> <img align="left" src="https://cdn.trakteer.id/images/mix/trakteer-icon-thumbnail.png" height="50" width="50" alt="lynnxha"  /></a></p>
