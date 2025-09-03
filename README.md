# jekyll-rpi-khk
[Raspberry Pi Documentation Website HTML, CSS, and JS](https://github.com/raspberrypi/documentation/) modified for my use case.

## To-Do's
- Figure out the boxes layout

## Changes Made
- Changed the primary color from red to purple (for my use case)
- Converted many hardcoded links and navigation panels into variables configurable in `_config.yml`
- Added support for GitHub-style blockquotes
- Replaced Algolia search with [Lunr](https://lunrjs.com/)

## Quick Start
1. Clone the repository: `git clone https://github.com/RichardLamb1/jekyll-rpi-khk.git`
2. Install Ruby. You'll need at least version 3.4.5. [ruby-install](https://github.com/postmodern/ruby-install) and [chruby](https://github.com/postmodern/chruby) are useful here.
3. Install Bundler and Jekyll: `gem install bundler jekyll`
4. Install dependencies: `bundle install`
5. Start your server: `bundle exec jekyll serve`
6. Open your server: http://localhost:4000

See the [Jekyll](https://jekyllrb.com/) website for more information.

## License
[BSD 3-Clause](https://opensource.org/licenses/BSD-3-Clause)