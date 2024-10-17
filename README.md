# Website prototype for the Center for Transformational Play

Deployed at [https://cmu-ctp.github.io/](https://cmu-ctp.github.io/)

This is a fork of: https://github.com/cmudig/cmudig.github.io <br>
which was inspired by: https://github.com/visdesignlab/visdesignlab.github.io and https://github.com/domoritz/domoritz.github.io. 

## Run

Install Jekyll dependencies with `bundle`. To start this page, run `bundle exec jekyll serve --livereload`.

## Run with Docker

```
docker run \
  --volume="$PWD:/srv/jekyll" \
  -p 4000:4000 -p 35729:35729 \
  -it jekyll/jekyll \
  jekyll serve --livereload
```

## Add Content

To add specific content, follow the README guides in the corresponding directories:

* [Add a person](_people)
* [Add a publication](_publications)
* [Add a post](_posts)
