# [💻 SG VERSE - A terminal like website!](www.yourbrandstories.co/)

Highly customizable, easy-to-use, and minimal terminal styled website template, powered by Next.js.

Building a simple website with LiveTerm only takes **minutes**, and you only need to work with **one** file: `config.json`. After you cloned this repository, simply run `yarn install && yarn dev` and start editing `config.json` to build your website!

Shoutout to [Liveterm](https://liveterm.vercel.app/) which made this possible!

## 🚀 Ship SG VERSE site in less than 5 minutes

SG VERSE requires the `yarn` package manager.

You can clone this repository to a location of your choosing

```bash
git clone https://github.com/ighoshsubho/TerminalPortfolio.git && cd TerminalPortfolio
```

Then install dependencies and start developing there:

```bash
yarn install && yarn dev
```

## 📄 Configuration

### Basic Configuration

90% of SG VERSE's configurations are done through the `config.json` file.

```javascript
{
  "readmeUrl": // create a Github README and link it here!
  "title": // title of the website
  "name": // your name, included in 'about' command
  "ascii": // ascii art to display
  "social": {
    "github": // your handle
    "linkedin": // your handle
  },
  "email": // your email
  "ps1_hostname": "liveterm" // hostname in prompt
  "ps1_username": "visitor", // username in prompt
  "resume_url": "../resume.pdf", // path to your resume
  "non_terminal_url": "W",
  "colors": {
    "light": {
      ...
    },
    "dark": {
      ... // you can use existing templates in themes.json or use your own!
    }
  }
}
```

Feel free to change it as you see fit!

### Advanced Configuration

If you want to further customize your page, feel free to change the source code to your liking!

## 🌐 Deploy on Vercel

The easiest way to deploy a Next.js app is to use the [Vercel Platform](https://vercel.com/) from the creators of Next.js.

## Credit

Again Shoutout to [Liveterm](https://liveterm.vercel.app/) for this amazing piece of work!

Based on M4TT72's awesome [Terminal](https://github.com/m4tt72/terminal).
