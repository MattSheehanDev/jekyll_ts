Jekyll plugin to compile Typescript
====

## Setup

1. Add *jekyll_ts.rb* to _plugins folder
2. Add plugin configs to your _config.yml file
    * tsc:     path of typescript compiler
    * js_dest: output of js files after compilation
3. Javascript files will write to js_dest location on build