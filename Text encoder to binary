def binaryencoder(words):
   en = ""
   alphabets = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z']
   
   for char in words:
     if char.lower() in alphabets:
       a = alphabets.index(char.lower())
       b = bin(a+1)
       en = en + b + "."
     elif char == " " :
       en = en + " "
     elif char == "." :
       en = en + "|"
     else :
       en = en + char
     
   print(en)
   
while True:
  words = input("Enter your words: ")
  binaryencoder(words)
  
   
     
   
  
    

