# comp5710-workshop-9-solved
**TO GET THIS SOLUTION VISIT:** [COMP5710 Workshop 9 Solved](https://www.ankitcodinghub.com/product/comp5710-workshop-9-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121345&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5710  Workshop 9 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Workshop Name: Software Forensics Through Application of Logging in Machine Learning Code

Description

Identify logging locations in a machine learning (ML) code.

Targeted Courses

Software Quality Assurance

Activities

Pre-lab Content Dissemination

We first need to know what to log and how to log. Let us use the following heuristics.

Heuristics on what to log

Resources

Exceptions

Change issues

Heuristics on how to log

Include the name of the identity provider or security realm that vouched for the username, if that information is available. Include the affected system component or other object (such as a user account, data resource, or file).

Include the status that says if the object succeeded or failed.

Include the application context, such as the initiator and target systems, applications, or components.

Include â€œfrom whereâ€ for messages related to network connectivity or distributed application operation.

Include the time stamp and time zone help answer â€œwhen.â€ The time zone is essential for distributed applications.

Heuristics on how not log

Do not log user names and passwords

Do not log sensitive information, such as credit card numbers or social security numbers Do not log nullable objects

In-class Hands-on Experience

Open https://docs.python.org/3/library/logging.html

Learn about the common logging methods with Python

Integrate logging for simple.py. Target the basic important things to log.

import

Code will be saved and uploaded in this repo.

Demo will be recorded and uploaded on CANVAS.

Assignment 3 (Post Lab Experience)

1. poisoning attacks that are introduced through passing in erroneous dataset files into ML code

2. model tricking that are results of models that are being attacked, which gives erroneous results. Incorrect prediction performance is an indicator of ML models being attacked.

3. Assist Dolly by writing logging code in the correct locations in workshop9.py with comments so that the two above-mentioned issues are logged for all provided ML functions. After writing the code, put in comments to justify your code, save workshop9.py.

4. You have the freedom to choose the locations that you think needs to be logged

Sample Input/Output:

Input:

workshop9.py

Expected Output: Code and Comments

iris = datasets.load_iris() // initiated logging logging.basicConfig(filename=’app.log’, filemode=’w’, format=’%(name)s – %(levelname)s – %(message)s’)
