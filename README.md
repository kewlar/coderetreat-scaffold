# Scaffold for Coderetreat

This is a skeleton for setting up the empty TDD project when participating in
[Global Day of Coderetreat](https://www.coderetreat.org/) events.

## How to use

Clone the repo, then go into the subdirectory of the language that you're going to use, and follow the
following instructions:

### Ruby

(assuming you have already set up Ruby and Bundler) 

1. Run `bundle` to install the dependencies.
2. Run `bundle exec guard` to launch the test runner.

You'll have [Guard](https://github.com/guard/guard) running [RSpec](http://rspec.info/) and
[RuboCop](https://github.com/rubocop-hq/rubocop) in red-green-refactor configuration.
[Byebug](https://github.com/deivid-rodriguez/byebug) is also thrown in, just in case.

### Javascript

(assuming you have already set up Yarn)

1. Run `yarn` to install dependencies.
2. Run `yarn run watch` to launch the test runner.

You'll have [Babel](https://github.com/babel/babel) transpiler, [Jest](https://jestjs.io/) test runner, and
[ESLint](https://eslint.org/) linter.
