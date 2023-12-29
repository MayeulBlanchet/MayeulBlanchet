from random import shuffle

words=input("mot1/mot2/mot3/mot4").split('/')
list_lenght=len(words)
print(words)
shuffle(words)
print(words)
if list_lenght<5:
    print(words[0],words[1])
else:    
    print(words[list_lenght-1],words[list_lenght-2],words[list_lenght-3])

