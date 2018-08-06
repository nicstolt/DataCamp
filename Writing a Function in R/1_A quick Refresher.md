# Writing a function in R

## Notes
* The parts of a function 
** Argument
** Body 
** Environment
* Return value is the last evaluated expression or the first evaluated ''' R return() ''' expression
* Functions can be treated like usual R objects

## Writing a function

``` R 
# Define ratio() function
ratio <- function(x, y) {
  x / y
}

# Call ratio() with arguments 3 and 4
ratio(3,4)
```
``` R 
## [1] 0.75
```
