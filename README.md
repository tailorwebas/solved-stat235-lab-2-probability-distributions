Download Link: https://assignmentchef.com/product/solved-stat235-lab-2-probability-distributions
<br>
In this lab assignment you will use numerical and graphical tools available in Excel to examine the process of manufacturing of ultra-strong alloys used in fasteners, springs and instrument parts. You will use the process to explore the basic properties of binomial and normal distributions through computer experiment and simulation. In particular, you will verify the process target parameters and the process distribution assumptions.




We have used some functions available in Excel to develop three instructional templates (interactive worksheets) that allow you to review the properties of binomial and normal distributions. Some cells and charts in the interactive worksheets are protected and are therefore read only.

<h1>                                     Tensile Strength of Alloys</h1>

Carpenter MP35N alloy is a nonmagnetic, nickel-cobalt-chromium-molybdenum alloy possessing a unique combination of ultrahigh tensile strength and excellent corrosion resistance. In addition, this alloy displays exceptional resistance to high temperature oxidation. Because of its unique combination of properties, MP35N alloy has been used in a wide variety of applications including fasteners, springs, nonmagnetic electrical components and instrument parts in medical, seawater, and chemical and food processing environments. The alloys are delivered to customers in the form of rectangular in cross-section slabs.

According to the manufacturing specifications, the tensile strength of MP35N is supposed to follow a normal distribution with a mean of 285 ksi and a standard deviation of 5 ksi. The critical values for the tensile strength are 275 on the low side and 295 on the high side. The alloy slabs with the tensile strength values below 275 ksi or above 295 ksi are considered to be unacceptable. Too low tensile strength makes the alloys not strong enough for intended applications, whereas too high tensile strength makes them loose some desirable physical properties.




In this lab assignment you will examine the tensile strength distribution with Excel. The lab assignment is based on the Excel file <em>lab2.xls</em> located at http://www.stat.ualberta.ca/statslabs/index.htm (click <em>Stat 235</em> link, and <em>Data </em>for<em> Lab 2</em>). The file consists of four worksheets: <em>Normal Density</em>, <em>Normal Probabilities</em>, <em>Binomial Probabilities,</em> and <em>Data</em>. The first three are instructional templates; the fourth one contains data related to the above problem.

<ol>

 <li>Open the worksheet <em>Normal Density</em>. This worksheet contains a graph of the density function for the tensile strength (TS). The graph shares your screen with the values of  and . This will enable you to change those values and immediately see the change in the density function without scrolling your screen or changing worksheets. Use the interactive graph to answer the following questions:</li>

</ol>

<ul>

 <li>Assume that the mean of TS is set at 285.  Enter the value of  as 4, then 5, and eventually 6. After each entry, carefully examine the shape of the corresponding density curve. You are not supposed to print the density curves. Describe briefly the change in the appearance of the density curve as  increases from 4 to 6. What does the increase in the standard deviation value mean to the alloy strength in the  manufacturing process?</li>

 <li>Now assume that the standard deviation =5 and the mean TS changes. Enter the value of  as 280, then 285, and finally 290.</li>

</ul>

Describe briefly how the shape of the corresponding density curve changes. How does the change in the value of  affects the strength of the alloy? Does the fraction of alloy slabs with unacceptable TS (below 275 or above 295 ksi) increase or decrease? Explain briefly. Do not print the density curves.

<ol start="2">

 <li>In this part you will determine how the changes in the mean and standard deviation affect the fraction of alloy slabs that do not meet the TS specifications. Assume in this question that TS follows a normal distribution. Answer the questions below using either the template <em>Normal Probabilities</em> or the appropriate built-in functions in Excel.</li>

</ol>

<ul>

 <li>Suppose =285 and =5. What fraction of alloy slabs will have unacceptable tensile strength (TS below 275 or above 295 ksi)? What fraction would have unacceptable TS when the value of  were 283 with the same value of ? You do not have to print out the values displayed on the worksheet, just copy the numerical values from the screen to your report.</li>

 <li>Now suppose that the mean TS is 285 with the value of  equal to 6. What fraction of alloy slabs will then be unacceptable?</li>

 <li>What is the fraction of alloy slabs with the TS value within 1 standard deviation of the mean of 285? What is the fraction of slabs with tensile strength within 2 standard deviations of the mean? Assume here that  = 5 ksi.</li>

 <li>Assume =285 and =5. What is the TS value exceeded by 95% of slabs? What would be the TS value exceeded by 99 % of slabs?</li>

 <li>One possible way to reduce the fraction of unacceptable alloy slabs is to reduce the process standard deviation. What must the standard deviation  be in order that only 1% of slabs have the TS values less than 275 or larger than 295? Assume  = 285. Notice that the template or appropriate statistical function in Excel is not able to provide the answer to the above question directly. You will have to vary the standard deviation until you reach the desired percentile. Report the approximate value of  with two digits after the point.</li>

</ul>

<ol start="3">

 <li>Suppose that the manufacturing process is operating properly and tensile strength follows a normal distribution with a mean =285 ksi and a standard deviation =5 ksi. You will simulate the TS measurements with a random number generator in Excel.</li>

</ol>

You must use Excel in Windows environment to obtain the data (different data may be produced by <em>Random Number Generation </em>tool in Excel on MAC OS). Excel 2010 or higher version should be used in this part (earlier versions may produce different sequence of random numbers for the same seed).




Use the <em>Random Number Generation </em>feature (seed 200) to generate 1 sample of size 200 from the normal distribution with the mean of 285 and standard deviation of 5 in a new worksheet.  This corresponds to selecting randomly 200 slabs and obtaining a TS measurement for each of them. You may sort the data in ascending order to answer parts (a)-(c).

<ul>

 <li>Count the number of unacceptable slabs (TS below 275 or above 295) in the sample. Is the observed number of unacceptable slabs consistent with the theoretical prediction obtained in Question 2, part (a)?</li>

 <li>Determine the number of observations within 1, 2, and 3 standard deviations of the mean for the sample. Compare your results with the 68-95-99.7 Rule (see <em>Lab 2 Instructions</em>).</li>

 <li>Obtain the values of the standardized variable Z=(TS-)/ for each observation in the sample of 200 CDS observations.  Do not print the values in your report. What is the  distribution of the standardized values? Refer to the theory to answer the question.</li>

 <li>Use the <em>Descriptive Statistics</em> to calculate the mean and standard deviation of the standardized observations obtained in (d). Report the two values with four digits after the  decimal point. Are the values consistent with the distribution parameters provided by the  theory? Explain.</li>

</ul>

<ol start="4">

 <li>The manufacturer has recently implemented some changes in the manufacturing process that are expected to make the process more cost effective without compromising the process parameters. In order to evaluate the effect of the changes on the TS distribution, a random sample was taken consisting of 200 slabs, and the TS measurements were recorded in the worksheet <em>Data</em>. The data are not to be printed in your submission.</li>

</ol>

<ul>

 <li>Use the <em>Descriptive Statistics</em> tool to calculate the  mean and standard deviation of the 200 TS measurements. Are the values consistent with the target parameters (mean =285 ksi and a standard deviation =5 ksi)? Comment briefly.</li>

 <li>Obtain the relative frequency histogram for the 200 observations. Use the class intervals of width 5 with bins beginning at 270 and going to 300. The format of your histogram should be the same as the format of the sample histogram in the <em>Lab 1 Instructions</em> (labels, title, no gaps between bars). Paste the histogram into your report. Describe the pattern displayed in the plot. Is there any strong indication that the data do not follow a normal distribution? Explain briefly.</li>

 <li>Assuming normality and the population parameters close to the values produced by the sample (large sample size), would the manufacturer be able to achieve the goal of not  exceeding 5% limit on the proportion of unacceptable slabs (tensile strength less than  275 or more than 295 ksi)? Use the <em>Normal Probabilities</em> template to answer the</li>

 <li>Use your findings in parts (a)-(b) to prepare a brief report to management that indicates whether or not the changes have changed the tensile strength. In particular,  comment on the changes in the process parameters (mean and standard deviation) and  normality of the TS distribution.</li>

</ul>

<ol start="5">

 <li>In this question you will use the worksheet <em>Binomial</em> in <em>xls</em> file or the built-in functions in Excel for binomial and normal distributions. You do not have to print anything in this part. Just copy down the numerical values provided by the function or the template into your report.</li>

</ol>

<ul>

 <li>The manufacturer’s goal is not to exceed 5% limit on the proportion of unacceptable slabs (tensile strength below 275 or above 295 ksi). If the requirement is not met, the production process is discontinued while adjustments are made. One recognized way of monitoring production is to take a random sample from each hour’s production and to determine the fraction of unacceptable slabs. The manufacturer developed a criterion according to which the manufacturing process is discontinued for adjustments when a random sample of 200 slabs results in more than 15 unacceptable slabs.</li>

</ul>

How likely is shutting down the manufacturing process erroneously based on the sample data? In other words, what is the probability of obtaining more than 15 unacceptable slabs in a random sample of 200 provided the true fraction of unacceptable slabs does not exceed 0.05?




<ul>

 <li>The manufacturer claims that the target mean TS is 285 ksi with the value of  equal to 5 ksi. Assuming that this is true, calculate the probability that more than 15 unacceptable slabs (TS below 275 or above 295) will be obtained in a random sample of 200 slabs.</li>

</ul>

In both parts (a) and (b) give the parameters of the binomial distributions used and report the corresponding probabilities.








