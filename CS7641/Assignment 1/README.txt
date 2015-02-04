Knime Analytics Platform 2.11.1 with Weka 3.6 and Weka 3.7 plugins has been used for this assignment.

Results from all the experiments have been exported from Knime as CSV files and can be found in the experiments folder.

How to install Knime :
You can download and install knime from : http://www.knime.org/downloads/overview

How to install Weka plugins :
1) Install weka 3.7 plugin by clicking Files->Install Knime Extensions and select Weka 3.7 for installation.
2) To install Weka 3.6 plugin :
	a) go to Help-> Install new software
	b) paste the following url in the "Work with" text box : https://www.knime.org/update/2.10/
	c) Select Weka 3.6 from the list of extensions and install.
	
How to run the code/workflows :
All knime workflows for this assignment are in the file knime-export.zip.
Import this file into Knime by clicking on Files -> Import Knime Workflow.
After importing the zip file , you will see two folders showing up in your Knime workspace.
The folder named "Learning Curve" contains the workflows for the learning curves.
The folder named "Parameter Optimization" contains the workflows for optimizing the parameters.

You can run a workflow by opening it up by double clicking on it and then clicking the green play icon on the top bar.

You would have to adjust the file input and file output locations before running the workflows. The output file location is stored in a Variable node which is located on the extreme left-top of every workflow.
You can adjust the file input locations by double clicking on the CVS Reader/Arff reader and providing it the correct location. 