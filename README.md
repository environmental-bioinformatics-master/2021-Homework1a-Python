# Homework 1a : Python
As with the last homework, clone this repo to the HPC. By following the homework link a new repo should have been created for you with the form `2021-Environmental-Bioinformatics/homework1a-python-USERNAME`. This is your repository and it is how you will be submitting your homework to us. Follow the same download protocol as before. 

For this homework, you will work on writing two functions that deal with counting and finding kmers. You will rely on your knowledge of strings, data collections (e.g. dictionaries, sets, lists), and indexing. I have provided [pseudocode](https://en.wikipedia.org/wiki/Pseudocode) to help you think about structuring your answers. I have also provided test cases for you to use to test that your code works as expected. 

For this homework, I want you to **comment your code.** Add information such that you know what each line is doing. 

## A note on Google
This is a great exercise! It is one that I did while learning to code in `python`. That being said... we are not the only ones who think this is a great exercise. So, many of the solutions to this exact problem are directly Google-able. In line with our collaboration policy, it is fine (and encouraged) to Google things like "nested for loop in Python" or "raise exception in Python". However, please don't cheat yourself out of the exercise by Googling: "Count Kmers in Python". Again, this was designed to help you learn and you won't learn much by copying answers from the internet.

**Use your peers. Use your brain. Ask the instructors. Embrace the struggle. It is the best way to learn.**

## Getting ready to run the assignment
The first thing that you will need to do prior to attempting this assignment is activate the conda environment we created in class `python_lab`. 

```
conda activate python_lab
```

You should now be in your environment and see your prompt change. 

## Starting jupyter
You are now ready to get going. As a reminder you will want to: 

1) Start up a `tmux` session. You can create a new named session (`tmux new -s name`) or attach an existing session (`tmux a -t name`). 

2) Use srun to log on to a node
  
4) Once in the session start up your conda environment: `conda activate python_lab`

5) Make sure you are in the directory that contains the python homework assignment (i.e. has this `README.md` file). Now you are ready to start up Jupyter Notebook. On poseidon run: `jupyter notebook --no-browser` and wait for it to start and report a port number. Then, on your local machine run create the tunnel. 

## Submitting your homework

Now push all your work to GitHub.

You should commit your changes to `Homework1a-python.ipynb` and push them to GitHub. Finally, make a file called `estimatedtime.txt`; in this file please estimate how much time you spent on the homework.

