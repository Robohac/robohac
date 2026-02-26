na=int(input("hello! welcome to pytriplet finder.which coloumn no.you will give? I.e. 1st,2nd or 3rd"))
#it asks for the digit of a pythgorean triplet.
num=int(input("what is that no.="))
if na == 1:
    print(num,num/2-1,num/2+1)
elif na == 2:
    print((num+1)*2,num,num+2) 
elif na == 3:       
    print((num-1)*2,num-2,num)
feedback=str(input("is it gone good?"))
if feedback == "yes":
    print("thank you!")
else:
    print("try again!")
