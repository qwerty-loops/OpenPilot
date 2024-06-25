Developed an Ai agent, that essentially is a codebase setup. Assume that a user wants to setup a codebase locally, 
all we require is the link of the required repo. With the link fed in, the LLm first checks if an environment exists and then whether there is a requriments file and if so,
installs all the necessary packages. Then it moves onto the readme file and executes the instructions provided in it.
Finally, after all the steps have been executed properly, it opens a code editor, runs the necessary file and outputs content.
This is aimed towards individuals who are not familiar with git/ individuals who don't want to expend time on cloning and running repos.
An additonal step which was introduced was to instill a RAG element where user can query what type of repo they would like to clone and the documents search would yield the most popular links from which we can select the one we liked most.
