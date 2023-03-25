# Plain Vanilla GitHub Pages README
The purpose of this project is to make as easy as possible for less-technical people to create and host basic web pages for free on [GitHub Pages](https://pages.github.com/).

[Check out my YouTube video on how to get started using this template](https://youtu.be/jlkHEmgQhGU)

## Getting started

### Copying the template and setting up publishing
1. Press the `Use this template` button on the `Code` tab.
1. Go to the `Settings` tab and then go to the `Pages` settings.
1. Set the `Source` to `main` and press `Save`.

You'll see a URL show up, but the site takes a few minutes before it's actually live. In the meantime, try creating a page.

### Creating your first page
1. Go to the `Code` tab.
1. Press the `Add File` button and select `Create new file`.
1. Name the page, for example, `first-page.md`. (Note the lack of spaces and the inclusion of the .md extension.)
1. Add a title in the front matter:
    ```
    ---
    title: First Page
    ---
    ```
1. Add some content using [markdown](https://guides.github.com/features/mastering-markdown/) syntax. For example, you could start with a heading and paragraph like this:
    ```
    # First page
    This is my first page.
    ```
5. Scroll down to the bottom of the page and press `Commit new file`.

### Checking your page online
1. On the Code tab, find and press the `Environments` link. (It may be in the right column.)
1. On the next page (Deployments), press the `View deployment` button. (You should see the default homepage load.)
1. In the address bar of the browser, add the name of your page _using the HTML extension_ and press return. For example: `first-page.html`. (The full address will be something like this: `https://pglevy.github.io/plain-vanilla-gh-pages/first-page.html`)

You should see the new page you created.

## Next steps
Now that you know how to create pages, here are some other things you can do:
- Create more pages.
- Update `index.md` (the homepage) with your own content.
- Add links between pages so it works like a website.
- Copy component code snippets from the [GitHub Primer design system](https://primer.style/css/components) to add more advanced functionality to your pages.

## Default `body` and `main` styling classes
- By default, the `body` element includes the `p-3` utility class from Primer. This adds some padding to the page on all sides.
- The `main` element includes these two classes: `container-md` and `markdown-body`. The first one sets a maximum width for the content area and the second provides the default GitHub styling for Markdown content.
- To override these, add these settings to the front matter of your content page: `body-style` and `main-style`.

For example:
```
title: Home
body-style: p-0
main-style: container-lg
```

If you want to replace the defaults with nothing, do this:
```
title: My Page
body-style: ""
main-style: ""
```

## Local CSS
If you want to work locally and/or offline, you can use a local copy of the Primer CSS instead of referencing the hosted version. Note the local copy may not be the latest version because it will need to kept up-to-date manually.

To switch to local CSS, replace this line in `_layouts/default.html`:
```
<link rel="stylesheet" href="https://unpkg.com/@primer/css/dist/primer.css">
```

with this:
```
<link rel="stylesheet" href="assets/css/primer.css">
```

## What to do if you're having problems
- Try starting over with a new repository and follow the instructions again.
- If it's still not working, [create an issue in the original Plain Vanilla GitHub Pages repo](https://github.com/lowcodelounge/plain-vanilla-gh-pages/issues), and I'll try to help.

## Getting started with Gitpod
Gitpod is a cloud-based development environment that allows you to work with code and static site compilers without having to install software on your local machine.

To use Gitpod:
1. [Create a copy](https://github.com/lowcodelounge/plain-vanilla-gh-pages/generate) of the repo template.
2. [Log into Gitpod](https://gitpod.io/login/) using your GitHub account.
3. [Open a new workspace using this Gitpod link](https://gitpod.io/#https://github.com/lowcodelounge/plain-vanilla-gh-pages/tree/main).

What happens next:
- An instance of the VS Code text editor opens in your browser.
- You may see some things happening in the Terminal panel.
- When it's finished, you'll see a message that says `Server running... press ctrl-c to stop.` in the Terminal panel.
- Your browser may block the pop-up that tries to open.
- If you don't see the live site, command-click the URL on this line in the Terminal panel: `Server address: http://127.0.0.1:4000`

## Building the running the site locally on your computer (for advanced users)
To run the site locally, you'll need to install [Jekyll](https://jekyllrb.com/), which requires a few steps. See the [official installation instructions](https://jekyllrb.com/docs/installation/).

## Credit and license
This project was created using the [GitHub Pages gem for Jekyll](https://github.com/github/pages-gem). It is licensed under [The Unlicense](https://github.com/pglevy/plain-vanilla-gh-pages/blob/main/LICENSE), which allows everything and promises nothing. 😎

Favicon is `Soft Ice Cream` from [Twemoji](https://twemoji.twitter.com/), licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).