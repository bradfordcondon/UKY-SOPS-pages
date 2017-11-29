![SOPS logo](images/sops_logo.jpg)

This repo is for the static pages of the [UKY SOPS](http://sops.as.uky.edu/) website.



## Instructions

Below are some basic instructions about the SOPs site.  I'm writing this assuming you are the new web administrator and don't know a whole lot about computers, HTML, or Drupal.

I strongly encourage you to read some basic Drupal tutorials when starting out.  If you want to see what content type is available, visit [the admin content list](http://sops.as.uky.edu/?q=admin/content).

### Administering a Drupal site
The SOPs website is a Drupal website.  Log in at http://sops.as.uky.edu/user.  If you are an admin, once you've logged in, you will see the site dashboard along the top, and you'll see an edit cog in the upper right of Drupal content.

The site consists of a menu,some static pages (Drupal content type: basic page), and the front page which displays articles.

#### Menu

The [menu](http://sops.as.uky.edu/?q=admin/structure/menu/manage/main-menu/edit&destination=node) along the top with links that go to static pages.  This repos stores those pages under version control so if they are accidentally deleted, they can be restored.

Contact Us is an exception: it is a *Web form*.  If you want to edit whats displayed, you need to edit the *markup* element of the web form!

#### Front page
The front page is meant to display *Articles*.  Feel free to include these in the repo, but considering these are ephemeral events, I haven't included them.


