### cs580-S2022-lab02-starter

### Title:

Exploring Peer-Reviewed Articles of the Literature

Designed for use with [GitHub Classroom](https://classroom.github.com/), this repository contains the starter files.

### Introduction

Research initiative progresses in function of the current ideas in the field of the work. This implies that one's research must constantly be checked, updated, and amended according to the fresh information which is available from colleagues and peers of the field. To determine direction and gather new facts and information for a research idea, an investigator must read the academic (i.e., peer-reviewed) articles of colleagues and peers who are also working on similar or related subject.


In this work, you will be following the ideas of others who are working on research projects which are related to your own research. This work will help you to focus your ideas more specifically so as to create a niche project which belongs uniquely to your project.

### What to do

You are to investigate and review three (3) peer-reviewed articles from the _literature_ using online search engines like [Google Scholar](https://scholar.google.com/) and similar. Your reviews will be published on your online research notebook.

#### Reviews Articles

One of the investigated articles will be a _survey_ or review paper in which the ideas of several different research projects have been introduced in conjunction an area of research. In other words, a survey article builds an argument that a particular task may be accomplished with the use of any of the introduced methods and /or resources.

 - An example of a survey paper may be found at the link: [Alignment-free genetic sequence comparisons: a review of recent approaches by word analysis](https://dl.acm.org/doi/10.1145/2506583.2512365) concerning various methodologies for comparing genetic material.

 - Another example of a peer-reviewed review article concerns Game Engine design and can be consulted at link [Augmented Reality and programming education: A systematic review](https://www.sciencedirect.com/science/article/pii/S2212868921000544?casa_token=3zvomjf3awsAAAAA:qFkxOc_PE5JF3YGMGQj8C5c8d7K-oWD620AbzxlWiLxzhj_1Xc0fHPvDMxeKLCnKZRBaK5248w)

The other two of the three papers will concern specific methods or research which is closely related to your own work.

### What to do

You will submit your work in this repository and on a post using your online research website.

Complete the markdown file: `writing/report.md` where you introduce your articles by responding to the leading questions. Once you have completed the work, please publish the questions and their responses on a posting or blog of your website. The please name the posting after the title of assignment.


### Learning

If you have not done so already, please read all of the relevant [GitHub Guides](https://guides.github.com/) that explain how to use many of the features that GitHub provides. In particular, please make sure that you have read the following GitHub guides: [Mastering Markdown](https://guides.github.com/features/mastering-markdown/), [Hello World](https://guides.github.com/activities/hello-world/), and [Documenting Your Projects on GitHub](https://guides.github.com/features/wikis/). Each of these guides will help you to understand how to use both [GitHub](http://github.com) and [GitHub Classroom](https://classroom.github.com/).

### Testing your assignment

This assignment uses [Docker](https://www.docker.com) and [GatorGrader tool](https://github.com/GatorEducator/gatorgrader) to check whether your assignment satisfies the minimum submission requirements. First, you need to make sure you have installed the [GatorGrader tool](https://github.com/GatorEducator/gatorgrader) to verify that the minimal content of your reflection document satisfies the Desktop](https://www.docker.com/products/docker-desktop) and have it running. Then, you can use you can use the [GatorGrader requirements specified in the lab assignment sheet. To run the GatorGrader application to start `gradle grade` as a containerized application, using the [DockaGator](https://github.com/GatorEducator/dockagator) Docker image available on [DockerHub](https://cloud.docker.com/u/gatoreducator/repository/docker/gatoreducator/dockagator). First, to ensure that the following command will work correctly, you must create the cache directory by running the command `mkdir $HOME/.dockagator`. Then, to see if your submission satisfies the minimal requirements, you can run the following command in the terminal:

```
docker run --rm --name dockagator \
  -v "$(pwd)":/project \
  -v "$HOME/.dockagator":/root/.local/share \
  gatoreducator/dockagator
```

This command will use `"$(pwd)"` (i.e., the current directory) as the project directory and `"$HOME/.dockagator"` as the cached GatorGrader directory. Please note that both of these directories must exist, although only the project directory must contain something. Generally, the project directory should contain the source code and technical writing of this assignment, as provided to a student through GitHub. Additionally, the cache directory should not contain anything other than directories and programs created by DockaGator, thus ensuring that they are not otherwise overwritten during the completion of the assignment.  If the above `docker run` command does not work correctly on the Windows operating system, you may need to instead run the following command to work around limitations in the terminal window:


```
docker run --rm --name dockagator -v "%cd%:/project" -v "%HomeDrive%%HomePath%/.dockagator:/root/.local/share" gatoreducator/dockagator
```

Please note; in the settings of Docker, your virtual drive must be shared for this command to work in Windows.
