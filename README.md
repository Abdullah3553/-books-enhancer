# -books-enhancer
This is a small project to implement a CLI program.
this program should help us to rnhance the quality of the pdf books available online. 

# The general Idea 
If we had a PDF file that contain text only. Usually, these kind of files are sacanned files and it's not an actaul text inside the pdf. Its like an image taken form a scanner. 
usually, these kind of files are books. So what if we can build a simple program that scan the pdf file, recoginze the text inside the file, produce an actual text and write it on a new file. 
That's the general idea. 

# The steps and tools
- I can imagine somthing like that written in python. But I really want to make that on C++ so I iwill use C++:
- We need a way to handle arabic letters in the first place.
- We need a way of reading the pdf file and interfacing it inside c++. 
- We need a way to scan each page and lable the obejcts inside that page. Wither its te t or somthing else ( picture or something ).
- we need a way to detect the text and analyzing it into words. 
- Each word should be recognized as letters. 
- the letters should be rewritten into a new file in that word detetced place. 
- A way to handle the missed words and the end of each paragraph. 
- I guess thats all we need currently. 

# Project state
- This is gonna be a CLI program and it will analyze arabic letters only for now. 
- Maybe in the future more languages will be added.
- Also maybe a GUI will be implemented but, For now this is still a future plan.
- I'm working on this prject alone so the updates may take a while based on my free time . 
- Sorry for the spelling mistakes :p 