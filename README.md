<h1 align="center">
   <strong>React-firebase-form</strong>
</h1>

<h2 align="center">
  A React form integrated with ChakraUI and Firebase realtime database.  
</h2>

<div align="center">  
  <img src="https://img.shields.io/github/license/gabrielpenteado/react-form?color=informational&style=flat-square" alt="license"/>

  <img src="https://img.shields.io/static/v1?label=npm&message=v9.5.0&color=informational&style=flat-square" alt="react version">

  <img src="https://img.shields.io/static/v1?label=react&message=v18.2.0&color=informational&style=flat-square" alt="react version">
  
  <img src="https://img.shields.io/static/v1?label=firebase&message=v9.18.0&color=informational&style=flat-square" alt="react version">

  <img src="https://img.shields.io/website?down_color=red&down_message=offline&style=flat-square&up_color=008000&up_message=online&url=https%3A%2F%2Freact-firebase-form.vercel.app" alt="website status">
</div>

## 📜 Contents

- [About the project](#-about-the-project)
  - Built with
  - Website
- [Getting Started](#-getting-started)
  - Requirements
  - Installation
- [Features](#-features)
  - Light / Dark Mode
  - Password Strength Meter
  - Pop-Up Message
- [Contributions](#-contributions)
- [License](#-license)
  <br>

## 🔎 About the project

<p align="justify"> 
   A registration form created with <strong>React</strong> and <strong>Typescript</strong> using 
   <em>React-Hook-Form</em> library for form validation.
   It's integrated with <strong>ChakraUI</strong> and with <em>Realtime Database</em> from <strong>Firebase</strong>.
   The form has responsive web design, <em>custom pop-ups</em> messages for each action(create/delete user) and a 
   <em>light/dark mode</em>.
</p>

<div align="center">
  <table>
    <thead>
      <tr>
        <th style="text-align: center">
          Video
        </th>
        <th style="text-align: center">
          Website
        </th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>
          <a href="https://www.youtube.com/watch?v=yN3159m4fnw">
            <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
          </a>
        </td>  
        <td>
          <a href="https://react-firebase-form.vercel.app/">
            <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
          </a>
        </td>  
      </tr>
    </tbody>
  </table>
</div>

<p align="center">
    <img src="https://raw.githubusercontent.com/gabrielpenteado/react-form/main/src/assets/reactform.png"> 
</p>

<div align="center">
  <table>
    <thead>
      <tr>
        <th style="text-align: center">
          <a href="https://raw.githubusercontent.com/gabrielpenteado/react-form/main/src/assets/light.jpg">Light-theme</a>
        </th>
        <th style="text-align: center">
          <a href="https://raw.githubusercontent.com/gabrielpenteado/react-form/main/src/assets/dark.jpg">Dark-theme</a>
        </th>  
      </tr>
    </thead>
  </table>
</div>

### Built with

![react](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![chakraui](https://img.shields.io/badge/Chakra--UI-319795?style=for-the-badge&logo=chakra-ui&logoColor=white)
![firabase](https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white)
<br>

## 🔥 Getting started

To start using this <strong>React form</strong> follow the instructions below.

### Requirements

- npm (^9.5.0)
- react(^18.2.0)
- [vite](https://vitejs.dev/guide/)
- [chakraUI](https://chakra-ui.com/getting-started/vite-guide)
- [react-hook-form](https://react-hook-form.com/get-started)
- [react-password-strength-bar](https://www.npmjs.com/package/react-password-strength-bar)
- [uid](https://www.npmjs.com/package/uid)

### Browsers Support

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/main/src/chrome/chrome_24x24.png" alt="Chrome" />](https://www.google.com/intl/en/chrome/)<br> Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/main/src/edge/edge_24x24.png" alt="Edge" />](https://www.microsoft.com/en-us/edge)<br> Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/main/src/firefox/firefox_24x24.png" alt="Firefox" />](https://www.mozilla.org/en-US/firefox/new/)<br> Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/main/src/safari/safari_24x24.png" alt="Safari" />](https://www.apple.com/br/safari/)<br> Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/main/src/opera/opera_24x24.png" alt="Opera" />](https://www.opera.com)<br> Opera |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                                   ✅                                                                                   |                                                                              ✅                                                                              |                                                                                       ✅                                                                                       |                                                                                ✅                                                                                |                                                                        ✅                                                                         |
|                                                                              last version                                                                              |                                                                         last version                                                                         |                                                                                  last version                                                                                  |                                                                           last version                                                                           |                                                                   last version                                                                    |

### Installation

1. Clone the repository<br>
   `git clone https://github.com/gabrielpenteado/react-form`

2. Access the project folder in the terminal

3. Install all packages dependencies<br>
   `npm install`

4. Add Firebase SDK<br>
   Rename <em>firebase_sample.tsx</em> to <em>firebase.tsx</em> and<br>
   replace the firebase configuration.
   > firebaseConfig {<br>
   > ..."your app's Firebase project configuration"<br>
   > };<br>

_Note: You can run the following command to install latest SDK :_
`npm install firebase`<br>

5. Start testing<br>
   `npm run dev`
   <br>

## 💫 Features

### Light / Dark mode

- The user can choose between a light or dark theme.

### Password strength meter

- A password's strength is measured according to predefined rules and is displayed using a horizontal scale next to the input field.

### Pop-up messages

- Custom pop-up messages are displayed for each action.

## 🤝 Contributions

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)<br>
The foundation of the open source community are the contributions, them inspire us to learn and create. Any contributions are greatly appreciated.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE.md](https://github.com/gabrielpenteado/react-form/blob/main/LICENSE.md) file for details.
<br>
<br>

<div align="center">
  <img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/u/63300269?v=4&h=100&w=100&fit=cover&mask=circle&maxage=7d" />
  <h1>Gabriel Penteado</h1>
  <strong>Full Stack Developer</strong>
  <br/>
  <br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-penteado)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gabrielpenteado)
[![Gmail](https://img.shields.io/badge/gabripenteado@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gabripenteado@gmail.com)
<br />
<br />

</div>
