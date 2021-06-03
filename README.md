# 1st-R-Program
Caching the Mean of a Vector

The first function, makeVector creates a special "vector", which is really a list containing a function to

set the value of the vector
get the value of the vector
set the value of the mean
get the value of the mean

makeCacheMatrix: This function creates a special "matrix" object that can cache its inverse.
cacheSolve: This function computes the inverse of the special "matrix" returned by makeCacheMatrix above. If the inverse has already been calculated (and the matrix has not changed), then the cachesolve should retrieve the inverse from the cache.
