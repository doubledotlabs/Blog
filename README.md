This blog, hosted by [Double Dot Labs](https://doubledot.dev/blog/), exists as a centralized collection for documenting anything and everything that exists in open source software.

[![Freenode IRC channel.](https://img.shields.io/badge/irc.freenode.net-%23%23doubledotlabs-brightgreen.svg)](https://webchat.freenode.net/?channels=%23%23doubledotlabs&uio=MTY9dHJ1ZSY5PXRydWUmMTE9MjE1e1)
[![Twitter account.](https://img.shields.io/badge/twitter-%40doubledotlabs-blue.svg?color=43b4f9&logo=twitter)](https://twitter.com/doubledotlabs)
[![CLA assistant.](https://cla-assistant.io/readme/badge/DoubleDotLabs/Blog)](https://cla-assistant.io/DoubleDotLabs/Blog)

## Contributing

We encourage others to contribute to this collection. This repository is published under the public domain and is open to any kind of
positive contribution, including new contributions, spelling / grammar fixes, suggestions for more articles, and more.

You do not have to be a member of Double Dot Labs to contribute to this project. Double Dot Labs is a community that hopes to
improve Open Source and enable healthy collaboration. You can find more community resources, such as our code of conduct and
license agreements, in the [DoubleDotLabs/Community](https://github.com/DoubleDotLabs/Community) repository.

### Adding New Articles

To contribute an article to this collection, first [fork this repository](https://github.com/DoubleDotLabs/Blog/fork).

Next, create a markdown file in the forked repository named with the format `{year}-{month}-{day}-{title}.md`.

In order for your article to show up on the site, it will need to have a [front matter](https://jekyllrb.com/docs/front-matter/).
To properly index your article, copy the text below to the top of the file, replacing the required metadata where necessary. Each
submission must have a minimum of one tag, one author, and one citation.

For a list of available tags, see the files in [this directory](https://github.com/DoubleDotLabs/DoubleDotLabs.github.io/tree/master/_tags).
If there is a tag missing that you believe would be beneficial to the collection, please
[create a new issue](https://github.com/DoubleDotLabs/Blog/issues/new) with the title "New tag: {tag name}" explaining why it should be
added. It doesn't have to be long, just as long as it demonstrates that the tag has a specific purpose; it is not directly related to a
specific organization or project, but is more specific than something like `messaging`, which can have more than one meaning (e.g. text
messaging / social networks, firebase cloud messaging / server technology).

```
---
layout: blog
title: "Post Title"
description: "A short 1-2 sentence description of your article."
tags:
  - a
  - bunch
  - of
  - relevant
  - tags
author: "Primary Author / Group Name"
authors:
  - name: "Author Name"
    url: https://example.com/
    avatar: https://example.com/avatar.png
citations:
  - name: "Citation Name"
    url: https://example.com/
---
```

Place your article text below this front matter, formatted in [Markdown styling](https://guides.github.com/features/mastering-markdown/).
GitHub-flavored markdown is partially supported.

For various reasons, any articles about excessively controversial or political topics will not be accepted. Once your article is finished,
you will need to agree to the [Contributor License Agreement](https://cla-assistant.io/DoubleDotLabs/Blog), then you may
[create a pull request](https://help.github.com/en/articles/creating-a-pull-request) to have it reviewed and added to this collection. You
must have explicit permission from all authors of an article in order to contribute it to this blog.

### Improving Existing Articles

There are not many requirements for modifying an article that has already been accepted. You will still need to agree to the
[Contributor License Agreement](https://cla-assistant.io/DoubleDotLabs/Blog), then you may simply create a pull request stating the reasons
for you change and it will be reviewed and (hopefully) merged accordingly. You may add yourself to the list of authors in the metadata if you
wish (provided that this is not your sole reason for contributing).

## License

Content in this repository is dedicated to the public domain under the [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/).
By contributing to this repository, you relinquish any copyright ownership to the contributed material. A copy of the CC0 license is provided
[here](./LICENSE).

> To the extent possible under law, [Double Dot Labs Blog contributors](https://doubledot.dev/blog/authors/) have waived all copyright and related or neighboring rights to this work.
> 
> [![Creative commons license button.](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
