{{< Concepts >}}

# Add empty if

It is always valid to add an empty "if". May be needed before doing the [Move statement into all branches of "if-else"](move-statement-into-all-branches-of-if-else) refactoring. Can be used before [Remove empty "else"](remove-empty-else).

## Constraints and Limitations

* None

## Steps

1. Add an empty "if" section with a simple condition.

Change this

```cpp
//Some code
//Some more code
```

to this

```cpp
//Some code
if (x == 6)
{
    ...
}
//Some more code
```
