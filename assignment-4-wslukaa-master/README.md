# COMP4651 Assignment-4 (8 marks)

### Deadline: Apr 9, 23:59 (Sunday)
---

In this assignment, you will write two Spark applications: word count (`word_count.ipynb`) and Web server log analysis (`apache_log.ipynb`). This assignment repo consists of the following three notebooks:

* `notebook_warmup.ipynb`: Warmup and VM testing (no grading)
* `word_count.ipynb`: WordCount application (**4 marks**)
* `apache_log.ipynb`: Apache log analysis (**4 marks**)

**Note:** Make sure you have completed [this](https://course.cse.ust.hk/comp4651/assignments.html) self-paced Spark tutorial. We will be running the three notebooks on **the same Spark VM** for the tutorial.

It is important to place the three .ipynb files to the **home directory** of your Spark VM: `/home/vagrant/`. You can `git clone` this assignment repo directly in Spark VM, and then copy the three notebook files to `/home/vagrant/`.

The following instructions assume that you have successfully launched the Spark IPython Notebook engine and connected to its web UI using the browser of your choice on your *host machine*. If you don't know how, please refer to `README.md` file in the Git repo of the self-paced Spark tutorial.

## Notebook Warmup and VM Testing (**no grading**)

We strongly recommend you test your Spark VM before getting started. Open `notebook_warmup.ipynb` in your web browser and follow the instructions there.

## Task-1: Word Count Application (**4 marks**)
Open the notebook file (`word_count.ipynb`) in your web browser and follow the instructions carefully. Once you've done coding, you'll submit your Python code to GitHub for autograding. You'll also need to explain your code to TA in the lab on April 10.

### Grading
* **Autograding (2 marks)**: You need to download the assignment code from your IPython Notebook environment. In the notebook web UI, You can click on "File", then hovering your mouse over "Download as", and then clicking on "Python (.py)". This will export your IPython Notebook as a `word_count.py` file to your computer. You can `git add` this file, then commit and push it to GitHub to submit your code.
* **Code explaination (2 marks)**: In the lab session on April 10, the TA will ask you to explain your code.

The autograder will give an *all-or-nothing* mark. That is, you will get no mark unless you have successfully completed **all** parts of this coding task.

## Task-2: Apache Web Server Log Analysis (**4 marks**)

Open the notebook file (`apache_log.ipynb`) in your web browser and follow the instructions carefully. Once you're done coding, you'll submit your python code for autograding. You'll also explain your code to TA in the lab session on April 10. 

### Grading
The grading scheme is exactly the same as that of Task-1: 2 marks for autograding and 2 for code explaination in the April 10 lab.
