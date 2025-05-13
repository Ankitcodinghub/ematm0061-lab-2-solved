# ematm0061-lab-2-solved
**TO GET THIS SOLUTION VISIT:** [EMATM0061 Lab 2 Solved](https://www.ankitcodinghub.com/product/ematm0061-lab-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93056&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EMATM0061 Lab 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This document describes your second assignment for Statistical Computing and Empirical Methods (Unit EMATM0061) on the MSc in Data Science. Before starting the assignment it is recommend that you first watch video lectures 3, 4 and 5.

You are encouraged to discuss these questions with your colleagues.

Begin by creating an Rmarkdown document with html output. You are not expected to hand in this piece of work, but it is a good idea to get used to using Rmarkdown.

You will need to install the Tidyverse set of packages if you have not already done so:

<pre>install.packages("tidyverse")
</pre>
Next load the Tidyverse library which is a superset of the ggplot2 library which we shall use for this assignment.

<pre>library(tidyverse)
</pre>
For the purpose of this assignment we shall use the Hawks data set from the Stat2Data package. This is a brilliant data set containing information about 908 Hawks collected by students and faculty at Cornell College in Mount Vernon, Iowa. First install the “Stat2Data” library:

<pre>install.packages("Stat2Data")
</pre>
We can then load the data set as follows.

This will load a data frame called “Hawks” into your environment. We will use a slightly smaller dataframe which we construct as follows:

<pre>hawksSmall&lt;-drop_na(select(Hawks,Age,Day,Month,Year,CaptureTime,Species,Wing,Weight,Tail))
</pre>
1 Visualisation

We begin by studying some of the concepts from Lecture 3. 1

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>library(Stat2Data)
data("Hawks")
</pre>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1.1 Types of variables

Check how many rows and columns hawksSmall using the dim() function. Use the head() function to display the top 5 rows of the hawksSmall data frame. Your result should look something like this:

## Age Day Month Year CaptureTime Species Wing Weight Tail ##1I19 91992 13:30 RT385 920219 ##2I22 91992 10:30 RT376 930221 ##3I23 91992 12:45 RT381 990235 ##4I23 91992 10:50 CH265 470220 ##5I27 91992 11:15 SS205 170157

For each of the following variables say whether they continuous, discrete or categorical. Discuss this with your colleagues.

1. Month 2. Species 3. Age

4. Wing 5. Weight

The information available at https://rdrr.io/cran/Stat2Data/man/Hawks.html may help. 1.2 What’s wrong with this plot?

Write down some problems with the plot displayed below.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
500

400

300

200

100

</div>
</div>
<div class="layoutArea">
<div class="column">
150 200 250

</div>
</div>
<div class="layoutArea">
<div class="column">
Culmen 10

20 30

</div>
</div>
<div class="layoutArea">
<div class="column">
Weight 2000

1500 1000 500

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Hopefully your report doesn’t contain plots like this!

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
1.3 Generate a histogram

Next use a combination of the functions ggplot() and geom_histogram to create a histogram plot of the weights of the Hawks within the hawksSmall data frame with bin widths of 100 grams. Your result should look something like this:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
150

100

50

0

</div>
</div>
<div class="layoutArea">
<div class="column">
0 500

</div>
<div class="column">
1000 1500 2000

Weight (gm)

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Describe the aesthetic used within this plot.

Which term best describes the shape of the data distribution of Hawk weights: “Unimodal”, “Bimodal” or “Trimodal”?

1.4 Generate a density plot

Use a combination of the functions ggplot() and geom_density() to create a density plot of the tail lengths of the Hawks within the hawksSmall data frame. Your result should something like this:

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Count

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
0.015

0.010

0.005

0.000

</div>
</div>
<div class="layoutArea">
<div class="column">
Create the following plots for yourself:

</div>
</div>
<div class="layoutArea">
<div class="column">
150

</div>
<div class="column">
200 250

Tail (mm)

</div>
</div>
<div class="layoutArea">
<div class="column">
Recreate your plot with the argument adjust = 0.5 and adjust = 1. Describe the role played by the adjust argument within the geom_density() function. How many modes does the data distribution of Hawk tail lengths have?

</div>
</div>
<div class="layoutArea">
<div class="column">
0.03

0.02

0.01

0.00

</div>
<div class="column">
Species CH

RT SS

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Density Density

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
150

</div>
<div class="column">
200 250

Tail (mm)

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
SS

RT

CH

</div>
<div class="column">
Species CH

RT SS

</div>
</div>
<div class="layoutArea">
<div class="column">
1.5 Scatter plots

</div>
</div>
<div class="layoutArea">
<div class="column">
150 200 250

Tail (mm)

</div>
</div>
<div class="layoutArea">
<div class="column">
How many aesthetics are present within the following plot? What are the glyphs within this plot?

</div>
</div>
<div class="layoutArea">
<div class="column">
2000

1500

1000

500

0

</div>
<div class="column">
Species CH

RT SS

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Weight (gm) Species

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
150

</div>
<div class="column">
200 250

Tail (mm)

</div>
</div>
<div class="layoutArea">
<div class="column">
Generate a plot similar to the above plot using the ggplot() and geom_point() functions. 1.6 Trend lines and facet wraps

Generate the following plot using the ggplot(), geom_point(), geom_smooth() and facet_wrap() functions.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
CH

</div>
</div>
<div class="layoutArea">
<div class="column">
RT

</div>
</div>
<div class="layoutArea">
<div class="column">
SS

</div>
</div>
<div class="layoutArea">
<div class="column">
900

600

300

</div>
<div class="column">
2000

1500

1000

500

</div>
<div class="column">
900

600

300

0

</div>
</div>
<div class="layoutArea">
<div class="column">
Species CH

RT SS

</div>
</div>
<div class="layoutArea">
<div class="column">
160 180 200 220

</div>
<div class="column">
150 200 250

Tail (mm)

</div>
<div class="column">
125 150 175 200 225

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
What are the visual cues being used within this plot? Based on the above plot, what can we say about the relationship between the weight of the hawks and their tail lengths?

As an additional challenge, if you have time, you could try adding an annotation to your plot which highlights the weight of the heaviest hawk in the data set.

If you want to learn more about ggplot2 take a look at the ggplot2 gallery https://exts.ggplot2.tidyverse. org/gallery.

2 Data wrangling

We next turn to the data wrangling concepts from Lecture 4.

2.1 Select and filter functions

Use a combination of the select() and filter() functions to generate a data frame called “hSF” which is a sub-table of the original Hawks data frame with the following characteristics:

1. Your data frame should include the columns:

a) “Wing”,

b) “Weight” c) “Tail”.

2. Your data frame should contain a row for every hawk such that:

a) They belong to the species of Red-Tailed hawks b) They have weight at least 1kg.

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Weight (gm)

</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Make use of the pipe operator to simplify your code.

How many variables does the dataframe hSF have? What would you say to communicate this information to a Machine Learning practitioner?

How many examples does the dataframe hSF have? How many observations? How many cases?

2.2 The arrange function

Use the arrange() function to sort the hSF data frame created in the previous section so that the rows appear in order of increasing wing span.

Use the head command to print out the top five rows of your sorted data frame. Your results should look something like this:

<pre>##    Wing Weight Tail
## 1  37.2   1180  210
## 2 111.0   1340  226
## 3 199.0   1290  222
## 4 241.0   1320  235
## 5 262.0   1020  200
</pre>
2.3 Join and rename functions

The species of Hawks within the data frame have been indicated via a two letter code. The correspondence between these codes and the full names is given by the following data frame.

</div>
</div>
<div class="layoutArea">
<div class="column">
## ## 1 ## 2 ## 3

</div>
<div class="column">
<pre>species_code species_name_full
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
CH RT SS

</div>
<div class="column">
<pre>     Cooper’s
   Red-tailed
Sharp-shinned
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Recreate the above data frame containing the correspondence between codes and the full species names and give your data frame an appropriate name.

Use a combination of the functions left_join(), the rename() and the **select()* functions to create a new data frame called “hawksFullName” which is the same as the “Hawks” data frame except that the Species column contains the full names rather than the two letter codes.

<pre>## Joining, by = "Species"
</pre>
Use a combination of the head() and select() functions to print out the top seven rows of the columns “Species”, “Wing” and “Weight” of the data frame called “hawksFullName”. Do this without modifying the data frame you just created. Your result should something like this:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##
## 1
## 2
## 3
## 4
## 5 Sharp-shinned  205    170
## 6    Red-tailed  412   1090
## 7    Red-tailed  370    960
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>   Species Wing Weight
Red-tailed  385    920
Red-tailed  376    930
Red-tailed  381    990
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Cooper’s  265    470
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Does it matter what type of join function you use here? In what situations would it make a difference?

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
2.4 The mutate function

Suppose that the fictitious “Healthy Hawks Society”1 has proposed a new measure called the “bird BMI” which attempts to measure mass of a hawk standardized by their wing span. The bird BMI is equal to the weight of the hawk (in grams) divided by their wing span (in millimeters) squared. That is,

Bird-BMI := 1000 × Weight/Wing-span2.

Use the mutate(), select() and arange() functions to create a new data frame called “hawksWithBMI” which has the same number of rows as the original Hawks data frame but only two columns – one with their Species and one with their “bird BMI”. The rows should appear in descending order of “bird BMI”. The top 8 rows of your data frame should look something like this:

<pre>##   Species  bird_BMI
</pre>
<ol>
<li>##1 &nbsp;RT 852.69973</li>
<li>##2 &nbsp;RT 108.75741</li>
<li>##3 &nbsp;RT 32.57493</li>
<li>##4 &nbsp;RT 22.72688</li>
<li>##5 &nbsp;CH 22.40818</li>
<li>##6 &nbsp;RT 19.54932</li>
<li>##7 &nbsp;CH 15.21998</li>
<li>##8 &nbsp;RT 14.85927</li>
</ol>
Use the filter() function to remove those cases where the bird BMI exceeds 100 from your data frame. Then generate a violin plot of your data which shows the distribution of “bird BMIs” broken down by species. Your result should look something like this:

</div>
</div>
<div class="layoutArea">
<div class="column">
SS

RT

CH

</div>
<div class="column">
Species CH

RT SS

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Species

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 4 16

Bird BMI

</div>
</div>
<div class="layoutArea">
<div class="column">
2.5 Summarize and group-by functions

</div>
</div>
<div class="layoutArea">
<div class="column">
Using the dataframe “hawksFullName”, from problem 3 above, in combination with the summarize() and the groupby functions, create a summary table, broken down by Hawk species, which contains the following

1Both the “Healthy Hawks Society” and the concept of “bird BMI” were made up purely for this assignment. 8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
summary quantities:

1. The number of rows;

2. The mean average wing span in centimeters;

3. The median wing span in centimeters;

4. The trimmed mean average wing span in centimeters (trim=0.1); 5. The mean average of the ratio between wing span and tail length.

Your final result should look something like this:

<pre>## # A tibble: 3 x 6
##   Species       num_rows mn_wing md_wing t_mn_wing tail_wing_ratio
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##   &lt;chr&gt;            &lt;int&gt;
## 1 Cooper’s            70
## 2 Red-tailed         577
## 3 Sharp-shinned      261
</pre>
</div>
<div class="column">
<pre>&lt;dbl&gt;   &lt;dbl&gt;     &lt;dbl&gt;           &lt;dbl&gt;
 244.     240      243.            1.22
 383.     384      385.            1.73
 185.     191      184.            1.26
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Next create a summary table of the following form: Your summary table will show the number of missing values, broken down by species, for the columns Wing, Weight, Culmen, Hallux, Tail, StandardTail, Tarsus and Crop. You can complete this task by combining the select(), group_by(), summarize(), across(), everything(), sum() and is.na() functions. You should end with a summary table of the following form:

<pre>## # A tibble: 3 x 9
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##   Species
##   &lt;chr&gt;
## 1 Cooper’s          1
## 2 Red-tailed        0
## 3 Sharp-shinned     0
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Wing Weight Culmen Hallux  Tail StandardTail Tarsus  Crop
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>&lt;int&gt;  &lt;int&gt;  &lt;int&gt;  &lt;int&gt; &lt;int&gt;
</pre>
</div>
<div class="column">
<pre>&lt;int&gt;  &lt;int&gt; &lt;int&gt;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
0 00 5 43 5 33

</div>
<div class="column">
0 0 0

</div>
<div class="column">
19 250 68

</div>
<div class="column">
<pre> 62    21
538   254
233    68
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
You can learn more about dplyr from the Tidyverse website https://dplyr.tidyverse.org/index.html.

3 Exploratory data analysis

We shall now illustrate some concepts from Lecture 5 on Exploratory Data Analysis in the context of our Hawks data set.

3.1 Combining location estimators with the summarise function

Use a combination of the summarise(), mean() and median() to compute the sample mean, sample median and trimmed sample mean (with q = 0.1) of the Hawk’s wing length and Hawk’s weight. Your result should look something like this:

<pre>##   Wing_mean Wing_t_mean Wing_med Weight_mean Weight_t_mean Weight_med
## 1  315.6375    322.2297      370    772.0802      779.3681        970
</pre>
Combine with the group_by() function to obtain a break down by species. Your result should look something like this:

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
<pre>## # A tibble: 3 x 7
##   Species Wing_mean Wing_t_mean Wing_med Weight_mean Weight_t_mean Weight_med
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##   &lt;fct&gt;       &lt;dbl&gt;
## 1 CH           244.
## 2 RT           383.
## 3 SS           185.
</pre>
</div>
<div class="column">
<pre>&lt;dbl&gt;    &lt;dbl&gt;       &lt;dbl&gt;
 243.      240        420.
 385.      384       1094.
 184.      191        148.
</pre>
</div>
<div class="column">
<pre>&lt;dbl&gt;      &lt;dbl&gt;
 410.       378.
</pre>
<pre>1089.      1070
 140.       155
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
3.2 Location and dispersion estimatiors under linear transformations

Suppose that a variable of interest Xi has values X1, . . . , Xn. Suppose that X1, . . . , Xn has sample mean μˆ. Let a, b ∈ R be real numbers and define a new variable X ̃i with values X ̃1,…,X ̃n defined by X ̃i = a·Xi +b fori=1,···,n. ShowthatX ̃1,…,X ̃n hassamplemeana·μˆ+b.

Suppose further that X1, . . . , Xn has sample variance SX2 . What is the sample variance of X ̃1, . . . , X ̃n? What is the sample standard deviation of X ̃1, . . . , X ̃n?

3.3 Robustness of location estimators

In this exercise we shall investigate the robustness of several location estimators: The sample mean, sample median and trimmed mean.

We begin by extracting a vector called “hal” consisting of the talon lengths of all the hawks with any missing values removed.

To investigate the effect of outliers on estimates of location we generate a new vector called “corrupted_hall” with 10 outliers each of value 100 created as follows:

We can then compute the mean of the original sample and the corrupted sample as follows.

<pre>mean(hal)
## [1] 26.41086
</pre>
<pre>mean(corrupted_hal)
</pre>
<pre>## [1] 27.21776
</pre>
Now let’s investigate what happens as the number of outliers changes from 0 to 1000. The code below generates a vector called “means_vect” which gives the sample means of corrupted samples with different numbers of outliers. More precisely, means_vect is a vector of length 1001 with the i-th entry equal to the mean of a sample with i − 1 outliers.

</div>
</div>
<div class="layoutArea">
<div class="column">
hal&lt;-Hawks$Hallux # Extract the vector of hallux lengths hal&lt;-hal[!is.na(hal)] # Remove any nans

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>outlier_val&lt;-100
num_outliers&lt;-10
corrupted_hal&lt;-c(hal,rep(outlier_val,times=num_outliers))
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
<pre>num_outliers_vect&lt;-seq(0,1000)
means_vect&lt;-c()
</pre>
for(num_outliers in num_outliers_vect){ corrupted_hal&lt;-c(hal,rep(outlier_val,times=num_outliers)) means_vect&lt;-c(means_vect,mean(corrupted_hal))

}

Copy and modify the above code to create an additional vector called “medians_vect” of length 1001 with the i-th entry equal to the median of a sample “corrupted_hal” with i − 1 outliers.

Ammend the code further to add an additional vector called “t_means_vect” of length 1001 with the i-th entry equal to the trimmed mean of a sample with i−1 outliers, where the trimmed mean has a trim fraction q = 0.1.

You should now have four vectors: “num_outliers_vect”, “means_vect”, “medians_vect” and “t_means_vect”. Combine these vectors into a data frame with the following code.

<pre>df_means_medians&lt;-data.frame(num_outliers=num_outliers_vect,
                             mean=means_vect,t_mean=t_means_vect,
</pre>
median=medians_vect)

Now use the code below to reshape and plot the data. The function pivot_longer() below is used to

reshape the data. Don’t worry if this operation is unclear at this stage. Its use will be explained soon.

<pre>df_means_medians%&gt;%
  pivot_longer(!num_outliers, names_to = "Estimator", values_to = "Value")%&gt;%
  ggplot(aes(x=num_outliers,color=Estimator,
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>                   linetype=Estimator,y=Value))+
  geom_line()+xlab("Number of outliers")
</pre>
The output of your code should look as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
100

80

60

40

</div>
<div class="column">
Estimator mean

median t_mean

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Value

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
0 250

</div>
<div class="column">
500 750

Number of outliers

</div>
<div class="column">
1000

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="section">
<div class="layoutArea">
<div class="column">
3.4 Box plots and outliers

Use the functions ggplot() and geom_boxplot() to create a box plot which summarises the distribution of hawk weights broken down by species. Your plot should look as follows:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
2000

1500

1000

500

0

</div>
</div>
<div class="layoutArea">
<div class="column">
CH RT SS

Species

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Note the outliers displayed as individual dots.

Suppose we have a sample X1, · · · , Xn. Let q25 denote the 0.25-quantile of the sample and let q75 denote the 0.75-quantile of the sample. We can then define the interquartile range, denoted IQR by IQR := q75 − q25. In the context of boxplots and outlier Xi is any numerical value such that the following holds if either of the following holds:

Xi &lt;q25−1.5×IQR Xi &gt;q75+1.5×IQR.

Create a function called “num_outliers” which computes the number of outliers within a sample (with missing values excluded).

Now combine your function num_outliers() with the functions group_by() and summarise() to com- pute the number of outlier for the three samples of hawk weights broken down by specied. Your result should look as follows:

<pre>## # A tibble: 3 x 2
</pre>
<ul>
<li>
<pre>## &nbsp;  Species num_outliers_weight
</pre>
</li>
<li>
<pre>## &nbsp;  &lt;fct&gt;                 &lt;int&gt;
## 1 CH                        3
## 2 RT                       13
## 3 SS                        4
</pre>
</li>
</ul>
3.5 Covariance and correlation under linear transformations

Suppose that we have a pair of variables: Xi with values X1, . . . , Xn and Yi with values Y1, . . . , Yn. Suppose that X1,…,Xn and Y1,…,Yn have sample covariance ΣX,Y . Let a, b ∈ R be real numbers and define a new variable X ̃i with values X ̃1,…,X ̃n defined by X ̃i = a·Xi +b for i = 1,··· ,n. In addition, let c, d ∈ R

</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Weight

</div>
</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
be real numbers and define a new variable Y ̃i with values Y ̃1,…,Y ̃n defined by Y ̃i = c·Yi +d for i = 1,··· ,n. What is the covariance between the pair of variables X ̃1, . . . , X ̃n and Y ̃1, . . . , Y ̃n?

Suppose that X1, . . . , Xn and Y1, . . . , Yn have correlation ρX,Y . What is the correlation between the pair of variables X ̃1,…,X ̃n and Y ̃1,…,Y ̃n?

</div>
</div>
<div class="layoutArea">
<div class="column">
13

</div>
</div>
</div>
