<div id="top"></div>
<!--
*** Credit to the Best-README-Template, https://raw.githubusercontent.com/othneildrew/Best-README-Template/master/BLANK_README.md. 
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]




<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/OrionSkywalker/cs465-fullstack">
    <img src="https://snhu.geigershops.com/store/20161222562/assets/items/largeimages/pi_DZ231C011_l.JPG" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">cs465-fullstack</h3>

  <p align="center">
    CS-465 Full Stack Development with MEAN
    <br />
    <a href="https://github.com/OrionSkywalker/cs465-fullstack"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/OrionSkywalker/cs465-fullstack">View Demo</a>
    ·
    <a href="https://github.com/OrionSkywalker/cs465-fullstack/issues">Report Bug</a>
    ·
    <a href="https://github.com/OrionSkywalker/cs465-fullstack/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Travlr][product-screenshot]](https://example.com)



<p align="right">(<a href="#top">back to top</a>)</p>



### Built With


* [Angular](https://angular.io/)
* [Bootstrap](https://getbootstrap.com)
* [MongoDB](https://github.com/mongodb)
* [Node](https://github.com/nodejs/node)
* [Express](https://github.com/expressjs/express)
* [hbs](https://github.com/pillarjs/hbs)
* [Passport](https://github.com/passport)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is a work in progress. Reviewing the project so installation is a breeze.

### Prerequisites

This is an example of the steps to take to get started.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Install the necessary global features.
2. Clone the repo
   ```sh
   git clone https://github.com/OrionSkywalker/cs465-fullstack.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Run the app from the travlr folder
   ```sh
   npm start
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Update planned for 2022

    - [ ] Remove Deprecated Modules

See the [open issues](https://github.com/OrionSkywalker/cs465-fullstack/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/OrionSkywalker/cs465-fullstack](https://github.com/OrionSkywalker/cs465-fullstack)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments


<p align="right">(<a href="#top">back to top</a>)</p>

## Architecture, Functionality, Testing and Reflection
#### The Angular project structure is different from the Express HTML customer facing pages in that Angular allows movement of data processing and logic to the browser. Some advantages of the SPA functionality are that there is a reduced load on the server and the use of typescript that can be converted to json. Disadvantages of the SPA are that it isn’t crawlable for indexing on search engines. Added functionality provided by a SPA compared to a simple web application interaction includes two-way data binding. The process of testing to make sure that the SPA is working with the API to GET and PUT data in the database that I used was to try and evaluate the http requests with postman, use developer tools in the browser, and console output to monitor with custom output. An error that I ran into while checking the http requests was an improperly formatted request in postman, this provided an error in postman and allowed me to see the problem. Mostly, I tested with the localhost route and observed feedback from console output with developer tools. MongoDB was used because of the use of JSON everywhere and the availabilithy of Mongoose to manage relationships to data.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/orionskywalker/cs465-fullstack?style=flat-square
[contributors-url]: https://github.com/OrionSkywalker/cs465-fullstack/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/orionskywalker/cs465-fullstack?style=flat-square
[forks-url]: https://github.com/OrionSkywalker/cs465-fullstack/network/members
[stars-shield]: https://img.shields.io/github/stars/orionskywalker/cs465-fullstack?style=social
[stars-url]: https://github.com/OrionSkywalker/cs465-fullstack/stargazers
[issues-shield]: https://img.shields.io/github/issues/orionskywalker/cs465-fullstack
[issues-url]: https://github.com/OrionSkywalker/cs465-fullstack/issues
[license-shield]: https://img.shields.io/github/license/orionskywalker/cs465-fullstack
[license-url]: https://github.com/OrionSkywalker/cs465-fullstack/blob/main/LICENSE
[product-screenshot]: https://github.com/OrionSkywalker/cs465-fullstack/blob/main/public/images/forRepo.png
