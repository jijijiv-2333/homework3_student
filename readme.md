# Homework 3 Starter Code and Data
## **Instructions:**
Read through the following instructions carefully!
### Accessing Class Code and Instructions

1. Create a fork of the class repository in GitHub.

2. Clone this repository into the home directory of your own JupyterHub by running this command:
```git clone your_SSH_URL```

**Our JupyterHub server has trouble remembering the file permissions for our SSH keys. If you get a file permission error with your private ssh key, run the following line of code in your Terminal:**

```chmod 400 ~/.ssh/id_ed25519``` 
<br>

This will change your file permission to the proper permissions that SSH requires.

3. There should now be a "homework_3" directory in the home directory of your JupyterHub. In terminal, change directories into "homework_3". Next, click on the the "homework_3" icon on the filepath hierarchy in the left panel of JupyterHub. If you don't see it, make sure you're in the home folder by clicking the folder icon under the search bar. 

4. Double click the "HW3.ipynb" to open it in a new tab and begin working on the assignment. Read the instructions carefully, and make sure to write your answers in the specified cells. 

5. Make sure to use the answer variable names provided in the starter code. There are autograder tests embedded in the notebook that will check your work when you run the Autograder, and you can which tests you passed/failed after you submit.

6. Edit the **README** file and write your name and UW NetID. Add a paragraph on why the following plots elements (below) are necessary when designing figures (4-5 sentences). (5 points) 

7. As you continue to answer the homework questions and make edits to your code, make sure to regularly update your GitHub repository as well via git add, commit, and push. A good rule of thumb would be to run these git steps anytime you make an addition or change that you don't want to accidentally lose. Generally, you can push once a day to maintain good version control practices. <br>

Also, make sure that your git commands are running without errors before you refresh your GitHub and check your changes. If you are not seeing the updated changes you created in your local JupyterHub directory, check where your status is by this command: <br>
``` git status```

Then, you can see if you made an error with your git add, commit, or push commands.


### Yiyang Liu yiyang23@uw.edu
Write your paragraph on the importance of the required plot elements here.

The concise, descriptive title for each figure/subplot are helpful to reading the graph and know what is been ploted. Axis labels with units can help we know the scale of the graph. Appropriate axis limits could make the graph in a proprate scale so that the garph can be read fully and clearly. Appropriate tick resolution using legend when using different datasets, appropriate font size all would help reading the graph easily.