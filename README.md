practice-todo-list
==================

practice ruby skills by building a simple to-do app

### From here:
http://sirupsen.com/what-I-wish-a-ruby-programmer-had-told-me-one-year-ago/

* first solution: https://gist.github.com/6656de5cc00df7802c5e
* added interface: https://gist.github.com/94bc0e64442de04deb0b
* added meta-programming: http://gist.github.com/255203


```
class TodoList
  def self.load(file)
      # read the file, create a list, create items, add them
  end

  def initialize
  end

  def add(item)
  end

  def write(file)
    # write the file, only write the undone items
  end

  def [](id)
    @list[id]
  end
end

class TodoItem
# provide reader and setter for name and state

  def initialize(name)
    # store name
    # set state to undone
  end
end

# ---
# the library will be used like this:
# list = TodoList.load("todo.td")
# list[0].done = true
# list.add TodoItem.new("another cool item")
# list.write("todo.td")
#
```
