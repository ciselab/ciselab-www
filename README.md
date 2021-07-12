# Website for the CISELab

This repo contains the sources for the Computational Intelligence for Software Engineering Lab (CISELab) website.
The website is built on top of the popular open-source static site generators [Hugo](https://gohugo.io/) and makes use of the [Wowchemy](https://wowchemy.com/) theme.
The [Netlify](https://gohugo.io/) service is used to host the website.

## Adding material

Material can be added by anyone in any section.
For adding material, check [this documentation](https://wowchemy.com/docs/).

**Note:** Do not directly push your changes to the main branch. Instead, send a Pull Request (PR).

### Adding members

Steps:

1. Run `hugo new --kind authors authors/<firstname-lastname>`
2. Update your information in **content/authors/<firstname-lastname>/index.md**
3. Replace **avatar.{jpg,jpeg,png,webp}** with your photo

### Adding funded projects

Steps:

1. Run `hugo new --kind project project/<my-project-name>`
2. Update the project information in **content/project/<my-project-name>/index.md**
3. Replace **featured.{jpg,jpeg,png,webp}** with the project logo

### Adding publications

Steps:

1. Run `hugo new --kind publication publication/<my-publication>`
2. Update publication information in **content/publication/<my-publication>/index.md**
3. Add the paper at **content/publication/<my-publication>/<my-publication>.pdf** or link to an external version using **url_pdf**
4. Add the BibTex at **content/publication/<my-publication>/cite.bib**

### Adding events

Steps:

1. Run `hugo new --kind event event/<my-talk-name>`
2. Update event information in **content/publication/<my-talk-name>/index.md**

## Build and preview locally

When making changes to the website, it is useful to build and preview the website locally before committing the changes to the repository.
Before you can build the website, you first need to install the following dependencies:

1. Install Hugo using [this documentation](https://gohugo.io/getting-started/installing/).
2. Install NPM using [this documentation](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
3. Install the development dependencies: `npm install`

To preview the website:

1. Run `view.sh`

When an error occurs during building, try deleting the local Hugo cache:

- MacOS/Linux: sudo rm -rf $TMPDIR/hugo_cache/

## Deploy website

The website is automatically deployed whenever a new commit is merged into the main branch.
To see a preview of the changes in a PR, press the details link in the deploy status check.
