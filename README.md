### AwesomePrint
---
https://github.com/awesome-print/awesome_print

```
gem install awesome_print
git clone git://github.com/awesome-print/awesome_print.git

# irb>
"awesome print".ai
cat > 1.rb
ruby 1.rb

rails console
require "awesome_print"
ap Account.limit(2).all
ap Account

puts "red text".red


```


```ruby
require "awesome_print"
ap object, options = {}

require "awesome_print"
data = [ false, 42, %w(forty two), { :now => Time.now, :class => Time.now.class, :distance => 42e42 } ]
ap data
^D

require "awesome_print"
AwesomePrint.irb!

require "awesome_print"
AwesomePrint.pry!

logger.ap object

:log_level => :info

logger.ap object, :warn

#~/.aprc file.
AwesomePrint.defaults = {
  :indent => -2,
  :color => {
    :hash => :pale,
    :class => :white
  }
}

```

```erb haml
<%= ap @accounts.first %>
!= ap @accounts.first

<%= ap @accounts.first, :html => true %>

```
