C-BinaryTrees

1-Project Overview:

C-BinaryTrees is a solo project focused on exploring the intricacies of binary trees. The project delves into the details, advantages, and disadvantages of using trees as fundamental data structures. Throughout the development process, I implemented various types of binary trees, including binary, binary search, AVL, and Max Binary Heap trees.

2-Key Components:

*Tests: The tests folder contains test files for all tasks, provided by ALX.

*Helper File: binary_tree_print.c is a vital C function responsible for printing binary trees in a visually appealing format.

*Header File: binary_trees.h is the project's header file, housing definitions and prototypes for all types and functions developed during the project.

3-Data Structures:



/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */

struct binary_tree_s

{
    
	int n;
    
	struct binary_tree_s *parent;
    	
	struct binary_tree_s *left;
    	
	struct binary_tree_s *right;
	
};

typedef struct binary_tree_s binary_tree_t;



4-Function Prototypes:

The project encapsulates various functions tailored for binary trees, including operations for traversal, insertion, deletion, balancing, and more.

5-Tasks:

The project is organized into multiple tasks, each addressing specific aspects of binary tree operations. Some noteworthy tasks include:

*New Node: 0-binary_tree_node.c creates a binary tree node with a given parent and value.

*Insert Left: 1-binary_tree_insert_left.c inserts a node as the left-child of another.

*Delete: 3-binary_tree_delete.c removes an entire binary tree.

*Is BST: 110-binary_tree_is_bst.c verifies if a binary tree is a valid binary search tree.

*BST Insert: 111-bst_insert.c inserts a value into a binary search tree.

*AVL Insert: 121-avl_insert.c inserts a value into an AVL tree.
