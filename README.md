# Investigating the relationship between Calculus and Linear Algebra with the Field of Machine Learning

## IB Personal Code: hst586

This is the github repository that contains the code for my HL Math IA for May 2022 with the title above.


## Instructions

To use the code in this repository you must have a few prerequisites installed. These instructions will install them, and then run the code.

1. Please install anaconda from [here](https://www.anaconda.com/products/individual)
2. Once anaconda is installed, open the anaconda prompt by following the instructions [here](https://docs.anaconda.com/anaconda/user-guide/getting-started/#open-anaconda-prompt).
3. Next go to the [pytorch website](https://pytorch.org/get-started/locally/), select the options that match your computer and copy the command that appears. 
   - For PyTorch Build, choose stable
   - Select the operating system you are using
   - Select conda as your package
   - Choose Python for language
   - Choose CPU for compute platform
   - Copy the command that appears
4. Paste the command into the anaconda prompt and hit "enter."
5. Now download this repository, there is a button that says "Code," after clicking it there should be an option for "Download Zip." 
6. Unzip the downloaded file.
7. Now copy the path to where you unzipped the file.
8. Navigate to this directory using the anaconda prompt, that was opeened in step 2.
   - This is done by typing "cd" followed by the path to the directory, and hitting "enter"
   - i.e
        > cd \<paste the path here\>
9. Now type "jupyter notebook" in the anaconda prompt.
10. This should open a webbrowser. In the webbrowser there should be a a list of files. Click on the file named "Numeral Classifier (Work).ipnyb"
11. This will open a new tab. In the new tab there will be a menu at the top with options such as "File, Edit, etc". Click on the option for "Cell" and then click "Run All".
12. Scroll to the bottom of the page and wait for the command to execute.
13. Once it is finished it should show the results of the neural network explaining how well it did.

*Note these instructions use the trained model that I developed, if you would like to train the model yourself (the code is included) do the following, This will take around 20-80 minutes to do*

## Instructions to train the network

1. Scroll to the 8th box from the top.
2. The first line in this box should say:
    > TRAIN = False
3. Change the "False" to "True", *note the T in True must be capitalized*
4. Now with this box highlighted, *(A blue line should appear at the side)* Click on the Cell button in the top menu, then click "Run All Below."

This will retrain the neural network with new weights and biases. The accuracy of this new network will be displayed at the bottom of the screen. Note that this process can take anywhere from 30 to over 80 minutes depending on the computer.


If you have any questions feel free to go the "Issues" tab of this webpage and open a new issue.