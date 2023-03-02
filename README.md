# C - Binary trees
This was a partner project in which we learned about the details, advantages, and disadvantages of using trees as data structures. We learned about how to qualify trees as well as how to traverse them. Throughout the project, we implemented binary, binary search, AVL, and Max Binary Heap trees.

## Tests ✔️

* Tester: Folder of test files for all tasks. Provided by ALX.

## Helper File

binary_trees.h: Header file containing definitions and prototypes for all types and functions written for the project.

Data Structure

``` struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
typedef struct binary_tree_s bst_t;
typedef struct binary_tree_s avl_t;
typedef struct binary_tree_s heap_t;
```

## Function Prototypes

 | File |  Prototype |
 | ---- | ---------- |
 |binary_tree_print.c | void binary_tree_print(const binary_tree_t *tree) |

