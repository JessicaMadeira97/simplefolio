## How To Use 🔧

From your command line, first clone Simplefolio:

```bash
# Clone this repository
$ git clone https://github.com/cobidev/simplefolio

# Go into the repository
$ cd simplefolio

# Remove current origin repository
$ git remote remove origin
```

Then you can install the dependencies either using NPM or Yarn:

Using NPM:

```bash
# Install dependencies
$ npm install

# Start development server
$ npm start
```

**NOTE**:
If your run into issues installing the dependencies with NPM, use this command:

```bash
# Install dependencies with all permissions
$ sudo npm install --unsafe-perm=true --allow-root
```

Once your server has started, go to this url `http://localhost:8080/` and you will see the website running on a Development Server:

<h2 align="center">
  <img src="https://github.com/cobidev/gatsby-simplefolio/blob/master/examples/example.png" alt="Simplefolio" width="100%">
</h2>

---

## Template Instructions:

### Step 1 - STRUCTURE

Go to `/src/template.html` and fill your information, they are 5 sections:

### Hero Section

- On `.hero-title`, put your custom title.
- On `.hero-cta`, put your custom button cta.

### Contact Section

- On `<p>` tag with class-name `.contact-wrapper__text`, include some custom call-to-action message.

### Footer Section
[Font Awesome Icons](https://fontawesome.com/v4.7.0/icons/) 

---

## Deployment 📦

Once you have done with your setup. You need to put your website online!

I highly recommend to use [Netlify](https://netlify.com) to achieve this on the EASIEST WAY

Because this template use Webpack maybe you can get errors during deployment, Please watch my step-by-step video tutorial to successfully upload your Simplefolio Website on Netlify!

**[WATCH NOW MY STEP-BY-STEP TUTORIAL FOR DEPLOYMENT](https://www.youtube.com/watch?v=soaG3GNSxJY)**

## Technologies used 🛠️

- [Webpack](https://webpack.js.org/concepts/) - Static module bundler
- [Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/introduction/) - Front-end component library
- [Sass](https://sass-lang.com/documentation) - CSS extension language
- [ScrollReveal.js](https://scrollrevealjs.org/) - JavaScript library
- [Tilt.js](https://gijsroge.github.io/tilt.js/) - JavaScript tiny parallax library
- [Popper.js](https://popper.js.org/) - JavaScript popover library

## Authors

- **Jacobo Martinez** - [https://github.com/cobidev](https://github.com/cobidev)