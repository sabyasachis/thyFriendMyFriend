# thyFriendMyFriend
Implementation of the paper titled "Thy Friend is My Friend: Iterative Collaborative Filtering for Sparse Matrix Estimation"

All the python files are in jupyter notebook.

## Directory structure of this repository:
- data        : contains datasets which we can use for running the implementation on
- play        : this contains all the files which stores most of our rough work. You
                may not be interested to explore this folder unless you are interested
                in understanding how the implementation was developed
- *src*         : contains the main jupyter notebook(s). It has list of all
                implementation functions adapted from the paper. There might be
                some other substitute functions which can also be used for
                performance comparisons
- *testscripts* : contains all testcripts which can be used to test datasets. You
                can run it to directly call the functions implemented in src/ jupyter
                notebooks

## Run this implementation (right away):
- after cloning the repository
- go to testscripts/ folder
- open testscript_std.ipynb jupyter notebook
- do 'run all cells'.
Or you could run each cell one by one to better understand the overall
code layout.

## Paper implementation
- Go through src/finalcode.ipynb

## Results
- We note (according to paper) that for recommendation datasets,
$$ if p > 1/n $$
where p is sparsity and n is dimension of the matrix
then Mean Square Error of the algorithm in paper is bounded by
$$ MSE = O((pn)** (-1/5)) $$
