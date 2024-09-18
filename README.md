<p align="center">  
  <a href="https://whatsapp.com/channel/0029Vac8SosLY6d7CAFndv3Z">
    <img alt="malvin" height="300" src="https://telegra.ph/file/b53dcabed5fa2e0fa8739.jpg">
    <h1 align="center"> MALVIN MD </h1>
  </a>
</p>
<p align="center">
<a href="https://github.com/kingmalvn"><img title="Author" src="https://img.shields.io/badge/kingmalvn-black?style=for-the-badge&logo=Github"></a> <a href="https://whatsapp.com/channel/0029Vac8SosLY6d7CAFndv3Z"><img title="Author" src="https://img.shields.io/badge/CHANNEL-black?style=for-the-badge&logo=whatsapp"></a> <a href="https://wa.me/263714757857"><img title="Author" src="https://img.shields.io/badge/CHAT US-black?style=for-the-badge&logo=whatsapp"></a>
<p/>
<p align="center">
<a href="https://github.com/kingmalvn?tab=followers"><img title="Followers" src="https://img.shields.io/github/followers/kingmalvn?label=Followers&style=social"></a>
<a href="https://github.com/kingmalvn/Malvin-Md/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/kingmalvn/Malvin-Md?&style=social"></a>
<a href="https://github.com/kingmalvn/Malvin-Md/network/members"><img title="Fork" src="https://img.shields.io/github/forks/kingmalvn/Malvin-Md?style=social"></a>
<a href="https://github.com/kingmalvn/Malvin-Md/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/kingmalvn/Malvin-Md?label=Watching&style=social"></a>
</p>

####  
# My Awesome Project

Welcome to my awesome project! Here you'll find...
## YouTube Channel

Check out my YouTube channel for tutorials and more!

[![YouTube Channel](https://img.shields.io/badge/Subscribe-My%20Channel-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/@kingmations1)
## WhatsApp Channel

Join our WhatsApp channel for updates and discussions!

[![WhatsApp Channel](https://img.shields.io/badge/Join-WhatsApp%20Channel-25D366?style=for-the-badge&logo=whatsapp)](https://whatsapp.com/channel/0029Vac8SosLY6d7CAFndv3Z)
## WhatsApp Support Group

Join our WhatsApp support group for assistance and discussions!

[![WhatsApp Support Group](https://img.shields.io/badge/Join-WhatsApp%20Support%20Group-25D366?style=for-the-badge&logo=whatsapp)](https://chat.whatsapp.com/Kg9vFD30nrN4vPbjNtyXUl)

#### SETUP

1.𝔽𝕠𝕣𝕜 𝕥𝕙𝕖 𝕣𝕖𝕡𝕠
    <br>
<a href='https://github.com/kingmalvn/Malvin-Md/fork' target="_blank"><img alt='Fork repo' src='https://img.shields.io/badge/Fork Repo-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=black&color=blue'/></a>

[GET UPDATEED SESSION ID FROM REPLIT](https://replit.com/@mrwasidev/session?v=1)

2.𝔾𝕖𝕥 𝕊𝕖𝕤𝕤𝕚𝕠𝕟 𝕀𝔻 (ℙ𝔸𝕀ℝ𝕀ℕ𝔾)
    <br>
    
<a href='https://wasi-bot-web.vercel.app/' ptarget="_blank"><img alt='SESSION ID' src='https://img.shields.io/badge/Session_id-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=black&color=orange'/></a>


3. [𝔾𝕖𝕥 𝕊𝕖𝕤𝕤𝕚𝕠𝕟 𝕀𝔻](https://replit.com/@mrwasidev/session?v=1)

    <br>
<a href='https://wasi-bot-web.vercel.app/' target="_blank"><img alt='SESSION ID' src='https://img.shields.io/badge/Session_id-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=black&color=blue'/></a>


#### 𝕕𝕖𝕡𝕝𝕠𝕪𝕞𝕖𝕟𝕥 𝕤𝕖𝕔𝕥𝕚𝕠𝕟
# <a href="https://dashboard.heroku.com/new?template=https://github.com/kingmalvn/Malvin-Md"><img title="heroku" src="https://img.shields.io/badge/DEPLOY ON HEROKU-h?color=blue&style=for-the-badge&logo=msi"></a>
# <a href="https://render.com/templ"><img title="RENDER" src="https://img.shields.io/badge/DEPLOY ON RENDER-h?color=black&style=for-the-badge&logo=msi"></a>
# <a href="(https://replit.com/github/kingmalvn/Malvin-Md"><img title="raplirt" src="https://img.shields.io/badge/RAPLIT-h?color=pink&style=for-the-badge&logo=msi"></a>
# <a href="https://wasimd-9dedcea2edba.herokuapp.com/"><img title="koyeb" src="https://img.shields.io/badge/DEPLOY ON KYOEB-h?color=green&style=for-the-badge&logo=msi"></a>

```
const { spawnSync } = require('child_process')
const { existsSync, writeFileSync } = require('fs')

const SESSION_ID = 'ADD YOUR SESSION ID' // Edit this line only, don't remove ' <- this symbol

if (!existsSync('kingmalvn)) {
  console.log('Cloning the repository...')
  const cloneResult = spawnSync(
    'git',
    ['clone', 'https://github.com/kingmalvn/Malvin-Md.git', 'kingmalvn],
    {
      stdio: 'inherit',
    }
  )

  if (cloneResult.error) {
    throw new Error(`Failed to clone the repository: ${cloneResult.error.message}`)
  }

  const configPath = 'kingmalvn/config.env'
  try {
    console.log('Writing to config.env...')
    writeFileSync(configPath, `VPS=true\nSESSION_ID=${SESSION_ID}`)
  } catch (err) {
    throw new Error(`Failed to write to config.env: ${err.message}`)
  }

  console.log('Installing dependencies...')
  const installResult = spawnSync('yarn', ['install', '--network-concurrency', '3'], {
    cwd: 'kingmalvn,
    stdio: 'inherit',
  })

  if (installResult.error) {
    throw new Error(`Failed to install dependencies: ${installResult.error.message}`)
  }
}

spawnSync('yarn', ['start'], { cwd: 'kingmalvn', stdio: 'inherit' })
```
### 𝕋ℍ𝔸ℕ𝕂𝕊 𝕋𝕆
 [`ASTROPED FOR PLUGINS `](https://github.com/astroped)
  [`ibrahim-tech-for-help`](https://github.com/ibrahimaitech)
  



   
## 𝕎𝔸ℝℕ𝕀ℕ𝔾
- 𝘛𝘩𝘪𝘴 𝘣𝘰𝘵 𝘪𝘴 𝘯𝘰𝘵 𝘮𝘢𝘥𝘦 𝘣𝘺 `𝘞𝘩𝘢𝘵𝘴𝘈𝘱𝘱 𝘐𝘯𝘤.` 𝘚𝘰 𝘮𝘪𝘴𝘶𝘴𝘪𝘯𝘨 𝘵𝘩𝘦 𝘣𝘰𝘵 𝘮𝘪𝘨𝘩𝘵 `𝘣𝘢𝘯` 𝘺𝘰𝘶𝘳 `𝘞𝘩𝘢𝘵𝘴𝘈𝘱𝘱 𝘢𝘤𝘤𝘰𝘶𝘯𝘵!`(𝘛𝘩𝘰𝘶𝘨𝘩 𝘺𝘰𝘶𝘳 𝘞𝘩𝘢𝘵𝘴𝘈𝘱𝘱 𝘢𝘤𝘤𝘰𝘶𝘯𝘵 𝘤𝘢𝘯 𝘣𝘦 𝘶𝘯𝘣𝘢𝘯𝘯𝘦𝘥 𝘰𝘯𝘭𝘺 𝘰𝘯𝘤𝘦.)
- 𝘐 𝘢𝘮 𝘯𝘰𝘵 𝘳𝘦𝘴𝘱𝘰𝘯𝘴𝘪𝘣𝘭𝘦 𝘧𝘰𝘳 𝘣𝘢𝘯𝘯𝘪𝘯𝘨 𝘺𝘰𝘶𝘳 𝘢𝘤𝘤𝘰𝘶𝘯𝘵.
- 𝘜𝘴𝘦 𝘢𝘵 𝘺𝘰𝘶𝘳 𝘰𝘸𝘯 𝘳𝘪𝘴𝘬 𝘣𝘺 𝘬𝘦𝘦𝘱𝘪𝘯𝘨 𝘵𝘩𝘪𝘴 𝘸𝘢𝘳𝘯𝘪𝘯𝘨 𝘪𝘯 𝘮𝘪𝘯𝘥.

<h2 align="center">  NOTICE
</h2>
   
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░░▒▓██████▓▒░ ░▒▓███████▓▒░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓████████▓▒░░▒▓██████▓▒░░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░      ░▒▓█▓▒░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░      ░▒▓█▓▒░▒▓█▓▒░ 
 ░▒▓█████████████▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓███████▓▒░░▒▓█▓▒░ 
                                                      

                                                      
