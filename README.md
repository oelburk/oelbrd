<a name="readme-top"></a>



<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/oelburk/oelbrd">
    <img src="Design/resources/oel-logo-color.png" alt="Logo" height="80">
  </a>

<h3 align="center">OELBRD</h3>

  <p align="center">
    Custom designed keyboard PCB and Firmware
    <br />
    <a href="https://github.com/oelburk/oelbrd/issues">Report Bug</a>
    ·
    <a href="https://github.com/oelburk/oelbrd/issues">Request Feature</a>
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
      <a href="#getting-started">Getting Started (Keymap setup)</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Creating a keymap</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Small project containing the PCB design files (KiCad project) along with the source code for different keymaps for my custom designed 60% keyboard.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [KiCad](https://www.kicad.org/download/windows/)
  * https://github.com/egladman/keebs.pretty
  * https://github.com/tmk/keyboard_parts.pretty
* [QMK](https://qmk.fm/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started (Keymap setup)

This is an example of how you can create your own keymap for the oelbrd.

### Prerequisites
* Text editor of choice
* [QMK](https://github.com/qmk/qmk_firmware/blob/master/docs/newbs.md)

### Creating a keymap

1. Clone the repo
   ```sh
   git clone https://github.com/oelburk/oelbrd.git
   ```
2. Create new folder in keymaps folder
   ```sh
   mkdir QMK/keymaps/my-keymap
   ```
3. Copy default keymap (optional)
   ```sh
   cp QMK/keymaps/default/keymap.c QMK/keymaps/my-keymap
   ```
4. Edit `keymap.c` with preferred layout
5. Compile the new layout using QMK
6. Flash new layout

<p align="right">(<a href="#readme-top">back to top</a>)</p>


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

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Shoutout othneildrew for nice README template](https://github.com/othneildrew/Best-README-Template)
* [Swe Mech Keebs Community](http://mekaniskatangentbord.se/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/oelburk/oelbrd.svg?style=for-the-badge
[contributors-url]: https://github.com/oelburk/oelbrd/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/oelburk/oelbrd.svg?style=for-the-badge
[forks-url]: https://github.com/oelburk/oelbrd/network/members
[stars-shield]: https://img.shields.io/github/stars/oelburk/oelbrd.svg?style=for-the-badge
[stars-url]: https://github.com/oelburk/oelbrd/stargazers
[issues-shield]: https://img.shields.io/github/issues/oelburk/oelbrd.svg?style=for-the-badge
[issues-url]: https://github.com/oelburk/oelbrd/issues
[license-shield]: https://img.shields.io/github/license/oelburk/oelbrd.svg?style=for-the-badge
[license-url]: https://github.com/oelburk/oelbrd/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: Design/oelbrd-mk1.jpg
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
