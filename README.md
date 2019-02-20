# COMP250-As3

Implemented methods in the DTNode (Binary Decision Tree) class:

1) DTNode.equals():
This method compares two DTNodes. Given another DTNode object, it checks if the tree the tree that is rooted at the calling 
DTNode is equal to the tree rooted at DTNode object that is passed as the parameter.

Two DTNodes are considered equal if:
a traversal (e.g. preorder) of each of the two trees encounters nodes that are equal;
internal node : the thresholds and attributes should be same;
leaf node : the labels should be same.

2) DTNode.ﬁllDTNode()
This method takes in a datalist (ArrayList of type datum) and should returns the calling DTNode object as the root 
of a decision tree trained using the datapoints present in the datalist variable.

3) DTNode.classifyAtNode()
This method takes in a datapoint (excluding the label) in the form of an array of type double (Datum.x) and should 
return its corresponding label (int).
