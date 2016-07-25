Social Buttons for Bootstrap
============================

Social Buttons made in pure CSS based on
[Bootstrap](http://twbs.github.io/bootstrap/) and
[Font Awesome](http://fortawesome.github.io/Font-Awesome/)!

[Check the live demo!](github.ibm.com/pages/dswb/bootstrap-social)

Extended from [lipis/bootstrap-social](https://github.com/lipis/bootstrap-social)

Installation
------------

Include the `bootstrap-social.css` or `bootstrap-social.less` in your project.

Available classes
-----------------
 - `btn-adn`
 - `btn-bitbucket`
 - `btn-bdu`
 - `btn-dropbox`
 - `btn-facebook`
 - `btn-flickr`
 - `btn-foursquare`
 - `btn-github`
 - `btn-google`
 - `btn-instagram`
 - `btn-linkedin`
 - `btn-microsoft`
 - `btn-odnoklassniki`
 - `btn-openid`
 - `btn-pinterest`
 - `btn-reddit`
 - `btn-soundcloud`
 - `btn-tumblr`
 - `btn-twitter`
 - `btn-vimeo`
 - `btn-vk`
 - `btn-yahoo`
 - `btn-weibo`

Examples
--------

```html
<a class="btn btn-block btn-social btn-twitter">
  <span class="fa fa-twitter"></span>
  Sign in with Twitter
</a>

<a class="btn btn-social-icon btn-twitter">
  <span class="fa fa-twitter"></span>
</a>
```

Compiling LESS
--------------

In order to generate `bootstrap-social.css`, you will need to compile
`bootstrap-social.less`.

```sh
$ npm install -g less clean-css less-plugin-clean-css
$ npm install
$ lessc bootstrap-social.less --clean-css="--s0 -b --advanced" > bootstrap-social.css
```
