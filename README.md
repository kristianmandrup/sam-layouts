SMA Prototype layouts
---------------------

### Install

First install dependencies using npm:

-	jquery
-	jade
-	semantic-ui
-	sortablejs

```sh
npm install
```

For semantic-ui, please use default configuration when asked (ie. just press *ENTER* at each step). Then build semantic-ui distribution files in`/semantic/dist`

```sh
cd semantic
gulp build
cd ..
```

Now you should be ready to work on the page layouts. See the docs for guidance!

### Usage

```
gulp jade
gulp watch
open semantic/pages/home.html
```

### Pages

Demonstrate the UI concepts for eah page

See `/semantic/pages`

### Docs

Describe the basic design idea and requirements for each set of pages.

See `/semantic/pages/docs`
