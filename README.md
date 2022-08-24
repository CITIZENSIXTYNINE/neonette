<h1 align="center">Neonette</h1>

### about

This is Neonette, an incredibly purple, but lightweight-ish stylesheet based on [Nanom's style.css](https://nanom.neocities.org) (from mid-2021). Made to be easy to use, modern and nice to look at, Neonette is perfect for making heavy text-based sites or just simple "homepage" sites like [mine](https://obama.solutions/~nicoleaoki)!

As mentioned before, Neonette is a fork of sorts of Nanom's style.css (well, index.css), with some addons sprinked in, for example, Neonette includes part of [SPCSS](https://github.com/susam/spcss) for images (w/ captions), codeblocks, quotes and tables. With this, Neonette is able to function as a complete "lightweight" stylesheet for all purposes, from making a template for your SSG, to making a full fledged website. Neonette has you covered for all of that stuff, and even if it doesn't feel free to [file an issue](https://github.com/nicoleaoki/neonette) and suggest features!

### usage

To start using Neonette on your project, it's as easy as copy and pasting one of the following snippets (can you even call them that?) into your site's code:

- for HTML, use `<link rel="stylesheet" type="text/css" href="https://neonette.netlify.app/neon.css">`

- for CSS, use `@import url(https://neonette.netlify.app/neon.css);`
- for JSX, I honestly have no fucking idea, please [submit a PR](https://github.com/nicoleaoki/neonette/pulls) and tell me how to.

Note that you do not need to import any "default" fonts or anything, Neonette includes Terminus (TTF, sad I know) as its default font.

After you're done with that, add `<main>` into your HTML and you should be good to go, here's an example of how your HTML should look like this:

```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="https://neonette.netlify.app/neon.css">
	<title>example site</title>
</head>
<body>
	<main>
		<p>Lorem Ipsum, I do not know what follows after that. I like potato chips.</p>
	</main>
</body>
</html>
```

With that out of the way, you're all set to develop using Neonette. Have fun!

### interested in using v1?

The current version of Neonette is v2, however, you can still load v1 by adding `v1/` to the link like this:

- `https://neonette.netlify.app/v1/neon.css`

Please note that v1 is just rebranded VanillaCSS with its colours shifted and a funny little border (although I think that's krisp.sdf.org exclusive? I don't remember), If you like how that looks, please check out [VanillaCSS](https://github.com/bradleytaunt/vanillacss).

### license

Due to how we're taking code from SPCSS, we have to license our code under MIT, this is both to ensure compatibility and because Nv1 was licensed under MIT and I don't want through the entire process of relicensing this to something else.

Originally, I planned to licence this under CC-0, to follow Nanom's footsteps on the entire "Take everything here, no need to credit me" thing.

### credits

- [@nanavortex](https://github.com/nanavortex) - for making their index.css to begin with, without it Neonette wouldn't even exist (neither as v1 or v2), thank you for making such an amazing site and allowing others to copy snippets from it.
- [@susam](https://github.com/susam) - for making SPCSS, the framework/library/stylesheet that handles all our image, codeblocks, quotes and tables. Without SPCSS this would literally just be Nanom's index.css without anything extra added to the table.
- [@bradleytaunt](https://github.com/bradleytaunt) - for making VanillaCSS, the framework/library/stylesheet that Neonette v1 was based on, I never properly credited Bradley's work aside a line in the CSS file, but knowing how Nv1 was just color-shifted VanillaCSS, I guess that it's only fair to credit his work.