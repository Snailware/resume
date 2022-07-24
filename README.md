<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<div align="center">

  <h3 align="center">Resume</h3>

  <p align="center">
    a resume in the form of a website.
    <br />
    <a href="https://github.com/Snailware/resume"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Snailware/resume/issues">Report Bug</a>
    ·
    <a href="https://github.com/Snailware/resume/issues">Request Feature</a>
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

<p align="left">This project is meant to serve as a resume. While its already hosted <a href="https://snailware.github.io/resume/">here</a> using <a href="">Github Pages</a>, a Dockerfile and associated instructions are also included to containerize a local version of the website with an Apache web server. </p>

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

-   [Bootstrap 5](https://getbootstrap.com/)
-   [Apache](https://www.apache.org/)
-   [Docker](https://www.docker.com/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

-   [Git](https://git-scm.com/) -> [Git for Windows/Mac/Linux](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
-   [Docker](https://www.docker.com/) -> [Docker Desktop for Windows/Mac/Linux](https://docs.docker.com/get-docker/)

### Installation

1.  [Download ZIP](https://github.com/Snailware/resume/archive/refs/heads/master.zip) and extract contents, **or** clone the repo:

    ```sh
    git clone https://github.com/Snailware/resume.git
    ```

2.  Navigate into the `resume` directory:

    ```sh
    cd resume
    ```

3.  Build a Docker image using the included Dockerfile:

    ```sh
    docker build -t resume:v1 .
    ```

4.  Run a container using the image we created:

    ```sh
    docker run -d -p 6969:80 resume:v1
    ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

Once your container is running, simply point your browser <a href="http://localhost:6969">here</a> to view the web site!

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/Snailware/resume/issues) for a full list of proposed features (and known issues).

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

Distributed under the GPL-3.0 License. See [LICENSE](https://github.com/Snailware/resume/blob/master/LICENSE) for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

<!--Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com -->

Project Link: [https://github.com/Snailware/resume](https://github.com/Snailware/resume)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

-   [Othneil Drew](https://github.com/othneildrew) - `README.md` created using [Best-README-Template](https://github.com/othneildrew/Best-README-Template).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
<!--
[contributors-url]: https://github.com/Snailware/resume/graphs/contributors
[forks-url]: https://github.com/Snailware/resume/network/members
[stars-url]: https://github.com/Snailware/resume/stargazers
[issues-url]: https://github.com/Snailware/resume/issues
[license-url]: https://github.com/Snailware/resume/blob/master/LICENSE
-->
