# Skip lessons (2nd method)
1. open lesson

2. CTRL+SHIFT+I to open inspect element

3. click network tab (you may need to click arrow first)

![image](https://cdn.discordapp.com/attachments/651943340245516292/914032951849779220/unknown.png)


4. answer one question correctly, while looking at network tab
5. something like this should show up

![image](https://cdn.discordapp.com/attachments/651943340245516292/914033958432428123/unknown.png)

6. right click on it and press copy as fetch

(![image](https://cdn.discordapp.com/attachments/651943340245516292/914031560972464158/unknown.png)

7. paste it into any text editor (notepad), and find "slideCompletedArr" (if you can't find it, chances are you need to use the other method)

8. change all the "false" values to true

![image](https://user-images.githubusercontent.com/66990287/143670260-1ae936d9-73d4-4432-af42-b9f5f378530f.png)

![image](https://user-images.githubusercontent.com/66990287/143670282-59955a92-911b-4d1b-a557-cfde4d732ae1.png)

**IF ITS A QUIZ YOU ALSO NEED TO ADD ",1" FOR EVERY FALSE VALUE IN "AllScoreDataArr", LIKE SHOWN BELOW**

![image](https://user-images.githubusercontent.com/66990287/143670758-2edb97cd-2c52-4733-b5ad-92e2047a4a5f.png)

![image](https://user-images.githubusercontent.com/66990287/143671217-f8a5f63e-5fe9-4c52-aacb-4206d6bc2246.png)

9. copy it, and then press the x in the top right of the lesson to close the lesson

10. press the console tab at the top

11. paste it in, and press enter

12. if it says "Promise pending" or whatever, then you've done it correctly. sometimes you may need to open the lesson and complete the last question