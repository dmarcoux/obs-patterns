---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# OBS Pattern Library
<p class="lead">
  This is a collection of design patterns we use on the Open Build Service.
</p>


## How to Contribute (Add/Edit Patterns)

1. Fork the project on [GitHub](https://github.com/openSUSE/obs-patterns)
2. Add/edit patterns under
  [_posts](https://github.com/openSUSE/obs-patterns/tree/master/_posts).
  Patterns are grouped by categories (a category being a directory under
  `_posts`). Each pattern is a file under `_posts/$some_category/` (with the
  filename being `$date-$pattern_name.html`)
3. Test your changes locally with Docker Compose by running `docker-compose up`
  and accessing <http://localhost:4000/>
4. Submit a pull request

## Deployments

Deployments are automated with a webhook, so whenever commits are pushed to
`master`, a new version will be published. The deployments are listed
[here](https://app.netlify.com/sites/obs-patterns/deploys).
