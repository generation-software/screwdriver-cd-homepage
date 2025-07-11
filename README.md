# Homepage

![Netlify](https://img.shields.io/netlify/e282e4fe-b993-48c3-8187-80ce0b658f69?style=for-the-badge&logo=netlify&logoColor=white&labelColor=00C7B7)

> Forked Homepage for Screwdriver CD service

[Screwdriver](https://screwdriver-cd.netlify.app/) is a self-contained, pluggable service to help you build, test, and continuously deliver software using the latest containerization technologies.

## To start using Screwdriver

For more information about Screwdriver, check out our [guide](http://docs.screwdriver.cd).

## To start contributing to Screwdriver

Have a look at our guidelines, as well as pointers on where to start making changes, in our [contributing guide](http://docs.screwdriver.cd/about/contributing).

### Prerequisites
- [Bundler 2.0](https://bundler.io/blog/2019/01/03/announcing-bundler-2.html)

### Usage

```bash
$ bundle install
$ bundle exec rake --tasks
rake build    # Generate documentation
rake doctor   # Test configuration
rake publish  # Generate and publish documentation to gh-pages
rake serve    # Run a local documentation server
```

### License

Code licensed under the BSD 3-Clause license. See LICENSE file for terms.
