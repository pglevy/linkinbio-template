# Link in bio template
Template for creating a simple “link in bio” site using [GitHub Pages](https://pages.github.com/).

<img width="1032" alt="linkinbio-template-screenshot" src="https://user-images.githubusercontent.com/5177337/227823745-ffb6acf3-fd3d-422f-b118-58ec50a72143.png">

## Getting started

### Copying the template and setting up publishing
1. Press the `Use this template` button on the `Code` tab and select `Create a new repository`.
1. Go to the `Settings` tab and then go to the `Pages` settings.
1. Set the source branch to `main` and press `Save`.

You'll see a URL show up, but the site takes a few minutes before it's actually live.

## Swapping out your content

This is the content you'll want to update with your info:

1. Name and profile blurb
1. Avatar image and alt text
1. Links
1. Interests (Optional)
1. Metadata

### Name and profile blurb

- Open `index.md` and change the `avatar-name` setting to your name.
- Use the content area to write your profile blurb. Use GitHub-flavored Markdown for formatting.

### Avatar image and alt text

- If you don't have an existing image online to use, upload one and copy the URL.
  - Go to the `assets/img` folder in your repo and use the `Add file` action.
- Open `index.md` and change `avatar-url` to the url of your image.
  - For example, `assets/img/YOUR-FILE.jpg`
  
### Links

- Open `_data/links.yml` and change the list of items, using the text, URL, and icon you want for each link.
  - See [Bootstrap Icons](https://icons.getbootstrap.com/) for the names of the icons.
  
### Interests

- Open `data/interests.yml` and change the list of items.
  - Put each item on a new line preceded by a hyphen and a space (`- `).
  - If you want to change the text preceding the interests, open `index.md` and change the `interest-prefix` setting.

### Metadata

- Open `data/metadata.yml` to change the site title, description, and language information used by browsers and search engines.

## Credit and license
This project was created using the [GitHub Pages gem for Jekyll](https://github.com/github/pages-gem). It is licensed under The Unlicense, which allows everything and promises nothing.

Favicon is `Soft Ice Cream` from [Twemoji](https://twemoji.twitter.com/), licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Other parts of this project, including Primer CSS and Bootstrap, have their own licenses.
