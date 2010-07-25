PullToRefresh

A simple iPhone TableViewController for adding pull-to-refresh functionality.

Inspired by [Tweetie 2](http://www.atebits.com/tweetie-iphone/), [Oliver Drobnik's blog post](http://www.drobnik.com/touch/2009/12/how-to-make-a-pull-to-reload-tableview-just-like-tweetie-2/)
and [EGOTableViewPullRefresh](http://github.com/enormego/EGOTableViewPullRefresh).


How to intall

1. Copy the files, PullRefreshTableViewController.h and PullRefreshTableViewController.m into your project.

2. Copy the pull-arrow.png into your project.

3. Link against the QuartzCore framework (used for rotating the arrow image).

4. Create a TableViewController that is a subclass of PullRefreshTableViewController.

5. Customize by adding your own refresh() method.


Enjoy!