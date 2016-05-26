# Heroku buildpack: #webscale

This is a [Heroku buildpack][buildpack] for making any app web-scale.

The buildpack takes the source tree, discards it and defines a process type
optimized for web-scale. The result is a very performant app capable of
handling a gazillion requests almost instantly. Because the response has been
crafted carefully, even clients on slow connections will load it immediately.

[buildpack]: https://devcenter.heroku.com/articles/buildpacks
    "Heroku Dev Center article on buildpacks"
