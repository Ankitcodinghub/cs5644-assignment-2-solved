# cs5644-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS5644: Assignment #2 Solved](https://www.ankitcodinghub.com/product/cs5644-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;33286&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS5644: Assignment #2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
<ol>
<li>(60 points) Machine learning has now permeated multiple disciplines, even politics. The current landscape in the US is rife with data scientists and other quantitative experts making predictions about ongoing and upcoming elections. Consider the Congressional Voting Records dataset&nbsp; from&nbsp; the&nbsp; UCI&nbsp; machine&nbsp; learning repository</li>
</ol>
(<u>https://archive.ics.uci.edu/ml/datasets/Congressional+Voting+Records)</u>.

&nbsp;

The dataset contains two files: one with a “.names” suffix and one with a “.data” suffix. The actual data is in the “.data” suffix and “.names” describes the metadata (i.e., describes what the different columns mean). Note that each row of the “.data” file contains one instance and includes both features and the class label (please take care to note the order). The machine learning&nbsp; problem&nbsp; here&nbsp; is&nbsp; to&nbsp; take&nbsp; the&nbsp; votes&nbsp; of&nbsp; US congressmen/congresswomen as input and predict whether they are a Republican or a Democrat. In particular, our goal is to solve this problem using both decision trees and a naïve Bayes classifier.

&nbsp;

First, spend some time understanding the structure of the dataset, how the instances are organized, how the features/class are organized, and so on. You need to “massage” this data into the form that scikit-learn requires before you can apply either a decision tree or a naïve Bayes classifier. So spend some time understanding and planning how you will do this massaging. You can do this in Python or in Excel or any way you choose. Note that this step is a natural part of the machine learning and knowledge discovery process. Data is rarely given in the&nbsp; form&nbsp; that&nbsp; machine&nbsp; learning&nbsp; can&nbsp; be&nbsp; directly&nbsp; applied,&nbsp; so&nbsp; that considerable effort goes into cleaning, manipulating, and massaging it. Do not apply scikit-learn before ensuring that it is in the form required.

&nbsp;

Just like the&nbsp; PlayTennis&nbsp; dataset,&nbsp; the&nbsp; features&nbsp; are&nbsp; binary-valued&nbsp; but note&nbsp; that some features have missing values for some rows (instances). You need to decide how you will handle them.

There are three possibilities here: i) discard instances that have missing feature values, ii) treat “missing” as if it is a value (and thus a binary feature becomes a ternary, or three-valued, feature), iii) impute missing values (i.e., for each feature, replace missing values with the most common value for that feature), so that they are no longer missing or unknown. If you read the “.notes” file, it explains why some values are missing and what they mean.

&nbsp;

<ul>
<li>Implement a decision tree and Naïve Bayes classifier for classification, with each of the above three ways of dealing with missing values. So you are experimenting with 6 scenarios.</li>
</ul>
&nbsp;

<ul>
<li>Perform 5-fold cross validation and report precision, recall, and F1-scores for each of the 6 scenarios.</li>
</ul>
&nbsp;

<ol start="2">
<li>(20+20=40 points) For what type of dataset would you choose decision trees as a classifier over Naive Bayes? Vice versa?</li>
</ol>
&nbsp;

(continued)

<strong>What to submit: </strong>

Exactly one zipped file containing:

<ul>
<li>a PDF document summarizing answers to questions 1 and 2. Do not submit pages and pages of code. Instead distill your lessons and experiences succinctly.</li>
<li>Either hyperlinks to or actual attachments of your data files and your iPython notebook(s).</li>
</ul>
&nbsp;

&nbsp;
