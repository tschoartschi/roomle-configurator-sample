# Roomle Configurator Sample

This is a sample repo to describe how to implement the Roomle Configurator with npm.

Please note that this repo uses modern JavaScript features like `async/await`, `addEventListener` etc.

If you don't want to use `async/await` you can use the calls as Promise. If you have struggles to rewrite the
`async/await` code, you can read the following [blog post](https://medium.com/@bluepnume/learn-about-promises-before-you-start-using-async-await-eb148164a9c8).

## Get me started

To start code locally you just have to do the following steps:

```bash
 git clone git@github.com:tschoartschi/roomle-configurator-sample.git roomle-configurator-sample
 cd roomle-configurator-sample
 npm install
 npm run serve
 ```

After that just open your favourite web browser on http://localhost:8080/

The blue background should indicate the space of your website. You could put important stuff there. Like a parlist
or different items which should be loaded in the configurator. Feel free to be creative how to embed the configurator.
But it's recommended to embed the configurator as big as possible because otherwise the UX will suffer. Have fun and
let me now if you have any troubles.
