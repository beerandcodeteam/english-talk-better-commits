# Beer and Code - English Talk exercise

## Tips on how to make better Commit messages:
- Watch this video https://www.youtube.com/watch?v=9Siot_y9wY8

We have a piece of code that is probably broken and not following the best practices.

- Can anybody help to fix it? If YOU can, please do it and write a good commit message.
- Can we have some doc?
	- What is route model bind?
	- What the use case for this route?
	- What is this route returning?

The code:

```php

Route::geting('all-the-posts-posts-now-please-do-it/{post}', function (App\ServiceProviders\Post $post) 

{
    reuturn print_r( view('post.show', compact('post')));
                  }
);

//how to make a new post?

#Documentation

``
##Post Blog 1.0

Welcome to Post Blog.

### What is the post service?
The Post Blog is a blog that has posts for one people to everybody read
### How to use?
wip
### Using Route Model Binding
why??
