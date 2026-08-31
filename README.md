# jerbersoft.github.io

The index page at <https://jerbersoft.github.io/>, listing the open-source projects and linking to
the documentation each one publishes.

It is one static `index.html` with no build step and no dependencies. `.nojekyll` turns off the
Jekyll pipeline that GitHub Pages would otherwise run — there is nothing here for it to process.

**This repository is not the personal site.** <https://herbertsabanal.com> is an Astro site served
by Cloudflare and lives elsewhere. This one exists because a `<user>.github.io` repository is the
only thing that can serve `jerbersoft.github.io/`, and GitHub does not allow its Pages site to be
switched off.

> It previously held a `beautiful-jekyll` fork whose `CNAME` set a custom domain. A custom domain on
> the *user* Pages site rewrites every project page under the account, so
> `jerbersoft.github.io/databentodotnet` redirected off-site and 404'd. Removing that domain is what
> let the project documentation sites work at all; this page is what replaced the fork.
