Tree Visualizer Project
A web-based interactive visualization tool for Binary Trees, Binary Search Trees (BST), and AVL Trees. This project helps users understand tree structures and algorithms through dynamic animations and visual feedback.

Features
Three Tree Types:

Binary Tree (Level-Order Insertion)

Binary Search Tree (BST)

AVL Tree (Self-Balancing BST)

Interactive Operations:

Insert nodes with visual feedback

Delete nodes with animation

Search for nodes with path highlighting

Tree traversal animations (Pre-order, In-order, Post-order)

Reset tree functionality

Visual Elements:

Animated node highlighting during operations

Clear visualization of tree structure with connecting lines

Responsive design that works on different screen sizes

Notification messages for user feedback

Files Structure
Copy
tree-visualizer/
├── index.html              # Home page with tree type selection
├── htmlbinarytree.html     # Binary Tree visualization page
├── htmlbst.html            # BST visualization page
├── htmlavl.html            # AVL Tree visualization page
├── style.css               # Main stylesheet (shared)
├── stylebinarytree.css     # Binary Tree specific styles
├── styleavl.css            # AVL Tree specific styles
├── binarytree.js           # Binary Tree implementation
├── bst.js                  # BST implementation
├── avl.js                  # AVL Tree implementation
How to Use
Open index.html in a web browser

Select the type of tree you want to visualize:

Binary Tree

Binary Search Tree (BST)

AVL Tree

Use the controls panel to:

Insert values (enter number and click Insert)

Delete values

Search for values

Perform tree traversals

Reset the tree

Technical Details
Pure JavaScript implementation of tree algorithms

CSS animations for visual feedback

Responsive design using flexbox

Object-oriented approach with TreeNode and Tree classes

Visual representation using absolute positioning and SVG-like lines

Requirements
Modern web browser (Chrome, Firefox, Edge, Safari)

No server required - works directly from file system

Future Improvements
Add more tree types (Red-Black, Splay, etc.)

Implement additional operations (rotation visualization for AVL)

Add step-by-step explanations

Include balance factor display for AVL trees

Add zoom/pan functionality for large trees

License
This project is open-source and available under the MIT License.
