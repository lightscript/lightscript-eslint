# lightscript-eslint 

`lightscript-eslint` is a fork of `babel-eslint` that parses code with
`babylon-lightscript` and `babel-plugin-lightscript`.

Any file that includes `.lsc` or `.lsx` in the filename (including, eg, `.lsc.js`)
will be processed with the LightScript compiler;
all others will be processed exactly as in `babel-eslint`.

To use, just `npm install --save-dev lightscript-eslint`
and add `parser: "lightscript-eslint"` to your `.eslintrc`.

Testing so far has been limited; this is very much alpha software and it may not work well. In particular, it is unlikely to work with many rules. 
