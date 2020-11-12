"""
addition using tuple type data
"""
tuple_num = ((2,4), (6,8), (10,12))

def addition_func(tuple_num, addition):
    new_tuple = ()
    for item in tuple_num:
        temp = ()
        for x in item:
            val = x + addition
            temp = temp[0:] + (val,)
        new_tuple = new_tuple[0:] + (temp,)
    return new_tuple


numbers = addition_func(tuple_num, 5)
print(numbers)
