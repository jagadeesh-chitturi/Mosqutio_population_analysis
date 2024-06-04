# Mosqutio_population_analysis

<h2>This is part of my complete analysis, which I haven't added here as we are still publishing the Research paper and can't share all the work until the paper is published. Please feel free to contact me if you need further information</h2>

- This repo contains two files:
- One is the PDF version, which helps you visualize the plots as intended and not get altered due to differences in loading libraries or execution.
- The other is a Python notebook with detailed analysis, as informed above. I can't provide the input Data files yet.
<br>
<br>

<body><b> This analysis aims to find the best time to release the genetically modified mosquitoes, which, when mated, produce fewer offspring and help reduce the mosquito populations. As this process is very costly, it needs perfect analysis of the best time of the year to implement the strategy and the correct count of mosquitoes required as fewer might not affect the existing population, and large numbers are too expensive.</b></body>
<br><br>
<body> Here, we have 4 parameters 
<li>The duration of release, here 180 days (6 months)</li>
    <li>The frequency of release: currently every 7 Days </li>
    <li> Release start day: every 30 days, like starting from Jan as day 0 and ending Dec 334 days, a total of 365 days </li>
    <li>The count of releases ranging from 25 mosquitoes to 400 mosquitoes for every release </li>
    <li><b>NOTE:</b> The count of mosquitoes is the proportion of the population to reduce the load on numerical computations and faster experiments</li>
</body>

<br><br>


## one Scenario
<body> below is one of the scenarios where mosquitoes are released every <b>7 days</b> for <b>180 days(6 months)</b> starting <b> February </b> and releasing <b>75 genetically modified mosquitoes</b> each time into the environment  </body>

![image](https://github.com/jagadeesh-chitturi/Mosqutio_population_analysis/assets/117065124/66440fda-05c0-48f7-ae5c-b69b8710d99d)

<body><b> explanation for above plot</b>:
the green plot is the general population of female mosquitoes without experiments<br>
The blue plot is the after the release of mosquitoes. We can observe that the population has been declining since March, one month after the start of release. They continue to decline until 6 months, and after that, they go back to the same populations as before.<br>
<b>Conclusion:</b>So it is not effective in reducing the populations while there is an increasing trend in the populations as of February 2021 </body>
<hr>
<hr>


## Other Scenario

<body> below is other scenario where mosquitoes are released every <b>7 days</b> for <b>180 days(6 months)</b> starting <b>August 2021</b> and releasing <b>50 genetically modified mosquitoes</b> each time into the environment  </body>

![image](https://github.com/jagadeesh-chitturi/Mosqutio_population_analysis/assets/117065124/2fed468c-931a-49c5-b168-aac47a4c496d)

<body><b> explanation for above plot</b>:
the green plot is the general population of female mosquitoes without experiments<br>
The blue plot is the after the release of mosquitoes. We can observe that the population has been declining since September, which is one month after the start of release. They continue to decline until 6 months, and the population will be completely eradicated by March 2022.<br>
<br><b>Conclusion:</b> It is very much more effective than the previous one, where we released 75 mosquitoes every time. Yet, the population kept surviving, but here, we used only 50 mosquitoes every time, and the population has completely vanished. So, the analysis suggests that it is better to implement the technique during the declining trend of mosquitoes from August to January when they will usually not survive due to cold weather.</body>
