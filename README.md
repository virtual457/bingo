<!-- Improved compatibility of back to top link: See: https://github.com/dhmnr/skipr/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">🎯 Bingo Game</h3>

  <p align="center">
    An interactive web-based Bingo game built with HTML, CSS, and JavaScript featuring real-time win detection and responsive design.
    <br />
    <a href="https://github.com/virtual457/bingo"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/virtual457/bingo">View Demo</a>
    ·
    <a href="https://github.com/virtual457/bingo/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/virtual457/bingo/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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

Bingo Game is a fully functional web-based implementation of the classic Bingo game. Built with vanilla HTML, CSS, and JavaScript, this project demonstrates modern web development practices while providing an engaging gaming experience.

The game features a 5x5 Bingo card with real-time win detection for horizontal, vertical, and diagonal patterns. Players can mark numbers as they're called, and the system automatically detects winning combinations.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Features

- **Interactive Gameplay**: Click to mark numbers on your Bingo card
- **Real-time Win Detection**: Automatic detection of winning patterns (horizontal, vertical, diagonal)
- **Responsive Design**: Works seamlessly across different screen sizes
- **Bootstrap Integration**: Modern UI components using Bootstrap framework
- **Win Pattern Tracking**: Tracks multiple winning patterns simultaneously
- **Clean User Interface**: Intuitive and user-friendly design

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### How It Works

The game uses a 5x5 grid system where each cell represents a number on the Bingo card. When a player clicks on a number, it gets marked and the system checks for winning patterns:

1. **Horizontal Lines**: Checks all 5 rows for complete matches
2. **Vertical Lines**: Checks all 5 columns for complete matches  
3. **Diagonal Lines**: Checks both diagonal patterns (top-left to bottom-right and top-right to bottom-left)

The win detection algorithm uses an array-based tracking system to efficiently monitor the game state and identify winning combinations in real-time.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) - Semantic markup structure
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) - Styling and layout
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Game logic and interactivity
- [Bootstrap 3.3.7](https://getbootstrap.com/docs/3.3/) - UI framework and responsive design

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/virtual457/bingo.git
   ```
2. Open the project folder
   ```sh
   cd bingo
   ```
3. Open `bingo.html` in your web browser
   ```sh
   # Double-click the file or drag it into your browser
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

1. **Start the Game**: Open `bingo.html` in your web browser
2. **Mark Numbers**: Click on any number on your Bingo card to mark it
3. **Track Progress**: The game automatically tracks your progress
4. **Win Detection**: When you complete a line (horizontal, vertical, or diagonal), the game will detect your win
5. **Multiple Wins**: You can achieve multiple winning patterns simultaneously

### Game Rules

- Mark numbers as they are called during the Bingo game
- Complete any horizontal, vertical, or diagonal line to win
- Multiple winning patterns can be achieved on the same card
- The game tracks all possible winning combinations automatically

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] Add sound effects for marking numbers
- [ ] Implement a number caller feature
- [ ] Add multiplayer support
- [ ] Create different card themes
- [ ] Add game statistics tracking
- [ ] Implement save/load game state
- [ ] Add mobile touch support optimization

See the [open issues](https://github.com/virtual457/bingo/issues) for a full list of proposed features (and known issues).

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

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Chandan Gowda K S - chandan.keelara@gmail.com

Project Link: [https://github.com/virtual457/bingo](https://github.com/virtual457/bingo)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Bootstrap](https://getbootstrap.com/) - CSS framework for responsive design
* [MDN Web Docs](https://developer.mozilla.org/) - Excellent web development documentation
* [GitHub Pages](https://pages.github.com) - Hosting platform for web projects
* [Choose an Open Source License](https://choosealicense.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/virtual457/bingo.svg?style=for-the-badge
[contributors-url]: https://github.com/virtual457/bingo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/virtual457/bingo.svg?style=for-the-badge
[forks-url]: https://github.com/virtual457/bingo/network/members
[stars-shield]: https://img.shields.io/github/stars/virtual457/bingo.svg?style=for-the-badge
[stars-url]: https://github.com/virtual457/bingo/stargazers
[issues-shield]: https://img.shields.io/github/issues/virtual457/bingo.svg?style=for-the-badge
[issues-url]: https://github.com/virtual457/bingo/issues
[license-shield]: https://img.shields.io/github/license/virtual457/bingo.svg?style=for-the-badge
[license-url]: https://github.com/virtual457/bingo/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/chandan-gowda-k-s-765194186/
