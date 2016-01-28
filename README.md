# Ruby Reading List

This is a guide for Ruby junior developers who have finished their basic trainging but do not know where to continue. It also aims to help them get ready for work quickly. Suggestions, ideas, and pull requests are welcome.

## General

- [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide)
- [Rails Style Guide](https://github.com/bbatsov/rails-style-guide)

## Testing

- [Better Specs](http://betterspecs.org/) illustrates different patterns to write a readable and efficient test suite in RSpec.
- [FactoryGirl Getting Started Guide](https://github.com/thoughtbot/factory_girl/blob/master/GETTING_STARTED.md) is a good starting point in using factory in testing. This guide is very long, but you don't have to read through carefully. Less mistakes will be made once you grasp the essentials.

## Debugging

- (正體中文) [Debugging Rails入門：五個必備技巧](http://motion-express.com/blog/20141017-debugging-rails-5-skills) tells five basic concepts for dugging a Rails application.

## Refactoring

- [7 Patterns to Refactor Fat ActiveRecord Models](http://blog.codeclimate.com/blog/2012/10/17/7-ways-to-decompose-fat-activerecord-models/) offers various methods to refactor a model class following the idea of "fat model, skinny controller"

## Project Structure

- [The roles of the Gemfile](http://yehudakatz.com/2010/12/16/clarifying-the-roles-of-the-gemspec-and-gemfile/) explains why `Gemfile.lock` should be committed in your ruby project but not in gem development.

## Performance & Scaling

- [Why Do They Say Rails Doesn't Scale?](http://codefol.io/posts/why-do-they-say-rails-doesnt-scale) tells you the fundemental ideas of why people always make jokes that "Rails doesn't scals".
- [Mass inserting data in Rails without killing your performance](https://www.coffeepowered.net/2009/01/23/mass-inserting-data-in-rails-without-killing-your-performance/) offers 4 options for mass insert in ActiveRecord without decreasing the performance.

## Tips & Tricks

- [11 Ruby Tricks You Haven’t Seen Before](http://www.blackbytes.info/2016/01/ruby-tricks/)
- [Better Hash Injection using each_with_object](http://technology.customink.com/blog/2014/10/14/better-hash-injection-using-each-with-object/) and [Benchmarking each_with_object Against inject when building Hashes from Arrays](http://andycroll.com/ruby/benchmarking-each_with_object-against-inject-when-building-hashes-from-arrays/)
- [What is `bundle exec`?](http://stackoverflow.com/questions/6588674/what-does-bundle-exec-rake-mean)