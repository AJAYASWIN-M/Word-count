# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

Step 1:Create a txt file to count the number of word in that file.

Step 2:Open the txt file in read mode using open().

Step 3:Using split() function to split the words in the txt file and count it.

Step 4:Save the python program using .py extention.

Step 5:Run the python program in terminal to get the output.

Step 6: Number of words in the txt file is displayed as the output


## PROGRAM:
```
## PROGRAM TO COUNT THE NUMBER OF WORDS
## DEVELOPED BY : AJAY ASWIN.M                                                                                                                                         ## REFERENCE NO :22009241
num_words=0
with open('a.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```
### OUTPUT:
![in](https://user-images.githubusercontent.com/118679692/214776728-5e077650-1acd-4aff-9cad-eb8b70ea7021.jpeg)




![out](https://user-images.githubusercontent.com/118679692/214776434-d8508358-ae67-40e2-852e-7fae0cf1e01c.jpeg)

## RESULT:
Thus the program is written to find the word count from a text.
