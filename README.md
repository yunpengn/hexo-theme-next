# <div align="center"><a title="NexT website repository" href="https://github.com/yunpengn/hexo-theme-next"><img align="center" width="56" height="56" src="https://raw.githubusercontent.com/yunpengn/hexo-theme-next/master/source/images/logo.svg?sanitize=true"></a> e x T</div>

<p align="center">«NexT» is a high quality elegant <a href="http://hexo.io">Hexo</a> theme. It is crafted from scratch with love.</p>

<p align="center">
  <a href="https://github.com/yunpengn/hexo-theme-next/releases"><img src="https://img.shields.io/github/package-json/v/yunpengn/hexo-theme-next?style=flat-square"></a>
  <a href="https://nodejs.org"><img src="https://img.shields.io/badge/node-%3E=10.9.0-green?style=flat-square"></a>
  <a href="https://hexo.io"><img src="https://img.shields.io/badge/hexo-%3E=4.0.0-blue?style=flat-square&logo=hexo"></a>
  <a href="https://github.com/yunpengn/hexo-theme-next/blob/master/LICENSE.md"><img src="https://img.shields.io/badge/license-%20AGPL-orange?style=flat-square&logo=gnu"></a>
  <a href="https://bestpractices.coreinfrastructure.org/projects/2625"><img src="https://img.shields.io/cii/level/2625?style=flat-square" title="Core Infrastructure Initiative Best Practices"></a>
  <a href="https://travis-ci.com/yunpengn/hexo-theme-next?branch=master"><img src="https://img.shields.io/travis/com/yunpengn/hexo-theme-next/master?style=flat-square&logo=travis%20ci" title="Travis CI [Linux]"></a>
  <a href="https://app.codacy.com/manual/yunpengn/hexo-theme-next/dashboard"><img src="https://img.shields.io/codacy/grade/72f7fe7609c2438a92069f448e5a341a/master?style=flat-square&logo=codacy" title="Project Grade"></a>
  <img src="https://img.shields.io/snyk/vulnerabilities/github/yunpengn/hexo-theme-next?style=flat-square" title="Vulnerabilities">
</p>

## About This Repository

[This repository](https://github.com/yunpengn/hexo-theme-next) is [Yunpeng](https://github.com/yunpengn/)'s forked version of the awesome [Hexo.js](https://hexo.io/) theme, [Next](https://github.com/theme-next/hexo-theme-next).

For more information and detailed documentation, please refer to the [official documentation](https://theme-next.org/).

## Upgrade to a Newer Version

The [Next](https://github.com/theme-next/hexo-theme-next) theme may include new changes frequently on their master branch. To keep this forked version up-to-date as well, we sometimes have to upgrade this repository to a newer version. To do so, follow the instructions below:

- Clone this repository by `git clone git@github.com:yunpengn/hexo-theme-next.git`;
- Navigate to this directory by `cd hexo-theme-next`;
- Add the upstream [repository](https://github.com/theme-next/hexo-theme-next) as a new remote by `git remote add upstream git@github.com:theme-next/hexo-theme-next.git`;
- Fetch the latest changes from the upstream by `git fetch --all`;
- Merge changes from upstream into origin by `git rebase upstream/master`;
  - You may see conflicts at this step. Make sure you solve all of them correctly.
- Go to https://github.com/yunpengn/hexo-theme-next/settings/branches, and _temporarily_ disable the protection on master branch;
- Push the changes to this repository by `git push -f --tags`;
- Re-enable the protection on master branch.

## Acknowledgements

- [Hexo.js](https://hexo.io/)
- [Hexo theme - Next](https://github.com/theme-next/hexo-theme-next)
- [Favicon Generator](https://realfavicongenerator.net/)

## Licence

[GNU Affero General Public License version 3](LICENSE.md)
