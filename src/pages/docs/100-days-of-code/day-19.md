---
title: Day 19
weight: 12
template: docs
---

Continuing with the WordPress development course...

![Blog feed page](/images/blog-feed-day19.png)

![Single post blog page](/images/blog-single-day19.png)

Today I worked on setting up the blog feed page and single blog page. We created a `Home` and `Blog` page in the WordPress dashboard and changed the settings so that the Home page we have been looking at is the home page according to WordPress. By default, WP shows the latest blog posts in a feed.

A new file had to be created so that we have a home and a blog home. The code on index.php moved to front-page.php and the blog home page code replaced it.

Some of the work that went into setting up the blog feed was:
- Dynamically displaying author, date, and category for a post
- Reusing the header banner for `index.php` and `single.php`
- adding pagination and testing it by changing the number of posts to display per page

Links to work:

* <https://github.com/prophen/100-days-of-code-blog>

Resources I used today:
- https://wordpress.org/support/article/formatting-date-and-time/
- https://www.udemy.com/course/become-a-wordpress-developer-php-javascript/
