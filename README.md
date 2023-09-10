# Intelligent-Combination-of-Approaches-Towards-Improved-Bangla-Text-Summarization-Dataset

This repository contains the dataset of the following paper: <br />
IEEE Xplore Link: https://ieeexplore.ieee.org/document/10200846

ResearchGate Link: https://www.researchgate.net/publication/373294869_Intelligent_Combination_of_Approaches_Towards_Improved_Bangla_Text_Summarization

# Overview
Some passages are collected manually from online news portals and some are collected by web scrapping from online newspaper websites. Then the preprocessed the documents manually and examined the line number of the documents. The standard form have been maintained that if the document's line no is minimum 10 or more. As well as the category also have been checked . ’”’,’|’,’/’, blank space, etc unwanted characters are removed from the  collected passages. We have checked the uniqueness of passages whether it is not used in more than one document and also if the passages are relevant to the categories or not, is inspected. Some summaries are generated manually and some are generated by using our own made desktop app using the python tkInter interface which can generate human-made summaries very fast and accurately. We have checked the passages and summaries manually that if it contains the central idea of the source
document. We have used a code to check whether the summary fulfills 40% of the source document or not.

# Dataset

There are 8 classes in the dataset. 
Those are: 
1. Accident
2. Bangladesh
3. Crime
4. Economics
5. Entertainment
6. International
7. Politics
8. Sports

# Human generated summaries by using tools(python tkInter interface)
The tool is a time-saving way to generate the summary more accurately. Here home interface is shown up and seeing how many summaries have remained. Behind the reason for the white and black color of the box is remained summaries. If there are no remaining summaries, all boxes will be black-colored. There shows some history of generating a summary. If there has any recently added summary then it shows the date, time, document number, dataset number, category, and summary number. There has also shown the calculation of the total passage number, summary number, and remaining summary.
![](/images/tool1.PNG)

After clicking any dataset button then this page will be shown up. The box color will be white if there has any remained summary otherwise the color will be black. If we want to go back to our home interface, there has a back button for that.
![](/images/tool2.PNG)

This is the interface where the source document has shown and we have to select most main conceptual lines to make the summary. At top of the page, there have dataset number, category name, summary number, and document number. In the next line, there is the total number of lines of the document and shows how many lines 40% contains. Next comes the  picked line no at the time of clicking tick in the checkbox. Then at the bottom, there have back and submit button.
![](/images/tool3.PNG)

After clicking submit button the summary will be added successfully. For this, there will be shown up a "Summary Added Successfully" message box.
![](/images/tool4.PNG)

If more or less than 40% lines are picked then the error box will be shown up and contains "Forty percent not marked" message.
![](/images/tool5.PNG)

### Author's Info
   Alam Khan **Email: [alamkhaan1997@gmail.com]**

  Sanjida Akter Ishita **Email: [sanjidaakterishita@gmail.com]**

  Fariha Zaman **Email: [fariha.aust.99@gmail.com]**

  Ashiqul Islam Ashik **Email: [ashiqulislam170204070@gmail.com]**


