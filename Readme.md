*This repository is a mirror of the [component](http://component.io) module [stagas/pager](http://github.com/stagas/pager). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/stagas-pager`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# pager

  Pager ui component.

  ![](http://f.cl.ly/items/023v0g1I2p2D4313033a/Screen%20Shot%202012-09-17%20at%202.40.06%20PM.png)

## Installation

    $ component install component/pager

## Events

  - `show` (n) emitted when a page is selected (0-based)

## API

### Pager#total(n)

  Set the total number of items to `n`.

### Pager#perpage(n)

  Set the number of items per page to `n`. [5]

### Pager#pages()

  Return the total number of pages.

### Pager#show(n)

  Select page `n`, `.render()`, and emit "show".

### Pager#select(n)

  Select page `n` and `.render()`.

### Pager#render()

  Re-render the pager.

# License

  MIT
