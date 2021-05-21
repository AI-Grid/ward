# 🔑 Discord Verification
A Discord verification bot using reCAPTCHA v2. 
## 🧳 Requirements
* node.js (I used v12.18.1)
* express (latest)
* axios (latest)
* discord.js (latest)

## 🔌 Installation
```
npm i
```

## 📘 Setup
Register a site with reCAPTCHA [here](https://www.google.com/recaptcha/admin/create) and choose reCAPTCHA v2 "I'm not a robot" Checkbox. Now on your reCAPTCHA dashboard copy the secret and public key into the config.json file. Add your Discord bot token, guild ID, and role ID into config.json aswell. If you are using a domain add it in the config.json file, if you are using HTTPS, enable it in the config add your certificate and private key file with the names: `certificate.pem` and `private.pem`.

## 🕹️ Usage
```
npm start
```

## 📷 Preview
![Embed](https://i.imgur.com/zomEnpw.png)
![Website](https://i.imgur.com/tmrcyjF.png)
