# csf211-lab-10-binary-search-trees-and-avl-trees-solved
**TO GET THIS SOLUTION VISIT:** [CSF211 Lab 10-Binary Search Trees and AVL Trees Solved](https://www.ankitcodinghub.com/product/csf211-lab-10-binary-search-trees-and-avl-trees-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91922&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSF211 Lab 10-Binary Search Trees and AVL Trees Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Topics: Binary Search Trees and AVL Trees

Exercise 1: [Expected Time: 5 + 40 + 15 + 15 + 25 =105 minutes] a) Define a tree node with four fields:

<ol>
<li>a value,</li>
<li>a pointer to the left sub-tree</li>
<li>a pointer to the right sub-tree and</li>
<li>height balance information, which is:</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
a) b) c)

</div>
<div class="column">
negative if the left subtree is taller, positive if the right subtree is taller, and zero if the subtrees are of the same height.

</div>
</div>
<div class="layoutArea">
<div class="column">
[Hint: Use bit-fields in struct so that minimum number of bits can be stored. E.g. struct { int x : 2; int y; } will direct a C compiler to assign two bits of storage for integer x. End of Hint.]

<ol start="2">
<li>b) &nbsp;Implement the binary search tree operations without balancing the height:
<ol>
<li>add</li>
<li>find and</li>
<li>delete [Hint: If the value to be deleted is in a leaf node it can be freed; if it is
not in a leaf node, then find the in-order successor, say s, and copy the value of s into this internal node. Then s is available for deletion and the same procedure can be applied recursively. End of Hint]
</li>
</ol>
</li>
<li>c) &nbsp;Implement the rotate operation of AVL tree such that rotate(bt, X,Y,Z):

Please read and understand the contents on the following URL before moving ahead: http://people.cs.ksu.edu/~schmidt/300s05/Lectures/Week13.html

<ol>
<li>orders X, Y, and Z as a, b, and c,</li>
<li>identifies the other children of X, Y, and Z as T0, T1, T2, and T3 in left-to-
right order
</li>
</ol>
and then balances bt by

<ol>
<li>replacing Z with b [Hint: This would require Z’s parent. You may use an additional parameter to the procedure if necessary passing the parent. End of Hint.]</li>
<li>setting a and c as the left and right children – respectively – of b</li>
<li>setting T0 and T1 as the left and right children – respectively – of a</li>
<li>setting T2 and T3 as the left and right children – respectively – of c</li>
</ol>
and returns the modified tree.
</li>
<li>d) &nbsp;Modify the add operation such that it:
<ol>
<li>identifies the point of imbalance and</li>
<li>invokes rotate with right parameters for height-balancing the binary tree.</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
e) Modify the delete operation such that it:

<ol>
<li>Identifies the first point of imbalance</li>
<li>invokes rotate with right parameter for height-balancing that sub-tree</li>
<li>and repeats a. and b until the root of the binary tree is balanced.</li>
</ol>
Exercise 2: [Expected Time: 15+30 = 45 minutes]

</div>
</div>
<div class="layoutArea">
<div class="column">
a) b)

</div>
<div class="column">
[Rank Query]: Implement an inorder traversal operation on binary search trees such that inorder(bt, K) returns the Kth smallest element in bt.

[Range Query]: Implement a rangeSearch procedure that given a binary search tree bt, and range K1..K2 of values, finds all the records in bt with keys in the given range. The algorithm would be based on deciding where the key of root value, say r.k, falls with respect to the range:

<ul>
<li> &nbsp;If r.k &gt; K2 then (recursively) search for the same range in the left subtree</li>
<li> &nbsp;If r.k &lt; K1 then (recursively) search for the same range in the right subtree.</li>
<li> &nbsp;If K1 &lt;= r.k &lt;= K2 then:</li>
</ul>
o Search for K1..(r.k) in the left subtree o Include r.k in the result

o Search for (r.k)..K2 in the right subtree

The result must be either accumulated in a non-local data structure or accumulated in a local data structure and returned from the procedure.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment to be uploaded:

Solve Exercise-1 and upload its solution. Your uploaded file must contain a file “complete.c” which includes all the functions implemented by you.

</div>
</div>
</div>
