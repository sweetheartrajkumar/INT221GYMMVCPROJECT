![Laravel-shield][Laravel-shield]
![Voyager-shield][Voyager-shield]
![Stage][Stage]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]



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






<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


