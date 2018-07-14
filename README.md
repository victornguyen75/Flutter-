# Flutter, the Dumb Twitter
## A Ruby on Rails Twitter Clone
## Here is the Flutter Mascot!
![feature-image](https://cdn.discordapp.com/attachments/338530149593251850/467520539209105408/unknown.png)

#### Original creator: Justalevel
#### This is a fork of justalever's master branch. 
[Download the source code](https://github.com/justalever/twittter)
Continue reading on [web-crunch.com](https://web-crunch.com/lets-build-with-ruby-on-rails-a-twitter-clone/)

### Features being used

The app itself will feature
- Basic CRUD principles (create, read, update, and destroy) *Tweeets*
- Implement a gem called [Devise](https://github.com/plataformatec/devise) to verify and authenticate users
- Different users can author different *Tweeets*

### Features not being used

Twitter is pretty elaborate application. As a result, it will not cover:
- Replies
- Retweets
- Likes
- Trends
- Who to Follow

There are also a few gems in the wild for "liking" posts. [A pretty good idea](https://github.com/schneems/Likeable)

**Note:** One big error I noticed after calling it quits on this build was that any logged in user could edit **any** other user's tweeets. This is a big security flaw as a user's abilities should only lie within their own account. See if you can find a way to only allow the current logged in user to edit their own tweets and not other users. I may revisit this series to extend and address these issues. 

### What I am doing differently from justalever's master branch

I am forking from his repository to make my own edits to this web application. I modified the profile images and included a variety of people to follow for my own amusement. This was a fun project that I got to apply my knowledge of Ruby and Rails into a web application as well as learn HTML, CSS, etc.

### Ruby gems used in this build

- [Better Errors](https://rubygems.org/gems/better_errors) - For better errors

- [Bulma](https://github.com/joshuajansen/bulma-rails) - for easy CSS. Feel free to roll your own styles and/or use a different framework.

- [Guard](https://github.com/guard/guard) - Useful for live reloading our `scss`, `js`, `css`, and `erb` files, although it's capable of much more!

  *Guard is required for the Guard LiveReload gem to work*

- [Guard LiveReload](https://github.com/guard/guard-livereload)

- [Simple Form](https://github.com/plataformatec/simple_form) - For simple forms!

- [Devise](https://github.com/plataformatec/devise) - Effortless user roles and authentication

- [Gravatar_image_tag](https://github.com/mdeering/gravatar_image_tag) - Integrated image tag which spits out gravatars.
