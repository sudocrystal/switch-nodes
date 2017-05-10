# switch-nodes

Write a method `switchNodes` that switches the order of two specific nodes in a linked list. You may assume that both values exist in the list.

For example, if the list initially stores these values:

[3, 7, 4, 9, 8, 12]

After the call `switchNodes(7,8)` the result should be:

[3, 8, 4, 9, 7, 12]

Assume that we are adding this method to the `LinkedList` class shown below. You may not call any other methods of the class to solve this problem, you may not construct any new nodes, and you may not use any auxiliary data structures to solve this problem (such as an array, ArrayList, Queue, etc). You also may not change any data fields of the nodes. **You must solve this problem by rearranging the links of the list.**

```ruby
class Node
  attr_accessor :data, :next

  def initialize(val,next_node=nil)
    @data = val
    @next = next_node
  end
end

class LinkedList
  def initialize
    @head = nil
    @size = 0
  end

  # methods
end
```

## Problem Source
This problem was modified from [UW's PracticeIt](https://practiceit.cs.washington.edu/problem/view/cs2/sections/linkedlists/switchPairs)
