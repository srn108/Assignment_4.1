# Assignment_4.1
# To write a function filter_long_words() that takes a list of words and an integer n and returns the list of words that are longer than n

def filter_long_words(lst1,number):
    lst2=[]
    for i in range(len(lst1)):
        if len(lst1[i])>number:
            lst2.append(lst1[i])
    
    return lst2

inputList =['one','two','three','four','twentytwo','twohundredandten']
inputIntegar =4

filter_long_words(inputList,inputIntegar) 
