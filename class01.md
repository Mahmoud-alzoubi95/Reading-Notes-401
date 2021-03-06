# Pain vs. Suffering

> That price is pain, the pain of growth
1. You’ll have to research for hours on end
2. You’ll Constantly be having to figure out how to collaborate with new people and deal with their (and your own) emotional quirks
3. You’ll be pushed physically, and while sitting in a chair and staring at your screen isn’t the most strenuous exercise in the world, the consecutive hours of it will take its toll

# Suffering is dependent on the story that we layer on top of our pain

* we must  consider heavily the story that you attach to it.

1. What’s your perspective?
2. Why are you doing this?
3. Do you want what comes at the end of this journey?
4. Are you doing this for you?

It’s not easy, nor is it common. This is why such skilled people are highly-valued in the industry. You are building your value.

# A beginner's guide to Big O notation

Big O notation is used in Computer Science to describe the performance or complexity of an algorithm.Its also, can be used to describe the execution time required or the space used by an algorithm.

1. O(1) : 

O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.
```
bool IsFirstElementNull(IList<string> elements)
{
    return elements[0] == null;
}
```

2. O(N)

O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set
```
bool ContainsValue(IList<string> elements, string value)
{
    foreach (var element in elements)
    {
        if (element == value) return true;
    }

    return false;
}
```
3. O(N2)

O(N2) represents an algorithm whose performance is directly proportional to the square of the size of the input data set. This is common with algorithms that involve nested iterations over the data set. Deeper nested iterations will result in O(N3), O(N4) etc.

```
bool ContainsDuplicates(IList<string> elements)
{
    for (var outer = 0; outer < elements.Count; outer++)
    {
        for (var inner = 0; inner < elements.Count; inner++)
        {
            // Don't compare with self
            if (outer == inner) continue;

            if (elements[outer] == elements[inner]) return true;
        }
    }

    return false;
}
```

4. O(2N)

O(2N) denotes an algorithm whose growth doubles with each additon to the input data set.<br>
 The growth curve of an O(2N) function is exponential - starting off very shallow, then rising meteorically.

 ```
 int Fibonacci(int number)
{
    if (number <= 1) return number;

    return Fibonacci(number - 2) + Fibonacci(number - 1);
}
```

## Logarithms

* ### **Binary search**:
 is a technique used to search sorted data sets. It works by selecting the middle element of the data set, essentially the median, and compares it against a target value. If the values match it will return success. If the target value is higher than the value of the probe element it will take the upper half of the data set and perform the same operation against it. Likewise, if the target value is lower than the value of the probe element it will perform the operation against the lower half. It will continue to halve the data set with each iteration until the value has been found or until it can no longer split the data set.
