[![Status](https://img.shields.io/badge/status-active-success.svg?style=flat-square&logo=netlify)](https://dscrnsitblog.netlify.app)
[![GitHub issues](https://img.shields.io/github/issues/dscrnsit/Blog?style=flat-square)](https://github.com/dscrnsit/Blog/issues)
[![Contributors](https://img.shields.io/github/contributors/dscrnsit/Blog?style=flat-square)](https://github.com/dscrnsit/Blog/graphs/contributors)
[![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-black-magic.svg)](https://forthebadge.com)

# [DSC Blog](https://dscrnsitblog.netlify.app)

## Usage


- Fork repository and clone it locally
- Customize the content
- Raise Pull Request, which will be verified and merged (Please add a screenshot highlighting the changes you've made in blog, if possible)

## Updating

Here is a git workflow for updating your fork (or downloaded copy) to the latest version:

```git
git remote add upstream https://github.com/dscrnsit/Blog.git
git submodule update --init --recursive
hugo server
git fetch upstream
git merge upstream/Blog
# resolve the merge conflicts in your editor
git add . -u
git commit -m 'Updated to the latest version'
```

## Using GitHub Issues

- Feel free to use GitHub issues for questions, bug reports, and feature requests
- Use the search feature to check for an existing issue
- Include as much information as possible and provide any relevant resources (Eg. screenshots)
- For bug reports ensure you have a reproducible test case
  - A pull request with a breaking test would be super preferable here but isn't required

## Contributors

- Vijeth P H - [@vijethph](https://github.com/vijethph)

---

## Credits

This application uses Open Source components. You can find the source code of their open source projects along with license information below. We acknowledge and are grateful to these developers for their contributions to open source.

### Original Project

PaperMod

### Source

https://github.com/adityatelange/hugo-PaperMod

### License

Copyright (c) 2020 nanxiaobei and adityatelange
Copyright (c) 2021 adityatelange

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
