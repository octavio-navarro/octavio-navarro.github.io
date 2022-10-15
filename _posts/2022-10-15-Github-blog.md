---
layout: post
title: "Starting a blog with Github pages"
date: 2022-10-15
tags: Learning GitHub
---

# Starting a blog with Github pages

In an attempt to get myself to learn things outside of my current course materials, I though it would be a good idea to start a blog to record the process. The first of, hopefully, several posts, is actually setting the blog up.

## Following a tutorial

After a quick google search, I decided to use GitHub pages. I found several tutorials, but found [Chad Baldwin's Tutorial][1] particularly simple. You can also find all the base code at [his github page][git]. All the steps are quite straightforward. I also looked a lot through Chad's repo to see how the layouts worked.

In general, the steps I took were the following:

1. Cloned the github pages repo I made a while back.
2. Downloaded the base code as a zip from Chad's github.
3. Extracted the code to my repo folder.
4. Updated the `_config.yaml` with the correct blog name, author, description, and links. Also removed the `rss` feed link, and added the `Blog Archive` and `Resume` pages reference. I got these from Chad's repo.
5. I structured the files in the repo, mainly adding the assets folder to have images and other things at hand.
6. Wrote this blog post, and, after several commits, got all running.

My main takeaways from this process are:

- The _config.yaml file is where you can customize everything. 
- You can add basic `html` files in addition to `md` files for the web pages.
- I will have the [Basic markdown guide][markdown_basics] always at hand.
- Adding images was rather straightforward once you arranged the files and set the file routes appropriately.
- I need to learn `Jekyll`, or how the layouts and templates work. It seems simple enough. May be another [learning opportunity][jekyll_docs].
- A local server to test the site before committing to github pages is needed.

That last point was really bothering me. I had to make a commit before I could see changed I had made to the website. The next step in my journey is setting up a local server.

## Setting up a local server

So, the next step was to set up a development platform. I could use WSL and install everything there, or use this as another learning opportunity: learning Docker.

That could very well be another post, so I'll start that, and update this post with the link once that is done.

## Next steps

Using the template was simple enough for me to start. I have some ideas to improve the blog/website:

- Figuring out how to make or modify my own templates.
- Making a more interesting landing page.
- Showing only the latest posts in the landing page.
- Adding a dark theme option.
- Adding content to the resume page.
- Adding more sections, such as `projects`.
- Adding `threejs` content.
- Adding [PyScript][pyscript] content.

But, for now, Docker.

### Additional Jekyll templates

I found additional templates that could be useful eventually:

- https://github.com/alshedivat/al-folio#installation
- https://github.com/cotes2020/jekyll-theme-chirpy

### Additional Resources

- [Jekyll's resources site](https://jekyllrb.com/resources/)

[1]: <https://chadbaldwin.net/2021/03/14/how-to-build-a-sql-blog.html> "Building a Free Blog with GitHub Pages in Minutes"
[git]: <https://github.com/chadbaldwin/simple-blog-bootstrap/>
[markdown_basics]: https://www.markdownguide.org/basic-syntax/
[jekyll_docs]: https://jekyllrb.com/docs/
[pyscript]: https://pyscript.net/