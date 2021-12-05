## References from Fireship (Module Bundlers Explained)

#### Without webpack-cli

We will get an error


```
Cannot use import statement outside a module
```
 because the browser doesn't know how to resolve lodash code. So, we need to install webpack cli.

#### Export multiple entry points

```
module.exports = {
entry: {
       foo: 'foo.js',
       bar: 'bar.js'
   }
}
```

#### Scss compilation failure

We will get this error
```
Module parse failed: Unexpected token
You may need an appropriate loader to handle this file type, currently no loaders are configured to process this file.
```
because we don't have loader yet.

#### What is a loader?  

```
Loaders process files that aren't Javascript. We will use style-loader, css-loader and sass-loader here.
```

#### Rules?

``` 
Rules match files to loaders.
```

#### Plugins?

```
Plugins tap into the bundler lifecycle. We will use webpack bundle analyzer plugin here.
```

#### Dev server

```
Set up a local dev server to watch changes to the project and recompile them.
```

#### Exercise

```
Try to use Snowpack by yourself
```


