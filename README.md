# README

You've stumbled upon the source of my blog.

It's hosted on github pages,

It uses jekyll for it's static pages.

Upon running of the `rails s` dev server, it will build the jekyll html
in the `public` directory.

That public folder is its [OWN github repository](https://github.com/beaukinstler/beaukinstler), which when pushed up to GH, 
will be beaukinstler.com.

So, edit the post in _posts, according to jekyll naming convention,
save, run puma on the app, then commit the chages int he public folder, then push the 
public folder. 

if all is well, commit the root folder, and push up to GH for safe keeping.

