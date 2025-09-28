# Safwan Safat — Personal Website

This repository contains the source code for my personal website, hosted with **GitHub Pages** using the [Jekyll Primer Theme](https://github.com/pages-themes/primer).

**Live site:** [https://sfwnsft.github.io](https://sfwnsft.github.io)

## About

The site serves as my online presence where I share Quick introduction, contact links, selected software projects with GitHub links, and online version of my resume with a downloadable PDF.

## Built With

* [Jekyll](https://jekyllrb.com/)
* [jekyll-theme-primer](https://github.com/pages-themes/primer)
* GitHub Pages

## Project Structure

```text
|
├── _config.yml        # Site configuration
├── index.md           # Homepage
├── projects.md        # Projects page
├── resume.md          # Resume page
├── assets/
│   ├── files/         # Resume PDF and other downloadable files        
└── README.md          
```

## Running Locally

1. Clone the repository:

```bash
git clone https://github.com/sfwnsft/sfwnsft.github.io.git
cd sfwnsft.github.io
```

2. Install Jekyll & Bundler:

```bash
gem install bundler jekyll
```

3. Run the site locally:

```bash
bundle install
bundle exec jekyll serve
```

4. Open in browser: `http://localhost:4000`

## License

This repository is published under the [MIT License](LICENSE).
Feel free to fork, adapt, and use, but please give credit.
