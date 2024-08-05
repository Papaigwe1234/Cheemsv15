### Aide de Jean Parker pour déployer le bot Cheems v15 sur Termux ou UserLand

---

Cette aide est destinée à ceux qui souhaitent déployer le bot **Cheems v15** sur **Termux** ou **UserLand** sans avoir à télécharger les fichiers. Vous êtes libres de fork le repo pour modifier le code en cas d'erreur.

<p align="center">
<img alt="Développement" width="250" src="https://media2.giphy.com/media/W9tBvzTXkQopi/giphy.gif?cid=6c09b952xu6syi1fyqfyc04wcfk0qvqe8fd7sop136zxfjyn&ep=v1_internal_gif_by_id&rid=giphy.gif&ct=g" /> 
</p>

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a><a><img src='https://i.imgur.com/LyHic3i.gif'/></a>


# Termux Deployment
```
termux-setup-storage
```
```
apt update
```
```
apt upgrade
```
```
pkg update && pkg upgrade
```
```
pkg install bash
```
```
pkg install libwebp
```
```
pkg install git -y
```
```
pkg install nodejs -y
```
```
pkg install ffmpeg -y 
```
```
pkg install wget
```
```
pkg install yarn
```
```
git clone (copie et passe le lien du repo que tu a fork avec tes modifications ) 
```
```
cd Jean
```
```
yarn install
```
```
node index --pairing-code
```
```
npm start
```
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a><a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
- If you want Command For 24/7 (might no work) 
```js
npm i -g forever && forever index.js && forever save && forever logs
```
<br>

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a><a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
<br>
<h2 align="center"> 🛡️ Windows Cmd & Vs 🛡️ </h2>

- [Download ffmpeg](https://ffmpeg.org/download.html#build-windows) and set the path
- [Download wget](https://eternallybored.org/misc/wget/releases/) and set the path
- [Download Node.js](https://nodejs.org/en/download/)
- [Download Git](https://git-scm.com/downloads)
- [Download Libwebp](https://developers.google.com/speed/webp/download)

```cmd
> git clone <Le lien du repo>
```
```
> cd Venom-2
```
```
> yarn install
```
```
>node index --pairing-code
```
```
> npm start
```
