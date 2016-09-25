---
layout: post
title: How to create a blog post
subtitle: Using Github's desktop client and a text editor
author: Steffen
tags: GAME, blog, howto
---

Adding a post to our blog is simple and open to all registered members of GAME. The blog is hosted on [https://pages.github.com](Github pages) and anyone with a Github account can push new articles directly to our repo. 

To do so, [sign up on Github](https://github.com/join) and install their [desktop client](https://desktop.github.com). Next, open our [repository](https://github.com/game-unige-blog/game-unige-blog.github.io), where the website is stored, and click the button in the top-right corner that says **Fork**. This will create a copy of our website in your github repository. Using the desktop client, you can then download the copy to your computer and start editing. 

To create a blog entry, open the folder containing the website and navigate to the folder *_post*. To create a new post, simply make a copy of any of the files in the folder, then change the file name to match today's date and add your post title after it. Your file should look something like this:

    2016-10-26-The title of my blog entry.md

To edit your blog entry, either open the file in your favorite text editor (I use [textmate](https://macromates.com)) and edit the header (the stuff between the "---") to include your *title*, *author*, and *tags* information. Then remove the text below the header and start writing. The blog uses markdown for formatting. It's the same stuff that e.g. wikipedia or stackoverflow use for text formatting and it's pretty straight forward once your tried it once. There's a good tutorial with the basics on [Github itself](https://guides.github.com/features/mastering-markdown/). You can also use [this converter](http://markitdown.medusis.com) to convert your formatted text into markdown, in case you've already written something in MS Word or on your wordpress blog or so. 

Now you're almost done. The last thing to do is to send the changes you made on your computer to your Github account online (this is called a *commit*), and then to add the files to our website repo (this is called a *merge*). In the Github Desktop client, check the new file you created and add a bit of information in the two boxes below so we know what you're adding. Then hit *Commit to master* and then *Sync*, which will upload your changes to your copy (your "fork") of the website's repo. It should look something like this:

[Github commit example](img/blog/github_commit_example.png)

Now, click the merge icon on top of the window to send your changes to our repo. We'll get a notification and will then add your new post asap. 

If that's too complicated, you can also always send your blog posts to game@unige.ch.