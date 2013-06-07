SVG font creator
================

This tool creates SVG font from separate images. Due simplified process,
images must be preliminary optimized with [SVGO](https://github.com/svg/svgo):

- scaled to required height
- all paths joined to single one
- no `fill` commands colors transforms and others
- `fill` defined by polyline direction (`cw` - black, `ccw` - white)

Installation:

```
npm install svg-font-create
```

Usage example:

See Makefile in embedded fonts repos https://github.com/fontello/awesome-uni.font/blob/master/Makefile

License
-------
View the [LICENSE](https://github.com/fontello/svg-font-create/blob/master/LICENSE) file
(MIT).
