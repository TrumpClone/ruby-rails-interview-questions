# Ruby/Rails Interview Questions

A collection of interview questions about Ruby/Rails.

There is a reason why there are no answers here — you as an interviewee should do your own research about things you don't know or fully understand. Self-study is the best way to learn but it doesn't mean you're on your own, feel free to drop by `#ruby` or `#rubyonrails` on [Freenode](https://freenode.net) and ask questions.

# Ruby

- What is a `Symbol`?
- Compare and `Symbol` and `String` in Ruby? Why use one vs the other?
- Describe multiple ways to define an _instance method_ in Ruby; now do similar for _class methods_
- Which is generally the better option (not only for Ruby): a recursive function or an iterative one?
- What are `#method_missing` and `#send`? Why are they useful?
- What are the various Ruby runtimes, and how are they different?
- What does `self` mean when used in a class?
- What does it mean that _"everything in Ruby is an object"_?
- What is a `Hash`? How efficient is reading/writing/iterating over one?
- What is a `block`? Write a method that takes a `block` as an argument
- What is the difference between a `lambda`, a `block` and a `proc`?
- What about _closures_ in Ruby? What are they?
- Explain what `a ||= b` means
- What is *memoization*? Why and when would you use it?
- Have you heard the term *PORO*? Do you know what it is?
- Is it bad to rescue `Exception`? Why?
- What's the difference between the `&` and `&&` operators?
- What's the difference between the `and` and `&&` operators? Why use one over the other?
- What is *meta-programming*, what methods of *meta-programming* does Ruby support, and when/why would you use it in a project?
- What does the `lazy` method do to enumerators and why is that useful?
- Why do some methods end with a bang `!` and others with question marks `?`, what are they called and what do they do?
- Talk about *SOLID* principle
- Go through Basic OOP primitives like _encapsulation_, _abstraction_, _polymorphism_ and _inheritance_
- What's the difference between `include` and `extend`?
- Describe access modifiers and how they are used within the ruby language (`private`, `public`, `protected`)
- How would you declare and use a _constructor_ in Ruby?
- How would you create _getter_ and _setter_ methods in Ruby?
- What is a `Class`, what is an `Object` and why we need `Module`?
- Does Ruby support _multiple inheritance_?
- What are *mixins*, how do they work, and how would you use them? What are some advantages of using them and what are some potential problems? Give examples to support your answers
- Explain what singleton methods are, what is _Eigenclass_ in Ruby?
- Describe Ruby method lookup path
- Describe available Ruby callbacks and how can we use them in practice?
- Why `Enumerable` is so useful? Elaborate on methods like `.each`, `.map`, `.inject`, `.reject`, _et cetera_ (also shortcut notation e.g. `.reduce(:+)`)
- Why would you use `BigDecimal` over `float`?
- When do you prefer to use `fetch` over `[]` on `Hash` (and other way around) and why?
- What's the difference between `local`, `@instance`, `@@class`, and `$global` variables? Why and where would you use specific type?
- How can you implement method overloading?
- How can you call the base _class method_ from inside of its _overriden method_?

# Rails

- Explain the different pieces of Rails
- Explain the processing flow of a Rails request
- Explain *MVC* in terms of Rails
- What is *REST*?
- Describe the Rails Asset Pipeline and how it handles assets (such as JavaScript and CSS files); bonus points for explaining what was the big change in Rails 5.1
- What is an *ORM*?
- What is ActiveRecord and what is Arel? Describe the capabilities of each
- What is the *Convention over Configuration* pattern? Provide examples of how it is applied in Rails
- What is the _fat model, skinny controller_ approach? Discuss some of its advantages and pitfalls, as well as some alternatives
- Describe the Rails testing philosophy
- Explain the use of `yield` and `content_for` in layouts and provide examples
- What is the purpose of layouts?
- What are `N+1` queries and how can you avoid them? How would you find/debug `N+1` queries?
- What are filters/actions in Rails? Describe the three types of filters, including how and why each might be used, and the order in which they are executed
- What is Rack middleware? How does it compare to controller filters/actions?
- Explain what Rails' mass-assignment vulnerability is and Rails' method to control field access
- How do you sort an `Array` of objects by a particular attribute? What is a better way to do sorting with ActiveRecord?
- What are the different server options for running a Rails/Rack app?
- Explain CSRF and how Rails combats it
- Explain various forms of caching available in Rails
- How is something like `30.seconds.ago` implemented?
- What is Rails _concern_?
- What is functionality of _helpers_?
- Which Rails server are you using?
- Which HTML template engine does Rails support?
- What are some ActiveRecords callbacks which you are familiar with?
- Does ActiveRecord have `after_delete` callback?
- What are the benefits of using active records as opposed to native SQL queries. On which occasion should you be choosing one over the other?
- Explain Rails DB migrate, and the benefits that comes along with that?
- Explain how Rails' scaffolding works and why you would want to use them
- What is _database transactions_ and how it is represented in Rails?
- Explain ActiveRecord’s associations (all of them)
- What are scopes in ActiveRecord? How should you use them?
- Where would you use `#pluck` and why exactly is it useful?
- Explain _eager loading_
- How can you eager load associated objects?
- What is difference between `render` and `redirect`?
- What is difference between `save!` and `save`? (Elaborate on general difference between AR methods with and without a bang `!`)
- What is difference between `form_for` and `form_tag`?
- What is the purpose of `environment.rb` and `application.rb` files?
- What is `request.xhr`?
- How can you list all routes for a Rails application?
- Give an example of nested routes usage
- What is _observer_ in Rails?
- What deployment tools do you use?
- Why do some people say _"Rails can't scale"_?
- When is Rails a good choice for a project?
- What are some of the drawbacks of Rails?

# Meta

Topics below require general Computer Science knowledge that is not tightly coupled with any _specific_ technology stack hence the more you know the better you'll be.

- Algorithms and Data Structures
- Database Design, SQL queries, NoSQL databases
- Testing (TDD/BDD)
- System Design
- DevOps
- Unix knowledge
- Networking
- Application Security

[Cracking the Coding Interview](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850/) is a good resource for high level overview.

# References

- https://www.toptal.com/ruby-on-rails#hiring-guide
- https://www.toptal.com/ruby/interview-questions
- https://www.quora.com/How-do-I-prepare-for-an-entry-level-Ruby-on-Rails-developer-interview-What-questions-should-I-expect
- https://github.com/afeld/rails_interview_questions
- https://github.com/rishiip/ruby-on-rails-interview-questions
- https://gist.github.com/ryansobol/5252653
- http://www.rubyinside.com/tips-hiring-ruby-web-developers-4757.HTML
- https://rubygarage.org/blog/how-to-interview-your-ruby-on-rails-developer
- http://anilpunjabi.tumblr.com/post/25948339235/ruby-and-rails-interview-questions-and-answers
- http://career.guru99.com/top-34-ruby-on-rail-interview-questions/
- http://blog.mypath.io/ruby-on-rails-interview-questions-that-will-land-you-the-job/
- https://srikantmahapatra.wordpress.com/2013/11/07/ruby-on-rails-interview-questions-and-answers/
- https://www.codementor.io/ruby-on-rails/tutorial/ruby-on-rails-interview-questions
- http://www.careerride.com/ruby-on-rails-interview-questions.aspx

# Contributing

Contributions are welcome. If you would like to correct an error or add new items to the checklist, feel free to create an issue and/or a PR. If you are interested in contributing regularly, drop me a line at the above e-mail to become a collaborator.
