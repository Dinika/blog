<p align="center">
  <a href="https://minimal-blog.lekoarts.de">
    <img alt="LekoArts" src="https://img.lekoarts.de/gatsby/gatsby-site-illustration.png" />
  </a>
</p>
<h1 align="center">
  Blog
</h1>

The source code for the blog is built using Gatsby and is based on [the excellent template](https://github.com/LekoArts/gatsby-starter-minimal-blog) created by [@lekoarts](https://github.com/LekoArts).

## Deployment

1. Merge the commits/PR to `main` branch.
2. From the `main` run `npm run deploy`. This will start a github action.
3. The site should automatically be published in a few minutes. 

I've noticed that after running `npm run deploy` the "pages" settings in github somehow changes the domain a dinika.github.io one.
In this case I need to add `blog.dinika.greyllama.cc` under the "Custom domain" section of settings and wait for a minute for the changes to take place.
I don't need to re-run `npm run deploy`.

## Debugging
Make sure that `gh-pages` is chosen as the deployment branch in github settings and the right custom domain is added.