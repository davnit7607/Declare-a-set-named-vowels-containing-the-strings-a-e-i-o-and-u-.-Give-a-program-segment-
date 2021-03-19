# Declare-a-set-named-vowels-containing-the-strings-a-e-i-o-and-u-.-Give-a-program-segment-

#Abhinav kumar
def Vowel(ch): 
    return ch.upper() in ['A', 'E', 'I', 'O', 'U']   
def count(str): 
    count = 0
    for i in range(len(str)):  
        if Vowel(str[i]): 
            count += 1
    return count 
str = input("enter your string: ") 
c=count(str)
print("no of vowels: ",c)
