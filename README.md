<h1 align="center">
  <img src="https://github.com/Silvio-Ronaldo/beTheHero/blob/master/frontend/src/assets/logo.svg" alt="Be The Hero Logo" height=100 />
</h1>

<p align="center"><strong>🦸‍♀️ Be The Hero's goal is to connect people to NGOs who need help.</strong></br>Developed at OmniStack#11</br>Practical project for study<p>

<p align="center">
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue" alt="Be The Hero is released under the MIT license" />
  </a>
  <a href="https://GitHub.com/Silvio-Ronaldo/beTheHero/graphs/commit-activity">
    <img src="https://img.shields.io/badge/Maintained%3F-yes-brightgreen" alt="Be The Hero is currently maintained by Silvio Ronaldo" />
  </a>
  <a href="https://GitHub.com/Silvio-Ronaldo/beTheHero/network/">
    <img src="https://img.shields.io/github/forks/Silvio-Ronaldo/beTheHero?style=social" alt="This is the number of forks in this repository" />
  </a>
  <a href="https://GitHub.com/Silvio-Ronaldo/beTheHero/stargazers/">
    <img src="https://img.shields.io/github/stars/Silvio-Ronaldo/beTheHero?style=social" alt="This is the number of stars in this repository" />
  </a>
  <a href="https://github.com/Naereen/badges">
    <img src="https://img.shields.io/badge/badge-awesome-brightgreen" alt="Badges are awesome" />
  </a>
</p></br>



<h2>
  📋 Table of contents
</h2>
<ul>
  <li><a href="https://github.com/Silvio-Ronaldo/beTheHero#-status">Status</a></li>
  <li><a href="https://github.com/Silvio-Ronaldo/beTheHero#%EF%B8%8F-demonstration">Demonstration</a></li>
  <li><a href="https://github.com/Silvio-Ronaldo/beTheHero#%EF%B8%8F-running-locally">Running Locally</a></li></br>
  <ul>
    <li><a href="https://github.com/Silvio-Ronaldo/beTheHero#-running-the-backend-server">Running Backend Server</a></li>  
    <li><a href="https://github.com/Silvio-Ronaldo/beTheHero#%EF%B8%8F-running-the-react-app">Running React App</a></li>
    <li><a href="https://github.com/Silvio-Ronaldo/beTheHero#-running-the-mobile-app">Running Mobile App</a></li></br>
  </ul>
  <li><a href="https://github.com/Silvio-Ronaldo/beTheHero#%EF%B8%8F-technologies">Technologies</a></li>
  <li><a href="https://github.com/Silvio-Ronaldo/beTheHero#-author">Author</a></li>
  <li><a href="https://github.com/Silvio-Ronaldo/beTheHero#%EF%B8%8F-license">License</a></li>
</ul></br>



<h2>📌 Status</h2>
<h4 align="center">🦸‍♀️ Be The Hero is complete. 🚀</h4></br>



<h2>🖥️ Demonstration</h2>
<h3>Web Layout</h3>
  <p align="center">
    <img src="./assets/layout.gif" alt="Be The Hero web layout" />
  </p></br>
  
<h3>ONG Register</h3>
  <p align="center">
    <img src="./assets/register.gif" alt="Be The Hero ONG register" />
  </p></br>
  
<h3>New Case</h3>
  <p align="center">
    <img src="./assets/new-case.gif" alt="Be The Hero web new case" />
  </p></br>
  
<h3>Mobile</h3>
  <p align="center">
    <img src="./assets/usage.gif" alt="Be The Hero mobile" />
  </p></br>



<h2>🕹️ Running locally</h2>
<h3>Prerequisites</h3>
<ol>
  <li><strong>Installing Git:</strong> You need to have Git on your machine to perform a few steps. To download Git, click <a href="https://git-scm.com/downloads">here.</a></li></br>
  <li><strong>Installing Node:</strong> To run the server you will need Node.js, to download it, click <a href="https://nodejs.org/en/">here.</a></strong></li></br>
  <li><strong>Installing Expo:</strong> To run the mobile, you need to install the Expo, click <a href="https://docs.expo.io/get-started/installation/">here.</a></li></br>
  <li><strong>Installing Yarn 1:</strong> Yarn is a package manager that you can download directly from the website by clicking <a href="https://classic.yarnpkg.com/en/docs/install#windows-stable">here.</a> If you prefer, use the NPM.</li></br>
  <li><strong>Code Editor (optional):</strong> Make sure you have a code editor of your choice. I recommend using the VS Code. If you need to, download it <a href="https://code.visualstudio.com/Download">here.</a></li>
</ol></br>

<h3>🎲 Running the backend server</h3>
<ol>
  <li>In a terminal, clone this repository:
    <p><code>git clone https://github.com/Silvio-Ronaldo/beTheHero.git</code></p>
  </li>
  <li>Enter the project folder:
    <p><code>cd beTheHero</code></p>
  </li>
  <li>Enter the server folder:
    <p><code>cd backend</code></p>
  </li>
  <li>Install all dependencies:
    <p><code>yarn install</code> or <code>yarn</code></p>
  </li>
  <li>Start the database with Knex migrations:
    <p><code>yarn knex migrate:latest</code></p>
  </li>
  <li>Start the development server:
    <p><code>yarn start</code></p>
  </li>
  <li>After these steps, the server should start at the <strong>3333</strong> port.</li>
  <li>If you want to run the tests, do:
    <p><code>yarn test</code></p>
  </li>
</ol></br>


<h3>⚛️ Running the React app</h3>
<ol>
  <li>If you have already cloned the repository, proceed, otherwise, see step 1 in 'Running the backend server'</li>
  <li>Enter the project folder:
    <p><code>cd beTheHero</code></p>
  </li>
  <li>Enter the web folder:
    <p><code>cd frontend</code></p>
  </li>
  <li>Install all dependencies:
    <p><code>yarn install</code> or <code>yarn</code></p>
  </li>
  <li>Start the web development server:
    <p><code>yarn start</code></p>
  </li>
  <li>After these steps, the server should start at the <strong>3000</strong> port, open the browser and access <a href="http://localhost:3000">http://localhost:3000</a>.</li>
</ol></br>


<h3>📱 Running the Mobile app</h3>
<ol>
  <li>With the Expo installed, according to the documentation, follow</li>
  <li>Enter the project folder:
    <p><code>cd beTheHero</code></p>
  </li>
  <li>Enter the mobile folder:
    <p><code>cd mobile</code></p>
  </li>
  <li>Install all dependencies:
    <p><code>yarn install</code> or <code>yarn</code></p>
  </li>
  <li>Start the mobile development server:
    <p><code>yarn android</code> or <code>yarn ios</code> according to your emulator / device.</p>
  </li>
  <li>After these steps, the mobile application must start on your emulator or on your device, according to your choice.</li>
</ol></br>



<h2>🛡️ Technologies</h2>
<p>The following tools were used in the development of the project: </p>

<h3>Backend</h3>
<ul>
  <li><a href="https://nodejs.org/en/">Node</a></li>
  <li><a href="http://knexjs.org">Knex</a></li>
  <li><a href="https://expressjs.com/pt-br/">Express</a></li>
  <li><a href="https://github.com/arb/celebrate">Celebrate</a></li>
  <li><a href="https://www.sqlite.org/index.html">SQLite</a></li>
  <li><a href="https://www.npmjs.com/package/cors">Cors</a></li>
</ul></br>

<h3>Web</h3>
<ul>
  <li><a href="https://pt-br.reactjs.org">React</a></li>
  <li><a href="https://react-icons.github.io/react-icons/">React Icons</a></li>
  <li><a href="https://github.com/axios/axios">Axios</a></li>
</ul></br>

<h3>Mobile</h3>
<ul>
  <li><a href="https://reactnative.dev">React Native</a></li>
  <li><a href="https://expo.io">Expo</a></li>
  <li><a href="https://docs.expo.io/versions/latest/sdk/mail-composer/">expo-mail-composer</a></li>
  <li><a href="https://reactnavigation.org">React Navigation</a></li>
  <li><a href="https://github.com/software-mansion/react-native-reanimated">React Native Reanimated</a></li>
</ul></br>



<h2>👽 Author</h2>
<table>
  <tr>
    <td align="center"><a href="https://github.com/Silvio-Ronaldo"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/48893927?v=4" width="100px;" alt="Silvio Ronaldo"/><br /><sub><b>Silvio Ronaldo</b></sub></a><br /><a href="https://github.com/Silvio-Ronaldo" title="Silvio Ronaldo">🍀</a></td>
  </tr>
</table>
<p>Leave your star, fork the project or open a pull request ❤️</p>
<p>Contact me on social networks: </p>
<p><a href="https://twitter.com/sivirinoo"><img src="https://img.shields.io/twitter/follow/sivirinoo?style=social" alt="Silvio Ronaldo's Twitter" /></a>
<a href="https://br.linkedin.com/in/silvio-ronaldo77"><img src="https://img.shields.io/badge/-Silvio-blue?style=flat&logo=Linkedin&logoColor=white" alt="Silvio Ronaldo's LinkedIn" /></a></p></br>


<h2>⚖️ License</h2>
<p><strong>Be The Hero is MIT licensed, as found in the <a href="./LICENSE">LICENSE file</a>.</strong></p>





