# [normanderwan.fr](https://normanderwan.fr)

> Sources of my personal website.

## Install

- Install [Git](https://git-scm.com/).
- Install [Hugo extended](https://gohugo.io/getting-started/installing/).
- Clone the repository: `git clone --recurse-submodules -j8 git@github.com:NormandErwan/normanderwan.fr.git`
- Add content:
    - Add blog post to `content/posts/YYYY/MM/post-title.md`, replacing YYYY and MM with current year and month.
    - Add images to `static/img/YYYY/MM/post-title-imageX.jpg`, replacing YYYY and MM with current year and month.
    - Reference images with `{{< figure src="/img/YYYY/MM/post-title-imageX.jpg" title="Image title" >}}`
- Watch for changes: `hugo server`.
- Compile the website: `hugo`.

## License

Non-code content is licensed under CC-BY, code content is licensed under the MIT license.