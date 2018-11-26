# Balanced-Binary-Search-Trees
A project that implements size balanced binary search trees w/ various operations 


![Size Balanced BST](https://cdn-images-1.medium.com/max/1600/1*OmRV7P0YluY2ToRj44jKGA.gif)



------------------------------------------------------------------------------------------------
/* Function:  to_vector
   Description: creates a vector and populates it with the 
   elements of the tree (in-order) and returns the vector 
   as a pointer 
   
   Runtime:  O(n) where n is the number of elements in the tree.
*/

std::vector<T> * to_vector()

------------------------------------------------------------------------------------------------


/* Function:  get_ith
   Description:  determines the ith smallest element in t and
     "passes it back" to the caller via the reference parameter x.  
     i ranges from 1..n where n is the number of elements in the 
     tree.

   Return value:  If i is outside this range, false is returned.  
     Otherwise, true is returned (indicating "success").

   Runtime:  O(h) where h is the tree height
*/
bool get_ith(int i, T &x)

------------------------------------------------------------------------------------------------

/* Function:  num_geq
   Description:  returns the number of elements in tree which are 
   greater than or equal to x.

   Runtime:  O(h) where h is the tree height
*/
int num_geq(const T & x)

------------------------------------------------------------------------------------------------


/* Function:  num_leq
   Description:  returns the number of elements in tree which are less
   than or equal to x.

   Runtime:  O(h) where h is the tree height
*/


------------------------------------------------------------------------------------------------


int num_leq(const T & x)


/* Function:  num_range
   Description:  returns the number of elements in tree which are
   between min and max (inclusive).

   Runtime:  O(h) where h is the tree height

*/

int num_range(const T & min, const T & max)

------------------------------------------------------------------------------------------------


