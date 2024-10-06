---
title: How to create your own blog using Github Pages and Markdown
layout: default
stylesheet: ../article.css
---

# How to Create Your Own Blog for Free with GitHub Pages
As a programmer, I often have to write documentation using markdown markup. 
And I like to write down somewhere what I've learned. I was curious - is it possible to just use markdown to run your blog. 
It turns out that it is possible with github pages

## Steps to Create a Blog with GitHub Pages
1. Create a GitHub Account
2. Create a New Repository
   * Name your repository in this format: yourusername.github.io.
   * Make sure to set the repository to Public, and then click Create repository.
3. Set Up Your Blog
   * Create a new file in your repository called index.md or index.html.
   * If you’re using Markdown (index.md), you can write your first post like this:

```
---
title: Welcome to My Blog
---
# Hello, World!

This is my first blog post on GitHub Pages. Stay tuned for more updates!
```
4. Customize Your Blog
   * Add a theme: GitHub Pages supports several pre-built themes. To add one, create a _config.yml file in your repository and add this line:
```js
theme: minima
```
   * You can also edit the CSS or HTML files if you want more control over the design.
5. Publish Your Blog
6. Once you commit your changes and push them to the repository, GitHub Pages will automatically publish your blog at https://yourusername.github.io. You can start sharing your blog link with the world!

## Conclusion
Creating a blog on GitHub Pages is a fantastic way to establish an online presence without paying for hosting. For example, this article was created here using github pages. Isn't this a miracle?