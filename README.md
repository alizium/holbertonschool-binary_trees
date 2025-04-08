🧠 Binary Trees
📚 Description
This project explores the fundamentals of binary trees, a core data structure in computer science. A binary tree is a hierarchical structure in which each node has at most two children — referred to as the left and right child.

The goal of this project is to implement various operations on binary trees, such as creation, insertion, traversal, and computation of properties like height and depth.

🧩 Data Structure
c
Copier
Modifier
typedef struct binary_tree_s
{
	int n;
	struct binary_tree_s *parent;
	struct binary_tree_s *left;
	struct binary_tree_s *right;
} binary_tree_t;
🧪 Features / Functions
binary_tree_node: creates a new node

binary_tree_insert_left: inserts a node as the left child

binary_tree_insert_right: inserts a node as the right child

binary_tree_delete: deletes an entire tree

binary_tree_is_leaf: checks if a node is a leaf

binary_tree_is_root: checks if a node is the root

binary_tree_preorder: traverses a tree using pre-order

binary_tree_inorder: traverses a tree using in-order

binary_tree_postorder: traverses a tree using post-order

binary_tree_height: measures the height of a binary tree

binary_tree_depth: measures the depth of a node

binary_tree_size: measures the total size of a tree

binary_tree_leaves: counts the leaves in a tree

binary_tree_nodes: counts nodes with at least one child

binary_tree_balance: measures the balance factor

binary_tree_is_full: checks if a binary tree is full

binary_tree_is_perfect: checks if a binary tree is perfect

🚀 Traversal Orders
Pre-order: root → left → right

In-order: left → root → right

Post-order: left → right → root