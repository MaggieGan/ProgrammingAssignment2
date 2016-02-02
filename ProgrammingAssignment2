## this function will cache the inverse result of a matrix 
## to avoid costly computation

## This function creates a special "matrix" object that can cache its inverse

makeCacheMatrix <- function(x = matrix()) {
  y<<-x
  inver<<-solve(x)
}


## This function computes the inverse of the special"matrix" returned by makeCacheMatrix above. 
##If the inverse has already been calculated(also not changed), then the cacheSolve should 
##retrieve the inverse from the cache.

cacheSolve <- function(x, ...) {
        ## Return a matrix that is the inverse of 'x'
  if(all(y==x)==TRUE){
    message("getting cached data")
    return(inver)
  }
  makeCacheMatrix(x)
  inver
}
