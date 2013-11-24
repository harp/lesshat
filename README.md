# harp-lesshat

> Smart LESS CSS mixins library.

## Dependencies

* [NodeJS](http://nodejs.org/) – _Server-side JavaScript runtime_
* [Harp](http://harpjs.com/) – _The static web server with built-in preprocessing_

## Install

To install LESS Hat, run the following command from the root of your harp project:

```bash
harp install lesshat
```

Your Project will look something like this…

```
myproject/                  <-- your project root (or public dir if in framework-mode)
  |- components/            <-- harp puts components here
  |   +- harp-lesshat/      <-- where this lib gets installed
  |       …
  |- main.styl              <-- where you reference LESS Hat 
  +- index.jade             <-- where you reference main.css
```

## Link

Now, from within a `.less` file in your project, you can `@import` LESS Hat:

```less
@import "components/harp-lesshat/less/lesshat.less";
```

Or, after running `harp install bootstrap`, use the prefixed version with Bootstrap:

```less
@import "components/harp-bootstrap/less/_bootstrap.less";
@import "components/harp-lesshat/less/_lesshat-prefixed.less"
```

## Resources

* [Harp documentation](http://harpjs.com/docs)
* [LESS documentation](http://lesscss.org)
* [LESS Hat documentation](https://github.com/csshat/lesshat/blob/master/README.md)

## License

This component is [LESS Hat](https://github.com/csshat/lesshat), which is MIT Licensed.