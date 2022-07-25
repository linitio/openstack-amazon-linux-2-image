<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.png" alt="Logo" width="105" height="150">
  </a>

<h3 align="center">Amazon Linux 2 image for OpenStack</h3>

  <p align="center">
    Simple port of Amazon Linux 2 AMI for OpenStack environements
    <br />
    <a href="https://github.com/linitio/openstack-amazon-linux-2-image"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/linitio/openstack-amazon-linux-2-image/issues">Report Bug</a>
    ·
    <a href="https://github.com/linitio/openstack-amazon-linux-2-image/issues">Request Feature</a>
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

This project is a simple port of Amazon Linux 2 AMI from Amazon Web Services  for OpenStack environments.  
This image is strictly the same that the original, the only change has been made is adding OpenStack datasource for cloud-init.  

This image is updated when AWS released a new version on their public repository [here](https://cdn.amazonlinux.com/os-images/latest/ "AWZ Images Repository").


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### How to use this image

1. Set your OpenStack environement variables
2. Download the latest image from release page
3. Upload image to your OpenStack environment
   ```sh
   openstack image create --disk-format=qcow2 --container-format=bare --min-disk 25 --file amzn2-kvm-2.0.20220606.1-x86_64.xfs.gpt.qcow2  'Amazon Linux 2'
   ```

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

Distributed under the GPL-2.0 License. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Kevin Allioli - [@linit_io](https://twitter.com/linit_io) - kevin@linit.io

Project Link: [https://github.com/linitio/openstack-amazon-linux-2-image](https://github.com/linitio/openstack-amazon-linux-2-image)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/linitio/openstack-amazon-linux-2-image.svg?style=for-the-badge
[contributors-url]: https://github.com/linitio/openstack-amazon-linux-2-image/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/linitio/openstack-amazon-linux-2-image.svg?style=for-the-badge
[forks-url]: https://github.com/linitio/openstack-amazon-linux-2-image/network/members
[stars-shield]: https://img.shields.io/github/stars/linitio/openstack-amazon-linux-2-image.svg?style=for-the-badge
[stars-url]: https://github.com/linitio/openstack-amazon-linux-2-image/stargazers
[issues-shield]: https://img.shields.io/github/issues/linitio/openstack-amazon-linux-2-image.svg?style=for-the-badge
[issues-url]: https://github.com/linitio/openstack-amazon-linux-2-image/issues
[license-shield]: https://img.shields.io/github/license/linitio/openstack-amazon-linux-2-image.svg?style=for-the-badge
[license-url]: https://github.com/linitio/openstack-amazon-linux-2-image/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/kevinallioli
[product-screenshot]: images/screenshot.png
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
