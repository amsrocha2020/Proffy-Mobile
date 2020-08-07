# Proffy ![stacks](https://img.shields.io/badge/NodeJS-v12.18.1-brightgreen) ![stacks](https://img.shields.io/badge/ReactJS-v16.13.1-brightgreen) ![stacks](https://img.shields.io/badge/Expo-v38.0.8-brightgreen) ![stacks](https://img.shields.io/badge/Stack-Typescript-blue) ![GitHub](https://img.shields.io/github/license/legeannd/nextlevelweek-proffy)


<p align="center">
  <img src="uploads/capa-mobile.png"/>
</p>

<p align="center">
  <img src="uploads/web.gif"/>
</p>

## About the project <a id="secao-en_us"></a>

Proffy is a platform that connects students aiming to get classes to teachers willing to teach the most varied school subjects, and has been developed during the second edition of Rocketseat's Next Level Week. In the project, it's possible to add a lot of classes, where the teacher can register his info, subjects and his available schedule to give classes. It's also possible search between registered classes, where the user choose the subject, week day and the hour of the day chosen to see if there is an available class.

## Content 
  * [How to execute the project](#installation)
    * [Installation - Back-end](#installation-back)
    * [Installation - Front-end](#installation-front)
    * [Installation - Mobile](#installation-mobile)

## How to execute the project <a id="installation"></a>
To execute the project, you'll need to have Node and NPM or Yarn installed to setup all the dependencies.


### Installation - Back-end (Server and API) <a id="installation-back"></a>

```bash
cd server
npm install
npm run knex:migrate
npm run start
```

If you are using Yarn, use this:
```bash
cd server
yarn install
yarn knex:migrate
yarn start
```

### Installation - Front-end (Web) <a id="installation-front"></a>

```bash
cd web
npm install
npm start
```

If you are using Yarn, use this:
```bash
cd web
yarn install
yarn start
```

After finishing installation, the web page will be open in your browser.

### Installation - Mobile (App) <a id="installation-mobile"></a>

Go to `api.ts` file inside `mobile/src/services` and change to your machine's server ip.
If you need to install *Expo*, execute the following command: `yarn global add expo-cli`.
After, execute the project.


```bash
cd mobile
npm install
npm start
```

If you are using Yarn, use this:
```bash
cd mobile
yarn install
yarn start
```

When executing the project, *Expo's* debug page will open in your browser.

To open the app in your mobile device, download *Expo's* app at Play Store or App Store and scan the QR code shown in the debug page, and wait until the installation finishes.
