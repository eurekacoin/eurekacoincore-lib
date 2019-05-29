EurekaCoincore Library
=======

A pure and powerful JavaScript EUREKACOIN library.


## Get Started

```
npm install eurekacoincore-lib
```

```
bower install eurekacoincore-lib
```

## Security

We're using eurekacoincore-lib in production, but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.



## Contributing

Please send pull requests for bug fixes, code optimization, and ideas for improvement. 

## Building the Browser Bundle

To build a eurekacoincore-lib full bundle for the browser:

```sh
gulp browser
```

This will generate files named `eurekacoincore-lib.js` and `eurekacoincore-lib.min.js`.

## Development & Tests

```sh
git clone https://github.com/eurekacoin/eurekacoincore-lib
cd eurekacoincore-lib
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

