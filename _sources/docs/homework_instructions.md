# Homework info & submission guidelines

You will be submitting your homework assignments on Gradescope.
Check out [Gradescope Student Guide](https://lthub.ubc.ca/guides/gradescope-student-guide/). 

## Accessing homework assignments

Each homework assignment will be made available on the [course GitHub page](https://github.com/UBC-CS/cpsc330-2024W1?tab=readme-ov-file#deliverable-due-dates-tentative) under the "Where to find?" column under the "Deliverable due dates" section.
You can also find the list of released (public) repositories [here](https://github.com/orgs/ubc-cpsc330/repositories).

Once the repository is ready, we'll make an announcement on Piazza.
Your homework assignment will generally consist of a Jupyter notebook along with necessary code and data or links to download the data.
You will have to setup your computer so that you can work on these assignments locally.
See this document for [setup instructions](setup.md).

## Use our template to create a repository

Here are the steps to create a repository for the released homework assignment.

1. Navigate to the homework assignment [from the list of repositories here](https://github.com/orgs/ubc-cpsc330/repositories).

1. On the GitHub repository, click "Use this Template" to create a repository under your account for this homework assignment.

![](img/template.png)

1. When cloning the repository, **remember to set the repository as "Private"** and name it something sensible so you can find it.

![](img/private_repo.png)

1. Clone the repository locally.

1. Complete your assignment, then commit and push your change to GitHub.

## How to submit

When you're ready to submit your assignment, make sure all your work in the Jupyter Notebook is saved, all changes in the repository are committed, and you've pushed up to GitHub.

### Preparation

1. Run all cells in your notebook to make sure there are no errors by running all cells: `Kernel -> Restart Kernel and Clear All Outputs` and then `Run -> Run All Cells`.

1. Notebooks with cell execution numbers out of order or not starting from “1” will have marks deducted. Notebooks without the output displayed may not be graded at all (because we need to see the output in order to grade your work).

### Submitting on Gradescope

1. Upload the assignment using Gradescope’s drag and drop tool. Make sure to access Gradescope via Canvas. Check out this [Gradescope Student Guide](https://lthub.ubc.ca/guides/gradescope-student-guide/) if you need help with your Gradescope submission.

1. Make sure that the plots and output are rendered properly in your submitted files.

1. If the `.ipynb` file is too big and doesn’t render on Gradescope, also upload a `pdf` or `html` in addition to the `.ipynb file`. If the `pdf` or `html` also fail to render on Gradescope, please create two files for your homework (e.g., `hw6a.ipynb` with Exercise 1 and `hw6b.ipynb` with Exercises 2 and 3) and include these two files in your repository.

You must **submit your final version of the notebook to [Gradescope](https://www.gradescope.ca)** where it will be graded.

Here is a video that shows you the process you'll be following (from a different course):

<div class="container youtube">
<iframe class="responsive-iframe" src="https://player.vimeo.com/video/1006094160?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Submit GitHub Repository on Gradescope"></iframe><script src="https://player.vimeo.com/api/player.js"></script>
</div>

Once you submit to Gradescope, you should go there and ensure your assignment is there as expected and all the output and plots are rendered properly. 

**It is your responsibility to make sure your assignment is submitted properly and failure to do so will result in a deduction of marks.**

## Additional submission instructions

### Datasets

Unless otherwise noted, if you download a dataset for your assignment, when you submit the dataset, the dataset will likely be removed from your submission, please do **not** submit the datasets. (If the dataset in bundled with the assignment, then it's fine to leave it there.)

### Report format

Your final report must be submitted online as a Jupyter notebook, so please do not write up your answers on paper! 

Be sure that your answers are clearly written and easy for the TA to understand. The TAs have the option to reduce your mark if your answers aren't clear or are difficult to understand (even if they are correct). 

Please do not delete the question cells or move the questions around. This will make things easier for the TAs.

**You must ensure that all your code output (values, tables, figures, etc.) is displayed in the notebook.** For example, if you are required to calculate some value, it is not sufficient to just store the value to a variable, nor is it sufficient to have a `print(value)` in your code - the print code must actually be run and the notebook saved, so that the output is shown on the screen when the notebook is rendered. Likewise, if there are tests (e.g. `assert` statements) provided in the code, make sure these are left in so we can see the output of the tests. This allows the TAs to see your results without running your code. Failure to display all output will result in a deduction of marks.

**If you are unsure whether your report is rendering properly, please view your submission in Gradescope. This is exactly how your TA will see it.**

### Figures

In most assignments, you will be asked to produce plots/figures. When including figures in your submission:

- Embed the figures in your report. Make sure your `.ipynb` file includes all the figures you want the TAs to see.
- All figures must include axis labels and, if multiple curves are present on the same figure, a legend.
- All figures must have some accompanying text explaining what the figure is about. You can do this by putting a figure title in the image itself (such as, "Training error vs. k") or you can use LaTeX to add figure captions that appear underneath the figure.
- Regardless of your image formats, all text must be big enough to read without straining or zooming. Please be careful about this for axis labels, legends, titles, etc. Avoid tiny text!

<!-- 
## Partners
**You must work alone for hw1 and hw2.** For hw3 onwards, I might consider allowing group submissions. (I'll update the instructions soon.) 
 -->

## Late submissions

By default late submissions will not be accepted.
The rationale is that we will be posting the solutions shortly after the assignment deadline, and we cannot accept submissions after the solutions are posted. 
This is not ideal, but I believe the overall policy is best for the class as a whole.

_In exceptional circumstances_ a late submission may be accepted with an academic concession - see [here](https://github.com/UBC-CS/cpsc330-2024W1/blob/main/syllabus.md#academic-concessions) for more info.

## Updates to assignments

If there are errors or other changes that need to be made to an assignment, I will announce them in a pinned Piazza post.

## Citing sources

If you use information from students outside your group or from online sources _including code snippets from Stack Overflow_ or lecture notes, cite this at the start of each question. **You will receive a mark of 0 for the assignment (and possibly other consequences) if you are found copying from other sources without citation**.

