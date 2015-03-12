# &lt;skylink-call&gt;
===================

Web-Component to embed a button into your website to call another visitor via WebRTC powered by [SkylinkJS](http://skylink.io/web).


## Usage

```html
<skylink-call app-key="Your APP key" caller-id="Your ID" caller-name="Your Name" callee-id="Callee ID" callee-name="Callee Name"></skylink-call>
```

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

```sh
$ [sudo] npm install -g bower grunt-cli
```

* Install local dependencies:

```sh
$ bower install
```


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D