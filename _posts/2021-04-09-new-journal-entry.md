# Notes from working on Week 2 assignments
---

- I've learned more about the maps method, which keeps coming up as useful. More specifically, I read about the idiomatic use of the map method as described here: https://www.brianstorti.com/understanding-ruby-idiom-map-with-symbol/.  It discusses the use of array.map(&:method_name), as the "&" usage was confusing.
- How about that ternary operator?!? https://www.rubyguides.com/2019/10/ruby-ternary-operator/ 
- In reviewing one of the solutions for Raindrops, I came across the use of '_'. I hadn't seen this before and found a great explainer here: https://po-ru.com/2012/09/21/rubys-magic-underscore. In brief, it's used to indicated an unused variable in a method call. Upon further reading, this post may provide a more recent and thorough review: https://genua.github.io/ruby/2015/03/04/underscores-ampersands-asterisks/#:~:text=The%20underscore%20adds%20as%20a,smaller%20count%20of%20array%20elements.
- AN interesting point on running tests from the reading:
  - The execution of each test method stops as soon as any error or an assertion failure is encountered, and the test suite continues with the next method. All test methods are executed in random order. The config.active_support.test_order option can be used to configure test order.
