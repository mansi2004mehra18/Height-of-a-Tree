# Height-of-a-Tree

Height of a Tree

𝑂
(
𝑛
)
O(n)
𝑛
n nodes

pgsql
Copy
Edit
if (root == null)
    return 0;

lh = height(root.left)
rh = height(root.right)

height = max(lh, rh) + 1
height = 3