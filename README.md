#findPath
LeetCode challenge findPath

Write method findPath
Should take two params:
object
keys separated by dots as string
Return value if it exists at that path inside the object, else return undefined

#Algorithm
Start the program
create a function findPath that takes 2 arguments
2.1 Object as first argument and path as second
Split the path using split('.') function with .(dot) as parameter and store in a variable as an array
Use a for..of loop to iterate over array variable from step 3 (say pathArray)
4.1 Assign value of obj[pathArray] to obj
4.1.1 if step 4.1 value is undefined, assign obj to undefined and break the loop, else goto 4.1.2
4.1.2 else let loop run
End for..of loop
Return obj
