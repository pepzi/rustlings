# My notes on rustlings

This is a collection of things I find especially interesting while working on the exercises

##### Some exercises
The following is a list of exercises I need to study more

    hashmaps3
    options2
    iterators4
    iterators5

##### Useful knowledge

- Traits as parameters, example:

    fn some_func(item: __impl SomeTrait__) -> bool { }

- It is also possible to accept items that implement multiple traits

    fn some_func(item: impl SomeTrait **+** OtherTrait) -> bool {