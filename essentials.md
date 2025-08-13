# WORKING GROUP ESSENTIALS

<br />
 
Welcome to our working group! 

If you are new to this project, we strongly encourage you to familiarize yourself with the basic content of this page. This will help you to jump right into the conversations we are having during our weekly meetings. Gaining familiarity with the history of this project will avoid confusions and waste of time (for you and the rest of the team).

Keep the following URLs handy as reference for all the work we have been producing under this project.

   * [Project's main website](https://eventdata.utdallas.edu/)  
   * [ConfliBERT GitHub](https://github.com/eventdata/ConfliBERT)  
   * [ConfliBERT HuggingFace](https://huggingface.co/eventdata-utd) 

<br />

## ConfliBERT BASIC DEVELOPMENTS

Please read the papers presenting the ConfliBERT family models in English, Spanish, and Arabic. 
Pay particular attention to the information sources and volume of corpus used for pre-training ConfliBERT in each language. You also want to identify the different versions of ConfliBERT (continual/from scratch, cased/uncased) available in each language. Also pay attention to the databases and specific tasks used in the downstream applications in each paper. 

* **ConfliBERT English**
   * Paper [Hu et al. (2022)](https://aclanthology.org/2022.naacl-main.400/)  


* **ConfliBERT Spanish**
   * Paper [Yang et al. (2023)](https://ieeexplore.ieee.org/document/10409883)  

* **ConfliBERT Arabic**
   * Paper [Alsarra et al. (2023)](https://aclanthology.org/2023.ranlp-1.11/)  

<br />

![alt text](https://github.com/eventdata/meetings/blob/main/Figures/stop.png "Title")

Seriously, please read the three papers listed above. Then you can keep going. 


## GOT A PAPER IDEA??

Awesome! We love new ideas and really like working with proactive collaborators. Before you get started with your own work, please take a look at our wotk in the [project's main website](https://eventdata.utdallas.edu/). 

Here you will see our work around the following topics:

* Extractive and Generative AI
* Active Learning
* Machine Translation
* Zero Shot
* Event data
* Applications on conflict research

So, before you get started, please get yourself familiar with the work that we have been doing. That will help you get quickly on top of your game.


<br />



## SPECIALIZED TOPICS

* Group other papers by topic TBD.



<br />

## MEETING ETIQUETTE

When participating in our meetings, please:
* Arrive on time
* Turn your camera on
* Keep your microphone off (unless you are speaking, of course)

If you want present your progress, please:
* Include your name in the [Fall 2025 schedule](2025_Fall.md)
* If relevant, include the URLs for the resources you want to discuss.
* Let's try to respect the order of cotributors listed in the agenda.
* Please be mindful of the time, so keep your contributions on point.

<br />

## DOCUMENT! DOCUMENT! DOCUMENT YOUR WORK!

We have a big collaborative team that often involves several members working on the same project. 
Also, we often use data, results, or outputs of some papers as inputs for new papers. 
So, it is super important for you to **document everything that you do**.

In this project, we abide by the [FAIR principles](https://www.go-fair.org/fair-principles/), which stands for:
* **F**indability
* **A**ccessibility
* **I**nteroperability
* **R**euse of digital assets

The overall objective is that all your data, scripts, and results should be easily accessible and replicable by anyone. 
Here, "*anyone*" means any member of our team, but also any external user who may not have any idea about the project or even advanced computer science skills. 
So, please make sure you structure your work flow, organize your data, write your scripts, and specific routines and commands in a way that anyone can follow your work.

Here are a few basic guidelines to keep in mind:

1. **Your data and scripts are not yours.**
   * Yes, you are the one doing all the work, but all the data and script should be tailored to a general public audience.
   * You certainly have your own working style and *speak* python or R as your native language. But not everyone is familiar with your style or has the same level of technical skills as you do. So, please make sure you document your work in a way that anyone can follow you.
   * The best practice for making your work FAIR is to intentionally start your work with a FAIR mindset since the begining. Avoid falling into the trap of "I will write this code very quickly, and then I will go back and edit for streamlining purposes". No, that is not an efficient use of time and it increases the chances of you not doing it.
2. **Document everything.**  
   * Documenting your work is your responsibility. Inadequate documentation leads to waste of time, duplicated efforts, or even data loss.
   * Organize your folders and subfolders in an intuitive and hierarchical way.
   * Please use headers and subheaders in your scripts to clearly structure and organize your work.
   * Make **excessive use of comments** to describe procedures and steps in your code. Ideally, you should document this for each single command.
   * This takes a concious documentation effort in structuring and conducting your work at every step. It will be hard at the beginning, but eventually it should flow naturally.
3. **Use snake_case convention**.
   * Try to use the `snake_case` for file nomenclature, variable names, and for developing your script.
   * Avoid at all costs the use of special characters for file or variable names (e.g. `:`, `*`, `#`, `!`, etc.).
4. **Use prefixes for sequential steps.** 
   * Try to use numeric prefixes in your folder and file names (e.g. `1_filename.txt`) to indicate steps or scripts that should be run in sequential order.
5. **Use sufixes for version control.** 
   * Always use numeric sufixes for version control (e.g. `1_filename_v1.txt`). In this way, the `v` sufix can help you track the evolution of your files.
   * You can also create an `old` folder to archive previous versions of your code to prevent clutering your working space without deleting old files.
6. **Always have a README file.**
   * Whether you are working locally, a folder in the AHP, or on GitHub, please write a README file. This should serve as your first guideline for your project.
   * Write as many README files as folders and subfolders in your project. 
7. **Ensure replicability.**
   * Make sure anyone can run your entire code to replicate all your results without your supervision. Your folders, scripts, and data should be self-explanatory. Avoid the "well, it runs in my computer" excuse.  
8. **Keep your work updated.**
   * Most likely, you will be working in a collaborative space (e.g. GitHub, Delta, Arizona HPC). If you are also conducting part of your work locally, please make sure that the shared folder contains the latest update of your work.
   * Make sure all those who need access to your data and scripts in the shared space have access to it. This does not mean that the space has to be public (yet), just make sure that all your team members can access the latest version of your files.
   * We tend to work at a very quick pace. So, make sure all your files are updated in the shared space.



