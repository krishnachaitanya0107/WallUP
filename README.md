<div id="top"></div>

[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/justdvnsh)
[![Patreon][patreon-shield]][patreon-url]
[![Slack][slack-shield]][slack-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="">
    <img src="./docs/app-icon.jpg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">WallUp</h3>

  <p align="center">
    An awesome app to download wallpapers for your phone. No ads ! I promise. 
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/justdvnsh/WallUP/issues">Report Bug</a>
    ·
    <a href="https://github.com/justdvnsh/WallUP/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

The project aims to solve a personal problem of downloading good quality wallpapers in my phone.   

Why a wallpaper app ? Here's why:
* There are already a lot of wallpaper apps, but the thing is that, they are optimized to show you the wallpapers only for your phone, i.e. they will only find the wallpapers of the screen resolution of your phone. So to download higher quality wallpapers you'd anyhow need to download from your browser. Now, this app can help you solve that feature as well.
* Most of the wallpaper apps, show you the wallpaper which are curated by themselves or using any API. This app parses the a lot of resources to provide you with the highest quality unique wallpapers.
* There are no ads. 

__WARNING: THIS PROJECT IS STILL IN HEAVY DEVELOPMENT, THEREFORE YOU MAY ENCOUNTER BUGS. You can OPEN the ISSUE on GITHUB REPOSITORY.__

__NEW ISSUES WILL BE ADDED REGULARLY__ 
  
__DO NOT PUT WALLUP OR ANY FORK OF IT INTO GOOGLE PLAYSTORE or Any other Store. It may VIOLATE THEIR TERMS AND CONDITIONS or you may encounter legal obligations.__

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

Simply fork the repo. Clone it into your machine and let AndroidStudio handle the rest.

<!-- ROADMAP -->
## Roadmap for Version 1 release of the app.

- [x] ~Add README~
- [x] ~Setup a clean architecture for the app~
- [x] Parse Wallpapers
    - [x] ~Parse Wallpaper Details~
        - ~Create a new modern UI for the Wallpaper Detail fragment~
    - [x] ~Add Wallpaper Search option~
        - Handle the errors when wallpaper or collection not found
    - Handle the network error (When not connected to internet)
    - Handle cases when the unwanted errors occur
        - ~Could Not Parse Exception~
        - Could Not Load Exception
    - Make the background function calls more efficient.
- [x] Setup Favorites page
    - Make a viewpager to display all the saved wallpapers in one tab, while all the saved collections in the other.
    - setup room to save the details
    - make a modern motion layout based UI for the page.
- [x] Setup Settings page
    - Multi-language Support
    - dark mode toggle
    - downloaded videos
    - about
    - help
    - FAQ's 
- Setup a new module to provide glide dependencies
- Setup a new module to provide coroutines dependencies
    - load glide components in a background thread.
- A new modern color scheme for the app.

See the [open issues](https://github.com/justdvnsh/WallUP/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "feature-request".
Don't forget to give the project a star! Thanks again!

__NOTE -> Every PR will be reviewed before merging.__

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

#### PLEASE MAKE SURE TO REMOVE THE .idea/ files before pushing a commit

__Want to support me by buying me a coffee ?__ [!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/justdvnsh)

__Want to contribute to this project by supporting us through money ?__ [![Patreon][patreon-shield]][patreon-url]

__Want to join the discussions ?__ [![Slack][slack-shield]][slack-url]

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Divyansh Dwivedi - [@justdvnsh](https://linkedin.com/in/justdvnsh) - justdvnsh2208@gmail.com

Project Link: [https://github.com/justdvnsh/WallUP](https://github.com/justdvnsh/WallUP)

Join the Discussion at: [![Slack][slack-shield]][slack-url]

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/justdvnsh
[product-screenshot]: images/screenshot.png
[patreon-shield]: https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white
[patreon-url]: https://www.patreon.com/justdvnsh
[slack-shield]: https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white
[slack-url]: https://join.slack.com/t/animeclassroom/shared_invite/zt-wut0t5mp-Y4kF6OGyxLBpyNM0eU6psw