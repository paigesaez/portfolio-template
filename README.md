# lynnandtonic Portfolio Template

## Whut

This is the template for my current portfolio site, redesigned in April of 2013.

You can preview this template here: [http://lynnandtonic.github.io/portfolio-template/](http://lynnandtonic.github.io/portfolio-template/)

## Getting Started

1. [Install DocPad](https://github.com/bevry/docpad)

1. Clone the project and run the server

	``` bash
	git clone git@github.com:lynnandtonic/portfolio-template.git
	cd portfolio-template
	npm install
	docpad run
	```

1. [Open http://localhost:9778/](http://localhost:9778/)

1. Start hacking away by modifying the `src` directory


## Domain set up

Before you deploy, you will want to update your production URL in the `docpad.coffee` file. In most cases, you will not need a contextPath. It is set up this way to accomodate subfolder paths when deployed to GitHub pages.

	site:
			# Site Production URL
			contextPath: '/portfolio-template'

## Production Build

    docpad run --env=production

## License

Characters and illustrations are from The Wizard of Oz by L. Frank Baum, in the public domain in the US since 1956.

Unless stated otherwise, all content is licensed under the [Creative Commons Attribution, Non-Commercial License](http://creativecommons.org/licenses/by/3.0/), © [Lynn Fisher](http://lynnandtonic.com)

See License.MD

### Summary:

You are free:
* to Share — to copy, distribute and transmit the work
* to Remix — to adapt the work

Under the following conditions:
* Attribution — You must attribute the work (but not in any way that suggests that I endorse you or your use of the work).
* Noncommercial — You may not use this work for commercial purposes.