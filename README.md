# BinarySearchTree
>> patika.dev sitesinin Data Structures dersinin son proje odevidir.


Verilen ornege gore bir Inorder Traversal tree olusturmamiz isteniyor. Bu durumda;

Step 1: Verilen listenin siralanmmasi gerekir.
  [7,5,1,8,3,6,0,9,4,2] --> [0,1,2,3,4,5,6,7,8,9]

Step 2: root = list[5] = 5, left = [0,1,2,3,4], right = [6,7,8,9]

Step3: left.root = [2], left.left = [0,1], left.right = [3,4]
      right.root = [8], right.left = [6,7], right.right = [9]

...  if we go on recursively;

             5
          /     \
         2       8
       /  \    /   \
      1    4  7     9
     /    /  /
    0    3  6
