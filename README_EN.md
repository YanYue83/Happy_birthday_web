# Happy Birthday

<p>
<img src="https://img.shields.io/github/stars/abandon888/HappyBirthday" alt="stars" />
<img src="https://img.shields.io/github/issues/abandon888/HappyBirthday" alt="issues" />
<img src="https://img.shields.io/github/forks/abandon888/HappyBirthday" alt="forks" />
<img src="https://img.shields.io/github/license/abandon888/HappyBirthday" alt="license" />
<a href="https://app.netlify.com/sites/friendly-paprenjak-ad64b7/deploys"><img src="https://api.netlify.com/api/v1/badges/39d29171-f3b1-4172-932e-1f657058303a/deploy-status" alt="Netlify Status" /></a>
</p>


A special way to wish someone happy birthday.

Preview: (https://yanyue83.github.io/Happy_birthday_web/)

## Project Highlights

1. Carefully designed text animations and romantic floating balloon animations
2. Customize all text content, images, background music and font styles by simply modifying the `customize.json` file
3. Click anywhere on the page to display gorgeous firework effects
4. Auto-play beautiful background music to create a warm and romantic atmosphere
5. Built with modern rspack for better performance

## Usage

Fork this project, modify the customize.json file by replacing its contents with your own, then deploy it on github pages or other hosting sites (like netlify).

## Local Development/Preview

The project uses npm as package manager. Make sure you have node environment configured locally, otherwise please install it yourself. Verify node environment as follows:

```
$ node -v
v22.2.1
```

Then install dependencies:

```
npm install
```

Run:

```
npm run start
```

## Others

The overall implementation uses pure HTML, CSS and JavaScript, along with GSAP for animations.

Thanks to the original project author for open sourcing. This project is modified based on [happy-birthday](https://github.com/faahim/happy-birthday).

If you like this project, you can give it a star ⭐ to encourage me, thank you!

## Changelog

### v2.0 (2025-02-03)

1. Use rspack to build project
2. Add font configuration support
3. Add firework effects
4. Optimize music playback interaction
5. More configurable options

### v1.0

1. Added music playback effect
2. Added guide page
3. Chinese localization
4. Optimized some details
