# README

You've stumbled upon the source of my blog.

It's hosted on GitHub pages,

It uses jekyll for its static pages.

Upon running of the `rails s` dev server, it will build the jekyll html
in the `public` directory.

That public folder is its [OWN GitHub repository](https://github.com/beaukinstler/beaukinstler), which when pushed up to GH, 
will be beaukinstler.com.

So, edit the post in _posts, according to jekyll naming convention,
save, run puma on the app, then commit the changes in the public folder, then push the public folder. 

if all is well, commit the root folder, and push up to GH for safe keeping.

You may notice that this might be overkill.  I agree. However, it's not that bad,
and I'm set up to make this data-driven using ActiveRecord in the future, so I'm okay with it if you are.