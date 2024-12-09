<p align="center">
<img src="https://i.imgur.com/dBaSKWF.gif" height="90" width="100%">



<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&pause=1000&color=FF0000&width=435&lines=%F0%9D%97%9E+%F0%9D%97%97+_+%F0%9D%97%A3+%F0%9D%97%94+%F0%9D%97%A1+%F0%9D%97%A7+%F0%9D%97%94+_+%F0%9D%97%A0+%F0%9D%97%97" alt="Typing SVG" /></a>



<p align="center">
<img src="https://i.imgur.com/dBaSKWF.gif" height="90" width="100%">



<p align="center">
<a href="https://github.com/KavishkaIroshanb">

  
<img src="https://pomf2.lain.la/f/fxhw0z8c.jpg"  width="700px">
</a>
<hr>



<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&pause=1000&color=FF0000&width=435&lines=%F0%9D%97%9E+%F0%9D%97%97+_+%F0%9D%97%A3+%F0%9D%97%94+%F0%9D%97%A1+%F0%9D%97%A7+%F0%9D%97%94+_+%F0%9D%97%A0+%F0%9D%97%97" alt="Typing SVG" /></a>




<img src="https://i.imgur.com/dBaSKWF.gif" height="90" width="100%">
<p align="center"> 



𝗠𝗬 𝗪𝗛𝗔𝗧𝗦𝗔𝗣𝗣 𝗖𝗛𝗔𝗡𝗡𝗘𝗟♻️

<a href="https://whatsapp.com/channel/0029VaxNSDR4SpkEoUszuP3E"><img alt="JOIN MY WHATSAPP CHANNEL KD_PANTA_00" width="300"></a>



𝗠𝗬 𝗪𝗛𝗔𝗧𝗦𝗔𝗣𝗣 𝗚𝗥𝗢𝗨𝗣🤖

<a href="https://chat.whatsapp.com/GvR2hfJ42mO9HNwuFJVax6"><img alt="JOIN MY WHATSAPP BOT GROUP KD_PANTA_00" width="300"></a>



<img src="https://i.imgur.com/dBaSKWF.gif" height="90" width="100%">
<p align="center">



🧑‍💻 𝗚 𝗘 𝗧 _ 𝗦 𝗘 𝗦 𝗦 𝗜 𝗢 𝗡 _ 𝗜 𝗗 📲

<a href="https://lithu-md-pair-13dc62a31d33.herokuapp.com/"><img src="https://img.shields.io/badge/QR%20OR%20PAIR%20CODE-blue" alt="GET SESSION" width="200"></a>



<img src="https://i.imgur.com/dBaSKWF.gif" height="90" width="100%">
<p align="center">


<hr>

<b>𝗖𝗢𝗣𝗬 𝗖𝗢𝗗𝗘</b></br>
```
on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start
```
