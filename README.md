<!--
![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&text=Che-ri&fontAlign=70&fontAlignY=40&animation=twinkling)
-->

<h3>📌Stack</h3>
<p">Technology used</p>
<div><img src="https://img.shields.io/badge/-Java-brightgreen"></img> &nbsp <img src="https://img.shields.io/badge/CSS3-0A84FF?style=flat-square&logo=CSS3&logoColor=white"></img>  &nbsp <img src="https://img.shields.io/badge/SCSS-fd79a8?style=flat-square&logo=Sass&logoColor=white"/></a>&nbsp  &nbsp <img src="https://img.shields.io/badge/styled%2Dcomponents-DB7093?style=flat-square&logo=styled%2Dcomponents&logoColor=white"/></a>
<br><img src="https://img.shields.io/badge/JavaScript-FFCD11?style=flat-square&logo=JavaScript&logoColor=white"></img> &nbsp <img src="https://img.shields.io/badge/React-00BCF6?style=flat-square&logo=React&logoColor=white"></img> &nbsp <img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=Redux&logoColor=white"/></a></div>

<h3>📫Contact</h3>
<div><a href="roseoutz@gmail.com"> &nbsp <img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=Gmail&logoColor=white"/></a></div>

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-0%20secs-blue)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=roseoutz&show_icons=true&theme=tokyonight)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=roseoutz&layout=compact&theme=tokyonight)

<p align="center">
   <img src="https://img.shields.io/badge/language-typescript-blue?style"/>
   <img src="https://img.shields.io/github/license/maxam2017/productive-box"/>
   <img src="https://img.shields.io/github/stars/maxam2017/productive-box"/>
   <img src="https://img.shields.io/github/forks/maxam2017/productive-box"/>
</p>
<p align="center">
   Are you an early 🐤 or a night 🦉?
   <br/>
   When are you most productive during the day?
   <br/>
   Let's check out in gist!
</p>

---

> This project is inspired by an awesome pinned-gist project.<br/>Find more in https://github.com/matchai/awesome-pinned-gists
## Overview
This project uses GitHub graphQL API to get the commit histories and write into the gist by [rest.js](https://github.com/octokit/rest.js#readme)

## Setup

### Prep work
1. Create a new public GitHub Gist (https://gist.github.com/)
1. Create a token with the `gist` and `repo` scope and copy it. (https://github.com/settings/tokens/new)
   > enable `repo` scope seems **DANGEROUS**<br/>
   > but this GitHub Action only accesses your commit timestamp in repository you contributed.
### Project setup

1. Fork this repo
1. Open the "Actions" tab of your fork and click the "enable" button
1. Edit the [environment variable](https://github.com/maxam2017/productive-box/blob/master/.github/workflows/schedule.yml#L17-L18) in `.github/workflows/schedule.yml`:

   - **GIST_ID:** The ID portion from your gist url: `https://gist.github.com/maxam2017/`**`9842e074b8ee46aef76fd0d493bae0ed`**.
   - **TIMEZONE:** The timezone of your location, eg. `Asia/Taipei` for Taiwan, `America/New_York` for America in New York, etc.

1. Go to the repo **Settings > Secrets**
1. Add the following environment variables:
   - **GH_TOKEN:** The GitHub token generated above.
1. [Pin the newly created Gist](https://help.github.com/en/github/setting-up-and-managing-your-github-profile/pinning-items-to-your-profile)

 Last Updated on 26/06/2022 18:43:42 UTC
<!--END_SECTION:waka-->
