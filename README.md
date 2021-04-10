![Status](https://img.shields.io/github/deployments/Bleeding-Action-Man/Bleeding-Action-Man.github.io/github-pages?style=flat-square) ![Size](https://img.shields.io/github/languages/code-size/Bleeding-Action-Man/Bleeding-Action-Man.github.io?style=flat-square) ![Last_Commit](https://img.shields.io/github/last-commit/Bleeding-Action-Man/Bleeding-Action-Man.github.io?color=purple&style=flat-square)

# General

You can visit it here: [Bleeding-Action-Man.github.io](https://Bleeding-Action-Man.github.io/)

## Base theme credits

Theme used: [Moving](https://github.com/huangyz0918/moving), heavily modified by `Vel-San` with plugins & UI changes to his likings.

## Development & previewing changes before pushing

Assuming you already have the [Jekyll](https://jekyllrb.com/docs/installation/#guides) enviroment installed, you just need to navigate to the repo directory after cloning and run this:

> bundle install

Once finished, navigate to _config.yml and scroll down to `remote_theme: XXX`, comment this and uncomment `theme: XXX`. This is **ONLY DONE** in development mode a.k.a *locally*! You need to revert back to `remote_theme: XXX` before pushing your commited changes.

Now, run `bundle exec jekyll serve` and open your browser at http://localhost:4000. This starts a Jekyll server. Add your posts in the `_posts` directory, following the exact naming convention as the other posts (also, make sure you are creating them in `.md`). As you make modifications to the new content, the site will regenerate and you should see the changes in the browser after a refresh, just like normal.