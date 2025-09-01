---
permalink: /
layout: docs
---

# Welcome
Welcome to `jekyll-rpi-khk`! Chances are, you're either a member of KHK or a developer looking to get started with a place for your documentation. Perhaps, you're even both! Well, if you are, you've come to the right place. This page will tell you how you can get started with this theme.

## About
This theme was originally forked from the [Raspberry Pi Documentation](https://github.com/raspberrypi/documentation/). I chose the Raspberry Pi theme over many others for two reasons:
1. Has a good layout for documentation
2. Supports <ins>automatically transitioning between light and dark mode based on the visitor's system settings</ins> (you'd be surprised how many Jekyll themes don't)
   - As a bonus, this theme offers a "good" dark mode, where the color that fills most of the screen is true black (hex value #000000)

### Changes made
- Changed the primary color from red to purple (for my use case)
- Converted many hardcoded links and navigation panels into variables configurable in `_config.yml`
- Added support for GitHub-style blockquotes

### My use case
I forked this theme with the intent of hosting documentation on how to run a chapter of [KHK](https://khk.org/). As a member of the Delta chapter, I thought that at the time, our documentation was disorganized, scattered, outdated, and sometimes even nonexistant! Wanting a centralized, version-controlled wiki-style place for our documentation that all members of the fraternity can easily read and edit, I started to explore my options. With that, I started looking for Jekyll themes, but couldn't find any that met my requirements. So, here this is!

For a demonstration of this theme's capabilities, check out the [sample page](/pages/sample-page).

## Getting Started
*Assumes you're on a Linux computer or a Windows computer using the Windows Subsystem for Linux (WSL)*
1. Optionally fork this repository. Clone it to your computer.
2. Configure the theme by editing _config.yaml. You can change the content of many links on the page to suit your needs.
3. Install Ruby. You'll need at least version 3.4.5. [ruby-install](https://github.com/postmodern/ruby-install) and [chruby](https://github.com/postmodern/chruby) are useful here.
4. Install Bundler and Jekyll: `gem install bundler jekyll`
5. Install dependencies: `bundle install`
6. Start your server: `bundle exec jekyll serve`
7. Open your server: http://localhost:4000

## Adding and Editing Documentation
Under the `_data` directory, you'll find a file called `nav.yaml`. This file contains the table of contents for the left sidebar navigation. The file's structure is shown below:
```yaml
- path: /parent1
  title: "Parent 1"
  toc:
  - path: /parent1/child1
    title: "Child 1"
    sections:
    - anchor: first-subheading
      heading: "First Subheading"
    - anchor: second-subheading
      heading: "Second Subheading"
    - anchor: third-subheading
      heading: "Third Subheading"
  - path: /docs/child2
    title: "Child 2"
- path: /parent2
  title: "Parent 2"
  toc:
  - path: /parent2/child3
    title: "Child 3"
    sections:
    - anchor: first-subheading
      heading: "First Subheading"
    - anchor: second-subheading
      heading: "Second Subheading"
    - anchor: third-subheading
      heading: "Third Subheading"
```

## License
[BSD 3-Clause](https://opensource.org/licenses/BSD-3-Clause)