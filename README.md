# Cucumber HTML Formatter

This is a cross-platform formatter that produces a pretty HTML report for Cucumber runs.

It is built on top of [@cucumber/react](https://github.com/cucumber/cucumber-react) and works with *any*
Cucumber implementation with a `message` formatter that outputs [cucumber messages](https://github.com/cucumber/common/tree/main/messages).

This formatter is built into the following Cucumber implementations:

* cucumber-ruby
* cucumber-jvm
* cucumber-js

## Contributing

The Java and Ruby packages are wrappers that bundle the build artefacts from the Javascript package.

Thus, to work on either the Java or Ruby packages, you will need to have installed Node.js first.

Once you have Node.js installed, you can use:

    make prepare

This will build the Javascript package and copy the required artifacts to the Java and Ruby packages.