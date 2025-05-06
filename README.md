# stat240-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [STAT240 Assignment 5 Solved](https://www.ankitcodinghub.com/product/stat240-assignment-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97945&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STAT240 Assignment 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Bus disruptions

Consider the Twitter data in the file translink.RData provided in the archive for this homework (you can load this using the R command load). Write an R function translink that takes 4 numerical arguments: a year (a numeric value such as 2020), a month (a numeric value between 1 and 12, inclusive with 1 indicating January), and a day of the month, and an hour of the day (in 24 hour time). The R function should return a list with two elements: 1) an element with the name start and with value specifying a character vector enumerating all bus routes that started to have disruptions during the hour indicated by the date and time provided to the function, 2) an element with the name stop and with value specifying a character vector enumerating all bus routes that stopped having disruptions during the hour indicated by the dat and time provided to the function. You don’t have to care about timezones for this question: you can assume that the time specified by the parameters to the function are in the same time zone as the data in translink.RData. Disruptions are defined as starting or stop- ping only if a Tweet indicating such is present in translink.RData (i.e., you don’t have to consider times that fall outside of the data provided in translink.RData). Note that some of the tweets in translink.RData may be truncated: you may ignore the truncated portions (this is approxi- mate). Note that there are some corner cases among the tweets (not all of the disruptions are indicated with the same format). For full marks, consider some of the corner cases. Example usage is as follows:

&gt; disruptions = translink(2020, 1, 26, 3) &gt; disruptions$start

[ 1 ] “401” “406”

&gt; disruptions$stop

</div>
</div>
<div class="layoutArea">
<div class="column">
[1] “23”

</div>
</div>
<div class="layoutArea">
<div class="column">
1 of 2

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
STAT240 Spring 2022 SFU Due March 2nd 6PM PST

For bonus points, have your function use the Twitter API to down- load and process tweets for the provided hour (instead of using the static translink.RData file).

<ol>
<li>a) &nbsp;Provide a pdf containing all of the code that you wrote for this project. If your code spans multiple files, put all of the code into a single pdf and use comments to indicate the filenames. You may use code from outside public domain sources provided that you follow the guidelines for academic honesty, and you cite the sources clearly in the comments.
(10 points)
</li>
<li>b) &nbsp;Write a short report arguing that the code you’ve provided works as required, and provide a pdf of the report. For example, show the translink function being called with different arguments, and show that the corresponding elements of the data file prove that the cor- rect bus routes are returned. You could also show that for a given element of the data file, the appropriate parameters provided to the translink function can be provided to return that specific route.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2 of 2

</div>
</div>
</div>
