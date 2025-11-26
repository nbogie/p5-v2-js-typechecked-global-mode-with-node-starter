javascript global-mode p5 v2 sketch with type-checking using jsconfig and node-installed p5 types

This version requires _node.js_ installed, only in order to download the p5 types conveniently. If you do not have node.js, there is [another version of this starter available](https://github.com/nbogie/p5-v2-js-typechecked-global-mode-starter) which comes with the type files saved in the projec and doesn't require node.js.

# install

`npm i`

This will download the most recent version of p5.js (into node_modules/). If you need a specific version you can edit package.json.

## template issues:

It's not a big deal but I think the location of the types should auto-resolve from the p5 package.json's `types` property. For now I've explicitly linked to them in `jsconfig.json` and that's version independent (for any p5 starting w v2).
