# config-start-jekyll
Gulp + Bower + Jekyll

## Compilation and Server
~/my-awesome-site > bundle exec jekyll serve
=> Now browse to http://localhost:4000

## Gulp
~/my-awesome-site > gulp => [default] 'minify-css' + 'minify-js'
~/my-awesome-site > minify-css => 'minify-css'
~/my-awesome-site > minify-js => 'minify-js'
~/my-awesome-site > watch => watch 'minify-css' + 'minify-js'