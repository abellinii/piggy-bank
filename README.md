

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->


<p align="center">
  <a href="https://github.com/abellini/piggy-bank">
    <img src="piggybank.png" alt="Logo" width="300" height="300">
  </a>

  <h1 align="center">Piggy Bank</h1>

  <p align="center">
  Piggy Bank is a savings service powered by the Celo protocol. Saving can be hard! Sometimes we all need a helping hand to reach our goals. Piggy Bank allows anyone, anywhere to set a savings goal and only be allowed to access the money once the goal has been reached.
    <br />
    <a href="https://github.com/abellini/piggy-bank"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://www.piggy-bank.thepassivetrust.com">Web Page</a>
    ·
    <a href="https://github.com/abellinii/piggy-bank/issues">Report Bug</a>
    ·
    <a href="https://github.com/abellinii/piggy-bank/issues">Request Feature</a>
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

[![piggybankscreenshot.png][product screenshot]](https://piggy-bank.thepassivetrust.com)

Here's a blank template to get started:
**To avoid retyping too much info. Do a search and replace with your text editor for the following:**
`github_username`, `repo_name`, `twitter_handle`, `email`


### Built With

* [React](https://reactjs.org/)
* [Celo](https://celo.org/)
* [Solidity](https://docs.soliditylang.org/en/v0.7.4/#)



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
```sh
npm install npm@latest -g
```

### Installation

1. Clone the repo
```sh
git clone https://github.com/abellini/piggybank.git
```
2. Install NPM packages
```sh
npm install
```



<!-- USAGE EXAMPLES --> 
## Usage

### Contracts

```
    -------     =======================     ============================   
   | Proxy |   ║ UpgradeabilityStorage ║ ← ║ OwnedUpgradeabilityStorage ║  
    -------     =======================     ============================   
         ↑               ↑                  ↑          ↑               ↑             
       ---------------------                |      ----------       ----------        
      | UpgradeabilityProxy |               |     | PiggyBank_V0 |  ←  | PiggyBank_V1 |       
       ---------------------                |      ----------       ----------   
                        ↑                   |
                     -------------------------- 
                    | OwnedUpgradeabilityProxy |
                     -------------------------- 
```


_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).



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



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* []()
* []()
* []()





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=flat-square
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=flat-square
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=flat-square
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=flat-square
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=flat-square
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username
[product-screenshot]: images/screenshot.png