<!--
**** THIS README IS GENERATED FROM
**** https://github.com/othneildrew/Best-README-Template
**** UNDER MIT LICENSE
--->

<h1 align="center">emergencyWebPage-Template</h1>

<p align="center">
  🚑 Emergency Purposed Web Pages Template
  <!-- Badges -->
  <br />
  <br />
  <a href="LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/nattadasu/emergencyWebPage-template?style=for-the-badge"></a>
  <a href="https://github.com/nattadasu/emergencyWebPage-template/issues"><img src="https://img.shields.io/badge/Issue-GitHub-black?style=for-the-badge&logo=github"></a>
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/nattadasu/emergencyWebPage-template?style=for-the-badge">
  <a href="CODE_OF_CONDUCT.md"><img src="https://img.shields.io/endpoint?style=for-the-badge&url=https%3A%2F%2Fraw.githubusercontent.com%2Fnattadasu%2FemergencyWebPage-Template%2Fmain%2Fconfig%2Fcc.shield.json"></a>

</p><br />

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#privacy-concern">Privacy Concern</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#creating-new-repo-with-this-repo">Creating New Repo With
        This Repo</a></li>
        <li><a href="#development">Development</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project is actually a form of worry of [the maintainer](#contact) if in
some case you need a emergency assistance, a cellphone that is brought does not
have power and does not have backup power.

For data serialization, we utilize [HJSON](https://hjson.github.io) and
[YAML](https://yaml.org/) as we aim this project to be beginner friendly and
not being *overwhelmed* with how JSON works. However, at the end result, those
one of formats will be converted to JSON for compatibility.

This site will be only accessible via QR Code attached on user's ID card(s) or
customized emergency card user made. To achieve this, this repo by default
contains [`robots.txt`](robots.txt) and `noindex` meta tag in
[`index.html`](index.html) to ask web scrappers like Google, Microsoft Bing, etc
to not scrape the site.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

At the moment, this project is using [W3.JS](https://www.w3schools.com/w3js/)
and [W3.CSS](https://www.w3schools.com/w3css/) to maintain lightweight of the
site, as we require this site to load ASAP.

However, to maintain simplicity and faster deploy, this repo was engineered to
be suitable with [GitHub Pages](https://guides.github.com/features/pages/)
without/less configuration required.

<p align="right">(<a href="#top">back to top</a>)</p>

### Privacy Concern

As this project will ask you several sensitive information such as:

* Real name,
* Birth date and place,
* Nationality,
* Address,
* Phone number,
* Medical information, such as:
  * Allergies,
  * Surgeries,
  * Medical condition, and
* Emergency contacts

We want you to keep the information secret by following this steps:

1. Make the repo private\
   This can ensure only you are able to maintain and protect your own data.
2. Do not delete [`robots.txt`](robots.txt) and/or any `<head>` tag contents on
   HTML files\
   Those two files contain traffic control for search engine scraping bot to not
   put the site to the search result.
3. Do not use any 3rd party service\
   Such as: short link generator, web hosting, etc. Their Privacy Policy and/or
   Term of Service may able to reveal your identity to public.
4. Do not reveal your website to public\
   As search engine may able to scrape your website from the site you're sharing
   to.

However we can not guarantee if your data will be safe even we stated the steps
that we believe will help you to secure your data.

**Note**:\
**THIS IS NOT A LEGAL NOR PRIVACY ADVICE**. Please to consult to your local law
enforcement to assist/suggest you on how to keep your data safe or resolving
with data leaks.
<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Below list things you need to use the software and how to install them.

* [`git`](https://git-scm.com)
* [Visual Studio `code`](https://code.visualstudio.com/) (recommended)\
  Used for code editing.
* [`node`](https://nodejs.org/)\
  Required for `npm`. Use the latest LTS version.

<p align="right">(<a href="#top">back to top</a>)</p>

### Creating New Repo With This Repo

> Below is the short summary for the instruction in how to make a repo using
> this template repo.
>
> For more information, please head to [USAGE.md](USAGE.md),

1. Click "Use this template" button at the right of "Code" dropdown, or
   [**click here**](https://github.com/nattadasu/emergencyWebPage-template/generate).
   * Make sure you have logged in to GitHub, otherwise the button is missing or
     link is invalid.

2. Once the repo created, clone the repo to your machine

   ```sh
   git clone https://github.com/<YOUR USERNAME>/<YOUR REPO NAME>.git
   ```

3. Install `npm` packages

   ```sh
   npm install
   ```

4. By your preferred file:

   * HJSON

     ```sh
     npm run prepare:hjson
     ```

   * YAML

     ```sh
     npm run prepare:yaml
     ```

<p align="right">(<a href="#top">back to top</a>)</p>

### Development

> Below is the short summary for the instruction in how to contribute to this
> template repo.
>
> For more information, please head to [CONTRIBUTING.md](CONTRIBUTING.md),

1. Fork this repo
2. Clone the repo

   ```sh
   git clone https://github.com/<YOUR USERNAME>/emergencyWebPage-Template.git
   ```

3. Install `npm` packages

   ```sh
   npm install
   ```

4. Check if node dependencies up-to-date

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Please head to [contributing.md](CONTRIBUTING.md) for more detailed information.

This project and everyone participating in it is governed by the
[Contributor Covenant Code of Conduct version 2.0][conduct]. By participating,
you are expected to uphold this code. For detailed information, read
[CODE_OF_CONDUCT.md][conduct].

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the [The Unlicensed License][license]. See
[`LICENSE`][license] for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Sultan Iskandar Maulana a.k.a Natsu Tadama (@nattadasu) — hello@nattadasu.my.id

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[conduct]: CODE_OF_CONDUCT.md
[license]: LICENSE

<p align="right">(<a href="#top">back to top</a>)</p>