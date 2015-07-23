# Let's test some Repls!

Below are some repls, some with whitespace, some without. They should all work.

%%%

### Ruby Repl Whitespace in Validation - 1 char

Write a method that returns 'ruby'

~~~ruby

def return_ruby
  # code your solution here
end

# do not remove the line below
return_ruby

~~~solution

def return_ruby
  "ruby"
end

puts_ruby_three_times

~~~validation 

assert_equal(response, "ruby")

~~~

%%%

Moving right along...

%%%

### Ruby Repl Whitespace in Validation - 4 chars

Write a method that returns 'ruby'

~~~ruby

def return_ruby
  # code your solution here
end

# do not remove the line below
return_ruby

~~~solution

def return_ruby
  "ruby"
end

puts_ruby_three_times

~~~validation 
 
assert_equal(response, "ruby") 
 
~~~

%%%

Now one with no whitespace...

%%%

### Ruby Repl - No Whitespace

Write a method that reverses a string, and call it, passing "12345" as an argument.

~~~ruby

# Code your solution here

~~~solution

def reverse(string)
  string.reverse
end

reverse("12345")

~~~validation

assert_equal(response, "54321")

~~~

%%%
