# seed-element-v1

An element that implements the Polymer Seed Element in raw web components


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install



## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
serve to keep your element's
bower dependencies in line. You can install it via:

    npm install -g serve

And you can run it via:

    serve

Once running, you can preview your element at
`http://localhost:3000`


## Testing Your Element

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/seed-element/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.

# seed-element-v1
