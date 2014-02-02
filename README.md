# &lt;imgur-gallery&gt;

A gallery for your [IMGUR Album](http://api.imgur.com/models/album)
> Maintained by [Brad Oyler](https://github.com/bradoyler).

## Demo

> [Check it live](http://bradoyler.github.io/imgur-gallery).

## Run locally (Mac)

```console
		$ git clone https://github.com/bradoyler/imgur-gallery.git
		$ cd imgur-gallery
		$ bower install
		$ python -m SimpleHTTPServer
```

## Usage

1. Import Web Components' polyfill:

	```html
	 <script src="bower_components/platform/platform.js"></script>
     <link rel="import" href="bower_components/polymer-ajax/polymer-ajax.html"/>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/imgur-gallery.html">
	```

3. Start using it!

	```html
	<imgur-gallery></imgur-gallery>
	```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 Feb 1, 2014
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License
[MIT License](http://opensource.org/licenses/MIT)

