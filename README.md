# 25_map-and-filter-
map() function , filter () function and difference

# Map():
The basic function of map() is to manipulate iterables. Map executes all the conditions of a function on the items in the iterable. for example, we have multiplied each element in the range 0–10 with 2 which gives us completely new list of elements. Map function takes all elements and allows you to apply a function on it and then passes it to the output which can have same as well as different values .

# b=list(map(lambda a:a%2==0,range(1,5)))#[False, True, False, True]
# a=list(map(lambda x:x*2,range(0,10)))#[0, 2, 4, 6, 8, 10, 12, 14, 16, 18]

# Filter():
As the name suggests, it is used to filter the iterables as per the conditions. Filter filters the original iterable and passes the items that returns True for the function provided to filter. Therefore only the items in the iterables can be expected to be seen in the output. In the above example the condition is given in the form of lambda function and the elements which satisfy the condition are given in the list. The elements which are divisible by 2 are left and others are filtered out.
# b=list(filter(lambda a:a%2==0,range(1,5)))#[2, 4]
# a=list(filter(lambda x:x*2,range(0,10)))#[1, 2, 3, 4, 5, 6, 7, 8, 9]

Map takes all objects in a list and allows you to apply a function to it whereas Filter takes all objects in a list and runs that through a function to create a new list with all objects that return True in that function. Hence, knowing the functionality and using it accordingly is important as both the functions have very minute difference in there functionality.

