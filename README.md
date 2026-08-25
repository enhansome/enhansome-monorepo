# Awesome Monorepo with stars

A curated list of awesome Monorepo tools, software and
architectures. Monorepos, short for mono-repositories, are
repositories that contain multiple projects, usually related to each
other.

Inspired by [vinta/awesome-python](https://github.com/vinta/awesome-python) ⭐ 315,914 | 🐛 15 | 🌐 Python | 📅 2026-08-25.

English | [简体中文](./README-zh-CN.md)

## Contents

* [Build systems & dependency management tools](#build-systems--dependency-management-tools)
* [Repository management tools](#repository-management-tools)
* [Good reads](#good-reads)
* [Version control systems & add-ons](#version-control-systems--add-ons)
  * [Git](#git)
  * [Mercurial](#mercurial)
* [Development process tools](#development-process-tools)
* [Notable public monorepos](#notable-public-monorepos)
* [Migration tools](#migration-tools)

## Build systems & dependency management tools

* [Bit](https://github.com/teambit/bit) ⭐ 18,460 | 🐛 89 | 🌐 TypeScript | 📅 2026-08-24 is a tool for building and managing JavaScript projects with multiple components, and managing the dependency graph of components.
* [Nix](https://github.com/NixOS/nix) ⭐ 17,561 | 🐛 2,925 | 🌐 C++ | 📅 2026-08-25 is a package and distribution build tool with remote caching, predominately used by NixOS.
* [Bolt Pkg](https://github.com/boltpkg/bolt) ⭐ 2,430 | 🐛 77 | 🌐 JavaScript | 📅 2024-06-01 is a super-powered JavaScript project management.
* [Bazel](https://bazel.build) is Google's monorepo-oriented build system. More on Bazel: [awesome-bazel](https://github.com/jin/awesome-bazel) ⭐ 1,239 | 🐛 13 | 📅 2024-11-13
* [OAO](https://github.com/guigrpa/oao) ⭐ 850 | 🐛 17 | 🌐 JavaScript | 📅 2023-01-03 is a Yarn-based, opinionated JavaScript monorepo management tool.
* [Spago](https://github.com/spacchetti/spago) ⭐ 832 | 🐛 40 | 🌐 PureScript | 📅 2026-08-17 is a PureScript package manager and build tool powered by Dhall and package-sets.
* [Symplify/MonorepoBuilder](https://github.com/Symplify/MonorepoBuilder) ⭐ 526 | 🐛 7 | 🌐 PHP | 📅 2026-07-31 is a PHP monorepo management tool.
* [baur](https://github.com/simplesurance/baur) ⭐ 379 | 🐛 32 | 🌐 Go | 📅 2026-08-01 builds only changed applications in a monorepo branch and manages build artifacts
* [MBT](https://github.com/mbtproject/mbt) ⭐ 219 | 🐛 22 | 🌐 Go | 📅 2023-10-13 is a build tool with differential build support.
* [Versio](https://github.com/chaaz/versio) ⭐ 125 | 🐛 13 | 🌐 Rust | 📅 2025-06-19 updates all version numbers in monorepo projects based on [conventional commits](https://www.conventionalcommits.org/), and can generate changelogs and tags.
* [Tainted](https://github.com/kynrai/tainted) ⭐ 60 | 🐛 3 | 🌐 Go | 📅 2021-01-15 is a tool to determine which Go packages need to be rebuilt in a monorepo.
* [Garment](https://github.com/Farfetch/garment) ⚠️ Archived is Farfetch's monorepo build system with centralized and customizable task management.
* [Layer-pack](https://github.com/layer-pack/layer-pack) ⭐ 30 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-18 is a Webpack plugin allowing monorepo structures via inheritable npm packages/code layers & es6 glob imports.
* [drkns](https://github.com/frantzmiccoli/drkns) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2024-07-10 is a simple and language agnostic monorepo build tool.
* [Buck](https://buckbuild.com/) is Facebook's monorepo-oriented build system.
* [GitLab CI](https://gitlab.com/gitlab-org/gitlab-ce/issues/19232) 11.4 supports running steps based on path changes.
* [Lerna](https://lerna.js.org/) is a tool for managing JavaScript projects with multiple packages, built on Yarn.
* [Nx](https://nx.dev/) is a build system for TypeScript monorepos and a set of monorepo management tools.
* [Pants](http://www.pantsbuild.org/) is a monorepo-oriented build system, used by Twitter, Foursquare and multiple other companies.
* [Please](https://please.build/index.html) a cross-language build system with an emphasis on high performance, extensibility and reproduceability.
* [pnpm](https://pnpm.js.org/en/) is a JavaScript dependency management tool that supports monorepos through a set of dedicated commands called `pnpm multi`.
* [Rush Stack](https://rushstack.io/) is a family of tools geared towards large scale TypeScript monorepos, and based around the [Rush](https://rushjs.io/) build orchestrator
* [Yarn](https://yarnpkg.com/blog/2017/08/02/introducing-workspaces/) is a JavaScript dependency management tool that supports monorepos through workspaces.
* [Turborepo](https://turborepo.org/) is a high-performance build system for JavaScript and TypeScript codebases.

## Repository management tools

* [meta](https://github.com/mateodelnorte/meta) ⭐ 2,217 | 🐛 34 | 🌐 JavaScript | 📅 2026-08-14 is a tool for managing multi-project systems and libraries. It answers the conundrum of choosing between a mono repo or many repos by saying "both", with a meta repo.
* [Syncpack](https://github.com/JamieMason/syncpack) ⭐ 2,088 | 🐛 17 | 🌐 Rust | 📅 2026-08-09 ensures consistent dependency versions in large JavaScript Monorepos.
* [Ultra Runner](https://github.com/folke/ultra-runner) ⭐ 1,246 | 🐛 59 | 🌐 TypeScript | 📅 2026-08-21 is a smart script runner and build tool for Lerna, Pnpm, Rush and Yarn. Scripts run concurrently, using the dependency topology. Builds keep track of file changes and are skipped when possible.
* [oao](https://github.com/guigrpa/oao) ⭐ 850 | 🐛 17 | 🌐 JavaScript | 📅 2023-01-03
* [wsrun](https://github.com/whoeverest/wsrun) ⭐ 512 | 🐛 24 | 🌐 TypeScript | 📅 2024-05-04 allows running a command in each package of a Yarn workspaces monorepo.
* [FBShipIt](https://github.com/facebook/fbshipit) ⚠️ Archived is a library written in Hack for copying commits from one repository to another.
* [Builder](https://github.com/FormidableLabs/builder) ⚠️ Archived is a tool that makes it possible to ship the same scripts across projects in a Node.js monorepo. For example, share build and testing scripts across projects.
* [monorepo-run](https://github.com/Akryum/monorepo-run) ⚠️ Archived is a collection of helpers to run scripts in each package of a yarn monorepo with a separated pane per package.
* [Lank](https://github.com/FormidableLabs/lank) ⚠️ Archived is a tool that links packages together in a Node.js monorepo using automatic configuration of `NODE_PATH` instead of symlinks. Lank also allows you to run the same commands across all (or subsets of all) packages.
* [adeira/shipit](https://github.com/adeira/shipit) ⭐ 46 | 🐛 0 | 🌐 JavaScript | 📅 2025-08-14 is a simplified JavaScript port of FBShipIt.

## Good reads

* [Why Google Stores Billions of Lines of Code in a Single Repository](https://research.google.com/pubs/pub45424.html)
* [Advantages and Disadvantages of a Monolithic Repository: A case study at Google](https://people.engr.ncsu.edu/ermurph3/papers/seip18.pdf)
* [Why you should use a single repository for all your company’s projects](https://www.drmaciver.com/2016/10/why-you-should-use-a-single-repository-for-all-your-companys-projects/)
* [Advantages of monorepos](https://danluu.com/monorepo/)
* [Monorepos make inner-source come to life](https://kevingoslar.medium.com/monorepos-make-inner-source-come-to-life-bd1592b0cadf)
* [What is a monorepo? (and Should You Use Them?)](https://semaphoreci.com/blog/what-is-monorepo).
* [Continuous Integration for Monorepos](https://semaphoreci.com/blog/continuous-integration-monorepos) for Semaphore-CI users.
* [monorepo.tools](https://monorepo.tools) - Monorepos explained

## Version control systems & add-ons

### Git

#### Tools

* [GVFS](https://github.com/Microsoft/GVFS) ⭐ 6,132 | 🐛 320 | 🌐 C# | 📅 2026-08-20 virtualizes the file system beneath your git repo so that git and all tools see what appears to be a normal repo, but GVFS only downloads objects as they are needed. Windows only.
* [josh](https://github.com/esrlabs/josh) ⭐ 1,913 | 🐛 119 | 🌐 Rust | 📅 2026-08-24 is a git server proxy enabling on-the-fly virtualization of repositories.
* [splitsh-lite](https://github.com/splitsh/lite) ⭐ 1,612 | 🐛 23 | 🌐 Go | 📅 2025-11-30 is a very fast git subtree alternative to splits subtrees from your project into subprojects.
* [git subtree](https://github.com/apenwarr/git-subtree) ⭐ 1,384 | 🐛 8 | 🌐 Shell | 📅 2017-07-20 merges and splits subtrees from your project into subprojects and back. Part of Git since version 1.7.
  * [git subsplit](https://github.com/dflydev/git-subsplit) ⭐ 327 | 🐛 18 | 🌐 Shell | 📅 2018-10-03 automates and simplifies the process of managing one-way read-only subtree splits.
* [mgt](https://github.com/nikita-skobov/monorepo-git-tools) ⭐ 39 | 🐛 15 | 🌐 Rust | 📅 2021-06-14 is a tool that enables easy bidirectional sync between multiple repositories via files that define how to remap a repository
* [go-diff](https://github.com/dstreamcloud/go-diff) ⭐ 32 | 🐛 1 | 🌐 Go | 📅 2023-12-27 is a handy tool analyzes which packages needed to be rebuilt due to changes.
* [Git shallow clones](https://git-scm.com/docs/git-clone) let you clone only part of your Git history.
  * [How to Use Git Shallow Clone to Improve Performance](https://www.perforce.com/blog/git-beyond-basics-using-shallow-clones)
  * [How to handle big repositories with Git](https://www.atlassian.com/blog/git/handle-big-repositories-git)
  * [Git clones vs Shallow Git clones](https://blogs.gnome.org/simos/2009/04/18/git-clones-vs-shallow-git-clones/)
* [Git filter-branch](https://git-scm.com/docs/git-filter-branch) let you rewrite a repository's history and prune branches.
  * [How to handle big repositories with Git](https://www.atlassian.com/blog/git/handle-big-repositories-git)
* [Git clone --single-branch](https://git-scm.com/docs/git-clone)
  * [How to handle big repositories with Git](https://www.atlassian.com/blog/git/handle-big-repositories-git)
* [Git sparse-checkout](https://git-scm.com/docs/git-read-tree/)
  * [Cloning specific folders from git](https://lakehanne.github.io/git-sparse-checkout)
  * [How to handle big repositories with Git](https://www.atlassian.com/blog/git/handle-big-repositories-git)
* [Git LFS](https://git-lfs.github.com/) improves the handling of large files in Git.
* [SlothFS](https://gerrit.googlesource.com/gitfs/+/HEAD/docs/manual.md) is similar to GVFS, but read-only. It works on Linux and macOS.

#### Scaling info

* Atlassian's [Monorepos in Git](https://developer.atlassian.com/blog/2015/10/monorepos-in-git/) and [How to handle big repositories in Git](https://www.atlassian.com/blog/git/handle-big-repositories-git) cover scaling options for Git.

### Mercurial

#### Tools

* [Watchman](https://github.com/facebook/watchman) ⭐ 13,693 | 🐛 257 | 🌐 C++ | 📅 2026-08-24, replaced by [fsmonitor](https://www.mercurial-scm.org/wiki/FsMonitorExtension) trigger partial, incremental builds when your files change

#### Scaling info

* [Scaling Mercurial at Facebook](https://code.facebook.com/posts/218678814984400/scaling-mercurial-at-facebook/)

## Development process tools

### Code reviews

* [Rietveld](https://github.com/rietveld-codereview/rietveld) ⭐ 585 | 🐛 242 | 🌐 Python | 📅 2025-03-01 is a code review tool by Google used by Chromium.
* [Pull Review](https://github.com/imsky/pull-review/) ⭐ 209 | 🐛 34 | 🌐 JavaScript | 📅 2023-03-02 Hubot plugin to automate pull reviews with lots of configuration options.
* [API Extractor](https://api-extractor.com/) is used to detect and review API signatures for TypeScript libraries, and also for publishing a multi-package API reference.

### CI tools

* [buildpipe](https://github.com/jwplayer/buildpipe) ⭐ 96 | 🐛 9 | 🌐 Go | 📅 2025-12-05 is a tool to dynamically generate Buildkite pipelines by looking at changes in projects.
* [bazel-travis](https://github.com/korfuri/bazel-travis) ⭐ 36 | 🐛 0 | 🌐 Python | 📅 2016-10-05 is a minimal setup to use Travis CI in a Bazel monorepo.
* [Incremental CI in Jenkins with Bazel](https://www.kchodorow.com/blog/2015/10/15/one-weird-trick-for-fast-ci/), article by Kristina Chodorow (Bazel team).
* [Codefresh](https://codefresh.io/) is a CI/CD platform for Docker/Kubernetes that has native [Monorepo support](https://codefresh.io/continuous-integration/using-codefresh-with-mono-repos/)
* [CI/CD for Microservices Using Monorepos](https://web.archive.org/web/20201109012429/http://blog.shippable.com/ci/cd-of-microservices-using-mono-repos), a post describing a Shippable.com build designed for triggering builds specific to the microservice that has actually been modified and ones depending on it.
* [Semaphore CI](https://semaphoreci.com) is a CI/CD platform with native [monorepo support](https://docs.semaphoreci.com/essentials/building-monorepo-projects/).

### Code ownership

* [CODEOWNERS generator](https://github.com/gagoar/codeowners-generator) ⭐ 66 | 🐛 20 | 🌐 TypeScript | 📅 2026-08-14 generates a CODEOWNERS file for your monorepo from files in subfolders.
* [Write Guard](https://github.com/geritol/write-guard) ⭐ 9 | 🐛 4 | 🌐 TypeScript | 📅 2023-03-05 uses GitHub actions to enforce file-level write access to a monorepo.
* [GitHub's CODEOWNERS](https://help.github.com/articles/about-codeowners/) can restrict who can approve a pull request that affects a given part of a monorepo.
* [Chromium's OWNERS file](https://chromium.googlesource.com/chromium/src/+/master/docs/code_reviews.md#OWNERS-files) inspired GitHub's CODEOWNERS.

## Notable public monorepos

* [NixOS's monorepo of packages and modules can be used to incrementally build and deploy Linux machines](https://github.com/NixOS/nixpkgs/) ⭐ 25,931 | 🐛 20,826 | 🌐 Nix | 📅 2026-08-25
* [Berty's monorepo - React-native mobile App + Golang backend + Gomobile bridge + iOS & Android native drivers + Protobuf](https://github.com/berty/berty/) ⭐ 9,278 | 🐛 92 | 🌐 TypeScript | 📅 2026-08-17
* [ProtonMail's monorepo (the proton web clients: mail, calendar...)](https://github.com/ProtonMail/WebClients) ⭐ 5,559 | 🐛 146 | 🌐 TypeScript | 📅 2026-08-25
* [M3 monorepo - Distributed TSDB, Aggregator and Query Engine, Prometheus Sidecar, Metrics Platform](https://github.com/m3db/m3) ⭐ 4,894 | 🐛 220 | 🌐 Go | 📅 2026-08-17
* [Habitat's monorepo](https://github.com/habitat-sh/habitat) ⭐ 2,748 | 🐛 23 | 🌐 Rust | 📅 2026-08-25
* [Celo's monorepo (includes blockchain, misc tooling, libraries, ops stuff like terraform modules, docs, etc)](https://github.com/celo-org/celo-monorepo) ⭐ 801 | 🐛 44 | 🌐 Solidity | 📅 2026-08-20
* [startup-os monorepo: working examples for Google's Open Source tools (bazel, etc) in a monorepo](https://github.com/google/startup-os) ⚠️ Archived
* [Entria's Full Stack Playground Monorepo](https://github.com/entria/entria-fullstack) ⭐ 498 | 🐛 2 | 🌐 TypeScript | 📅 2024-04-23
* [Foursquare's opensource projects](https://github.com/foursquare/fsqio) ⭐ 256 | 🐛 21 | 🌐 Scala | 📅 2024-07-30
* [Stellar's Go monorepo](https://github.com/stellar/go) ⚠️ Archived

## Migration tools

* [Gazelle](https://github.com/bazelbuild/rules_go#generating-build-files) ⭐ 1,482 | 🐛 497 | 🌐 Go | 📅 2026-08-24 generates Bazel BUILD files automatically for Go packages.
* [tomono](https://github.com/unravelin/tomono) ⭐ 920 | 🐛 4 | 🌐 CSS | 📅 2025-09-01 imports an existing set of Git repositories into a monorepo.
* [shopsys/monorepo-tools](https://github.com/shopsys/monorepo-tools) ⭐ 698 | 🐛 1 | 🌐 Shell | 📅 2026-08-11 contains a set of tools for building and splitting a monolithic repository.
* [Bazel's migration-tooling](https://github.com/bazelbuild/migration-tooling) ⚠️ Archived repository.
* [Fastlane monorepo migration tools](https://github.com/fastlane/monorepo) ⚠️ Archived tools for migrating code and github issues. Specific for fastlane so requires some code changes to use

## Development Workflows

* [Trunk Based Development](https://trunkbaseddevelopment.com), a source-control branching model, where developers collaborate on code in a single branch called ‘trunk’, resist any pressure to create other long-lived development branches by employing documented techniques. They therefore avoid merge hell, do not break the build, and live happily ever after.
* [Branch By Abstraction](https://www.branchbyabstraction.com), is a set-piece technique to effect a ‘longer to complete’ change in the trunk.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)]("http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Uriel Corfa has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
