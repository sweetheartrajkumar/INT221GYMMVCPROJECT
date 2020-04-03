![Laravel-shield][Laravel-shield]
![Voyager-shield][Voyager-shield]
![Stage][Stage]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<link rel="shortcut icon" href="http://www.iconj.com/ico/0/j/0jfxz36x0g.ico" type="image/x-icon" />

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/cristianmarint/MotionGym">
    <img src="docs/imgs/logo.png" alt="Logo" width="120" height="120">
  </a>

  <h3 align="center">Motion Gym</h3>

  <p align="center">
A open source gym management system build.
    <br />
    <a href="https://cristianmarint.github.io/MotionGym/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/cristianmarint/MotionGym/issues">Report Bug</a>
    ·
    <a href="https://github.com/cristianmarint/MotionGym/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

<img src="docs/imgs/Landing_page.gif" alt="drawing" width="1920"/>

There are many of gym management systems instead of using one of those I decided to build one with Laravel 5.8 using the package Voyager 1.2 to make the proccess quicker and easier for basic operations (BREAD).  
<br>
Of course, this project may not be current suilble for a big business but it will improve with time. keep in mind that it's in early development stateges. Therefore, if you want to get involve feel free to do so.

[![Login & admin][login-admin]](https://github.com/cristianmarint/MotionGym)

### Built With
* [Laravel](https://laravel.com)
* [Voyager](https://laravelvoyager.com/)
* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)
* [VueJs](https://vuejs.org/)



## Getting Started

This is an example of how you can set up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

You must have [Composer](https://getcomposer.org/download/) and a DB server.
Its recommend to use [Xampp](https://www.apachefriends.org/es/index.html) or [Mamp](https://www.mamp.info/en/downloads/) for starters.

### Installation


1. Install composer
`composer install`
2.  Migrate database
`php artisan migrate`
3. Seed database
`php artisan db:seed`
4. Create your own admin user
`php artisan voyager:admin your_email@provider.com --create `




<!-- USAGE EXAMPLES -->
## Usage

Currently there are no useful example due to early stages.



<!-- ROADMAP -->
## Roadmap
See the [open issues](https://github.com/cristianmarint/MotionGym/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


