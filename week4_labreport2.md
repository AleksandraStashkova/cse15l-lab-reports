The first change occured when we worked on removing the exclamation mark before the image link. Since the program was looking for the opening bracket first,
we needed to get rid of the exclamation to receive the actual link printed.


**Preface:** unfortunately, thougout the week 3 and 4 I had to jump between two separate lab sessions and in total of 3 TAs. That had resulted in the absence of 
required code changes and surely overall understanding of the material. I decided to start over and re-do the lab assignments on my own. My code changes are: 


> Code Change 1
The first code change will reference the fact that while testing the test2.md file, the program does not realize the difference between the link and the image. The output:

![image](SS1.png)

This bug is actually cause by the fact that the program ignored the "!" in the beginning. This is why I am going to implement a following change: