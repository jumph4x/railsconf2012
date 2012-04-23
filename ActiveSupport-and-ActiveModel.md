**Presenter:** Bryan Liles

## Abstract

> Have you ever wondered what makes Rails tick? Bryan Liles will cover two of the pillars of the Rails foundation: ActiveSupport and ActiveModel. Together we will discover where some of Rails’ ease and power originates and how make use of it in your projects.

## Notes

### From @jumph4x

### ActiveSupport

* https://github.com/seyhunak/twitter-bootstrap-rails and https://github.com/ccocchi/sass-twitter-bootstrap-rails to not waste time with UI overhead 
* Benchmarking in rails is drop dead simple
* class attributes with cattr
* ActiveSupport callbacks made available and very easy with ActiveSupport
* Old requires of active_support pulled in everything. New pattern allows for ala carte includes of features you want


### ActiveModel

* Has a set of lint tests to be able to test your ORMish implementation against the API it expects. Things like an errors object that responds to :[], for example
* Validations can now apply to more than Rails models

### Additional advice

* Recommends use of pry-rails as a quick man-like reference for Ruby right within the console. Additionally allows to quickly edit loaded files with the `edit` command, loads the new code without reloading the console session. Also shows source for internal Ruby methods
* Reinforces writing tests first
* Reinforces reading the Rails source, mentions there are many useful remarks in the comments
* Shows a Rails 4 feature on how to extend behavior using Concerns. A new convention-over-configuration pattern



## External Links

* [Some related website](http://www.example.com/)
