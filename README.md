
# ECE231L Homework Week 12- Priority Queue

## Overview

For this assignment I have given you skeleton code for the PriorityQueue class.
Implement it.

## PriorityQueue

```
template<typename T, typename Compare>
class PriorityQueue
{
  protected:
    std::vector<T> c;
    Compare comp;
  
  public:
  
  operator=(const PriorityQueue&)
  const T& top() const;
  void push(const T&);
  void pop();
  bool empty() const;
  size_t size() const;
  
  void print100values()
  {
  };
};
```

## Report

Create md file report with the following information. For each of the two compare classes.

  1. Time to load the unsorted `numbers` file
  1. Output the first 100 values in `c`.
  1. Time remove 1000 values.
  1. Output the first 100 values in `c`.
  
