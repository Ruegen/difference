# Array intersection

When you forget how easy ruby makes things, especially at a job interview...
```ruby
a1 = ['alpha', 'bravo', 'charlie', 'delta', 'echo']
a2  = ['charlie', 'echo']
puts a1 - a2
# =>  ['alpha', 'bravo', 'delta']

puts a1 & a2
# =>  ['charlie', 'echo']
```