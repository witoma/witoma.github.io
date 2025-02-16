---
title: "Para sport classification"
excerpt: "A machine learning approach to recommending a class for a given strength impairment profile <br/><img src='/images/wheeltrack2.png'>"
collection: projects
author_profile: false
#permalink: /projects/projects-1
--- 



*What is this Para sport classification application?*  


The <a href="https://gamespeed.shinyapps.io/paraclass/" target="_blank">Para sport classification application</a> app can be found <a href="https://gamespeed.shinyapps.io/paraclass/" target="_blank">here</a>.


This application recommends a sports class based on a male wheelchair track athlete's strength impairment profile. The work is based on some of my previous research e.g., <a href="https://pubmed.ncbi.nlm.nih.gov/29175826/" target="_blank">this paper</a> which quantified clusters of strength impairment profiles that were consistent with the principle of "evidence-based classification". These principles and the practical implementation can be found <a href="https://pubmed.ncbi.nlm.nih.gov/25134747/" target="_blank">here</a> and <a href="https://pubmed.ncbi.nlm.nih.gov/29627091/" target="_blank">here</a>.


*How to use the application*  

In the left sidebar simply use the sliders to select the force generated by six muscle groups (the strongest and weakest pronators, the trunk only, the strongest and weakest arm extensors, and the trunk and arms simultaneously). You will also need to select a wheelchair top speed.  

After you select these values, press the green refresh button in the sidebar.  

After processing, on the top row of values, a recommended class will appear along with an estimated top speed and prediction intervals. The "decisions" from each classifier are also displayed. With one exception, if there is a discrepancy between the three classifiers, the majority is the recommended class. The exception is when the athlete's actual top speed (that you enter in the sidebar) is greater than the upper prediction interval displayed on the top row. When this happens, the recommended class is the highest class shown across the three classifiers.  

Currently, the application is password protected. If you would like to try it out please contact me and I will send you a username and password.  
