# Decision trees project

You can find the instructions of the project in the file [decision-trees.ipynb](decision-trees.ipynb).

To submit your solution, please modify the file [decision-trees.lp](asp/decision-trees.lp) of the directory [asp](asp) with your encoding.

Every time you push a new commit, your solution will be tested automatically. 
The timeout per instance is 180 seconds, and the actual command for the test is:
* `python asp/test.py -e asp/decision-trees.lp -t 180`

For help, type `python asp/test.py --help`.

After a few minutes you will be able to see the result of the test in the **Actions** tab:
* Click on the test/workflow run.
* Scroll to the section "grade/grade summary".
* Check the result in the table ("PASS" or "FAIL").

Then scroll down until around line 150.
For each instance, you will see if the test is a:
* "success" (correct answer),
* "failure" (wrong answer),
* "timeout" (no solution found before the time runs out), or
* "error" (clingo error).
