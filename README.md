[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/nginx/community-blog/badge)](https://securityscorecards.dev/viewer/?uri=github.com/nginx/community-blog)
[![Community Support](https://badgen.net/badge/support/community/cyan?icon=awesome)](/SUPPORT.md)
[![Community Forum](https://img.shields.io/badge/community-forum-009639?logo=discourse&link=https%3A%2F%2Fcommunity.nginx.org)](https://community.nginx.org)
[![License](https://img.shields.io/badge/License-BSD_2--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](/CODE_OF_CONDUCT.md)

# NGINX Community Blog

## Overview

This repository is used to store external blog contributions to the [NGINX Community blog](https://blog.nginx.org/). Contributions are more than welcome! Do keep in mind that the NGINX Community blog is primarily meant as a blog for our OSS projects.

## Blog Submission Process

To start the blog submission process, open an issue with your blog idea. Once the idea is approved, open a PR with your draft. We will review your draft, ask for changes where required, and once there is a final draft that both parties are happy with, we will merge the PR. Once the PR is merged, it will get staged and published at the earliest slot in our publishing calendar.

### On Opening Issues with Blog Ideas

Issues opened should follow one of two patterns:

1. If this is your first interaction with us, describe your blog idea. We will get back to you as soon as possible and let you know what we think of it! Depending on the context, we might ask you refine your blog idea. Do not open a PR until we approve your issue!
2. If you have already engaged with us through a different communication channel, share and we have given you the go ahead to publish a blog, open an issue with a brief description of the blog idea linking back to the original communication channel (if possible). Once you open the issue, feel free to open a PR whenever you have a draft ready! Your blog idea has already been approved.

### Blog Review Process

Once you open a PR with your blog draft, we will try to get it reviewed as soon as possible. We will review technical content for accuracy, and copy edit your text. We will not make any changes without your consent and will not suggest changes to tone and sentiment unless your draft is very dissonant to the overall tone of the community blog. Once both you and us are happy with the draft, we will merged it into the `main` branch and stage it and publish it as soon as possible. If your blog release is time sensitive (e.g. you want to write something about an upcoming NGINX OSS feature) let us know in the original issue and we will do all we can to get it up in due time!

## Blog Guidelines

Please follow the following guidelines when submitting blogs:

- Please write your blog in Markdown. This makes it easier for us to review and stage your blog!
- For each new blog, create a folder in the [/blogs](/blogs/) directory and place your Markdown file inside. If you are including any images in the blog, include them inside this folder too.
- Start each blog with both the Title and Author metadata. Ideally, also include a Featured Image. Featured Images are used as your blog thumbnail picture and are placed immediately below your title. Featured Images should have a 16:9 ratio. Other ratios will work, but will be cropped.
- If you include any technical details and/or benchmarks in your blog, make sure the details are entirely reproducible! We strive to provide actionable information to our users, and reproducible tech content is a must.
- You will be able to include a Call to Action, but remember this is an OSS focused non-commercial blog, so any CTAs have to be community focused.
- See an example blog at [/blogs/example-blog/example.md](/blogs/example-blog/example.md)) for more info.

## Contributing

Please see the [contributing guide](/CONTRIBUTING.md) for guidelines on how to best contribute to this project.

## License

[BSD 2-Clause](/LICENSE)

&copy; [F5, Inc.](https://www.f5.com/) 2025
