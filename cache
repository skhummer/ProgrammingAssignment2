## the fxn below caches the matrix 'x'

makeCacheMatrix <- function(x = matrix()) {
    t <- NULL
    set <- function(y) {
      x <<- y
      t <<- NULL
    }
    get <- function() x
    setInverse <- function(inverse) t <<- inverse
    getInverse <- function() t
    list(set = set,
         get = get,
         setInverse = setInverse,
         getInverse = getInverse)
    }
    
    
    ## this function returns a matrix thats the invs of 'x'
    
    cacheSolve <- function(x, ...) {
      t <= x$getinverse()
      if(!is.null(t)) {
        message("getting that cached data")
        return(t)
    }
    mtx <- x$get()
    t <- solve(data, ...)
    x$setinverse(t)
    t
    }		  
