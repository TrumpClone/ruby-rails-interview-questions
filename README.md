# Ruby/Rails Interview Questions

A collection of interview questions about Ruby/Rails. Contributions and pull requests are kindly welcomed!

# Ruby

- What are Ruby mixins, how do they work, and how would you use them? What are some advantages of using them and what are some potential problems? Give examples to support your answers
- What is a `Symbol`?
- Compare and contrast `Symbols` and `Strings` in Ruby? Why use one vs. the other?
- Describe multiple ways to define an instance method in Ruby
- In Ruby, which is generally the better option: a recursive function or an iterative one?
- What are `#method_missing` and `#send`? Why are they useful?
- What are the various Ruby runtimes, and how are they different?
- What's the difference between an instance variable, a class instance variable and a class variable? Why would you use one over the other?
- What does `self` mean when used in a class?
- What does it mean that _"everything in Ruby is an object"_?
- What is a `Hash`? How efficient is reading/writing/iterating over one?
- What are `blocks`? Write a method that takes a `block` as an argument
- What is the difference between a `lambda`, a `block` and a `proc`?
- What about closures in Ruby? What are they?
- Explain what `a ||= b` means
- What is memoization?
- Have you heard the term PORO? Do you know what it is?
- Is it bad to rescue `Exception`? Why?
- What's the difference between the `and` and `&&` operators? Why use one over the other?
- What is meta-programming, what methods of meta-programming does Ruby support, and when/why would you use it (or not) in a project?
- What does the `lazy` method do to enumerators and why is that useful?
- Talk about SOLID principle
- Go through Basic OOP principles — encapsulation, abstraction, polymorphism and inheritance
- What's the difference between `include` and `extend`?
- Understand access modifiers and how they are used within the ruby language (`private`, `public`, `protected`)
- Why do some methods end with a bang `!` and others with question marks `?`, what are they called and what do they do?
- What is a `Class`, what is an `Object` and why we need `Modules`?
- Why `Enumerable` is so useful?
- Why would you use `BigDecimal` over `float`?
- When do you prefer to use `fetch` over `[]` on `Hash` (and other way around) and why?

# Rails

- Explain the processing flow of a Rails request
- What is REST?
- Describe the Rails Asset Pipeline and how it handles assets (such as JavaScript and CSS files).
- What is ActiveRecord and what is Arel? Describe the capabilities of each
- What is the _Convention over Configuration_ pattern? Provide examples of how it is applied in Rails
- What is the _fat model, skinny controller_ approach? Discuss some of its advantages and pitfalls, as well as some alternatives
- Describe the Rails testing philosophy
- Explain the use of `yield` and `content_for` in layouts and provide examples
- What are `N+1` queries and how can you avoid them? How would you find/debug `N+1` query?
- What are filters in Rails? Describe the three types of filters, including how and why each might be used, and the order in which they are executed. Provide examples.
- What is Rack middleware? How does it compare to controller filters/actions?
- Explain what Rails’ mass-assignment vulnerability is and Rails’ method to control field access
- Why do some people say _"Rails can't scale"_?
- When is Rails a good choice for a project?
- What are some of the drawbacks of Rails?
- How do you sort an `Array` of objects by a particular attribute? What is a better way to do sorting with ActiveRecord?
- Explain the different pieces of Rails
- What are the different server options for running a Rails/Rack app?
- Explain CSRF and how Rails combats it
- Explain various forms of caching available in Rails
- What are some Ruby web server options?
- How is something like `30.seconds.ago` implemented?
- What is Rails concern?
- Which Rails server are you using?
- Which HTML template engine does Rails support?
- What are some ActiveRecords callbacks which you are familiar with?
- Does ActiveRecord have `after_delete` callback?
- What are the benefits of using active records as opposed to native SQL queries. On which occasion should you be choosing one over the other?
- Explain Rails DB migrate, and the benefits that comes along with that?
- Explain how Rails' scaffolding works and why you would want to use them
- What is database transactions and how it is represented in Rails?
- Explain ActiveRecord’s associations (all of them)
- What are scopes in ActiveRecord?
- Where would you use `#pluck` and why exactly is it useful?

# Meta

- Algorithms and Data Structures
- Database Design and SQL
- Testing (TDD and BDD)
- System Design
- DevOps

# References

- https://www.toptal.com/ruby-on-rails#hiring-guide
- https://www.toptal.com/ruby/interview-questions
- https://www.quora.com/How-do-I-prepare-for-an-entry-level-Ruby-on-Rails-developer-interview-What-questions-should-I-expect
- https://github.com/afeld/rails_interview_questions
- https://github.com/rishiip/ruby-on-rails-interview-questions
- https://gist.github.com/ryansobol/5252653
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
