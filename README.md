# README

This is the github pages source repo for the custom domain [www.oscar.nierstrasz.org](https://www.oscar.nierstrasz.org).

This repo has been forked from the [academicpages theme repo](https://github.com/academicpages/academicpages.github.io) (master branch).
New content is exclusively on the `gh-pages` branch so updates can be fetched and merged.

---
# Changes

- Removed old repo
- Forked [academicpages.github.io](https://github.com/academicpages/academicpages.github.io) to this repo (`onierstrasz.github.io`)
- Created a new branch `gh-pages`
- Changed `Setting>Pages` to deploy from the `gh-pages` branch
- Set custom domain to www.oscar.nierstrasz.org
- Added new `README` (moved old one to [README-academicpages.md](README-academicpages.md))
- Configured `_config.yml` for sidebar
- Updated `_pages/about.md`
- Fixed the css for links pages and archive in `_sass`

---
# AcademicPages FAQ

See the [academicpages overview](https://academicpages.github.io) as well as the [minimal mistakes quick start guide](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).
Also see [Pooja Rani's website](https://poojaruhal.github.io) and the [github repo](https://github.com/poojaruhal/poojaruhal.github.io) as an example.

To make it easy to pull updates from the academicpages theme, the website contents are on a separate `gh-pages` branch.
See [Publishing from a branch](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
To pull and merge updates, there are [various possible strategies](https://stackoverflow.com/questions/20101994/how-to-git-pull-from-master-into-the-development-branch).

* **Q** How to adjust the CSS?

Update the SCSS files in the `_sass` folder.

* **Q** Where to put files other than papers?

Put all downloads in the `files` folder.

* **Q** How to configure the top and top corner menus?

See _data/navigation.yml

* **Q** How to control the link generation in the sidebar?

See: `_includes/author-profile.html`
In particular the YouTube and Wikipedia links can be changed.
Other links can be added ... (need icons).

---
