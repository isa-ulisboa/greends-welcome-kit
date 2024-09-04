# Master in Green Data Science - Welcome Kit
### Master in Data Science in Agriculture, Food, Forest and Environment
### Instituto Superior de Agronomia, Universidade de Lisboa


## Welcome

Welcome to **[Master in Green Data Science](https://www.isa.ulisboa.pt/ensino/mestrados/mcdaafa/lp/)**! The purpose of this welcome kit is to help you to set up your computer environment and get ready to start your master programme. We will use a set of common tools and resources across all mandatory courses, which includes:

1. [Python](#python)
2. [Jupyter Notebooks](#jupyter)
3. [VPN](#vpn)
4. [Google for Education account](#google)
5. [Google Collaboratory](#colab)
6. [Git](#git)
7. [Github](#github)
8. [Text editor](#editor)
9. [MariaDB](#mariadb)
10. [DBeaver](#dbeaver)
11. [Discord](#discord)
12. [Fenix](#fenix)

As a student of this course, you will have access to the Informatics Room 48 (Sala PORBIOTA, Main Building) at ISA where desktop computers will be prepared with all the necessary tools. However, you might want to setup your on computer (laptop or desktop) to work off or on class, if you prefer so. This will be necessary to complete homework exercises and assignments.

All of these resources are available for free for Linux, MacOS or Windows, so you can choose which developer environment you want to use. We will support all of them. We will also rely heavily on online services for collaboration and sharing, so you will have to set them up as well. Some resources may require on-campus connections, in which case you need to have a VPN connection.


### 1. <a name="python">Python</a>

We will use **python** as our primary programming language throughout the course. Python is on of the most used programming languages worldwide, and it is very popular within the Data Science community.

Python is an opensource and free software, which is most certainly available to be installed from the apps/package manager in your system. Or you can go to [Python.org](https://www.python.org/) to download installation packages of the latest stable 
release. Make sure that in the Windows inatallation, you check `Add Python to PATH` option.

It is also recommended to have a package manager for Python installed. These can by [PIP](https://pypi.org/project/pip/) or Conda. **pip** is normally installed  by default if python was downloaded from python.org. You can ensure that it is installed running the following command in your terminal:
```
python -m ensurepip --upgrade
```
For more details, check [pip installation](https://pip.pypa.io/en/stable/installation/).

### 2. <a name="jupyter">Jupyter Notebook or Jupyter Lab</a>

[**Jupyter Notebook**](https://jupyter.org/) and [**Jupyter Lab**](https://jupyter.org/) are both browser-based interactive computing platform to create notebook documents. Notebooks combine code, text and visualisation that you run interactively to perform your operations in a data science project. Jupyter is a opensource and free software that uses python, but can run notebooks with code implemented in python, R or other languages.

You can opt for Jupyter Notebook or Jupyter Lab, as you wish. Normally, installing Jupyter Lab also includes Notebook in its installation.

To [install Jupyter Notebook](https://jupyter.org/install), you need to have Python in your system. The recommended way of installation is using [PIP](https://pypi.org/project/pip/) (Python Package Index), which needs also to be installed.

To install Jupyter Notebook, run from a terminal:

```
pip install notebook
```

After the installation completed, you can start the application from a terminal by running:

```
jupyter notebook
```

If you opt to install Jupyter Lab, run from a terminal:

```
pip install jupyterlab
```

After the installation completed, you can start the application from a terminal by running:

```
jupyter lab
```

### 3. <a name="vpn">VPN</a>

Some resources might be available only when you are in an on-campus connection. In that case, if you are working remotely from home, you need to have an active VPN connection. ISA provides VPN connections to all its students. You can find more information on how to configure your connection [here](https://www.isa.ulisboa.pt/di/servicos/acesso-vpn). To activate your VPN access, you need to deliver a signed [term of responsability](https://www.isa.ulisboa.pt/files/di/pub/docs/formularios/TermoResponsabilidadeVPN.pdf) at ISA Informatics Support office (Main Building, room 28A).


### 4. <a name="google">Google for Education account</a>

As a student of the University of Lisbon, you have access to a [ULisboa User Account](https://www.ulisboa.pt/info/conta-utilizador-ulisboa), which will enable several services and resources, including a **Google for Education** account. We might use several application of this service in our classes, so it is recommended to activate the Google account before classes start. The services in this account include Gmail, Google Drive, Google Classroom, Google Calendar, Google Collaboratory, Google Jamboard, etc.

Activate your ULisboa account at https://utilizador.ulisboa.pt. This will also require that you activate your ISA student email in advance. In case you need support, contact the Informatics Support at ISA by helpdesk@isa.ulisboa.pt. 


### 5. <a name="colab">Google Collaboratory</a>

One of the Google for Education resources we will use is **Google Collaboratory**. This is an online *Jupyter Notebook* environment that enables running notebooks in a cloud environment. Google Colab provides computing resources (including GPU processors), allows sharing of notebooks and access to files stored in Google Drive, so it is a great environment for our data science projects.

You need to have your Google for Education account active to sign in in Colab.


### 6. <a name="git">Git</a>

**Git** is a *distributed version control* system that will help you to manage and share your code between computers, with colleagues and the data science community. We will use *git* in our projects to start from a template repository, develop our code, do hands on exercises, submit homework and assignments. When using *Google Colab*, you will also have the possibility to share your code using *git* and *Github*.

You can install **Git** in your computer, from the apps/package manager of your system, or downloading from [https://git-scm.com](https://git-scm.com). In the classroom we will learn how to configure *git* and the essential commands to start using it.


### 7. <a name="github">GitHub</a>

**Github** is a code repository that enables sharing code between developers. It supports *git* commands to grab or submit code, and manages versions. You will use *Github* in many tasks to manage your projects, get and submit code.

To use Github, you need to [create and account](https://github.com/signup), which is available for free.

The ISA repository is available at [https://github.com/isa-ulisboa](https://github.com/isa-ulisboa).


### 8. <a name="editor">Text editor</a>

One of the most used tools by you will be a text editor. It will be used to view and edit code, data files, documentation, etc. You can use any editor of your choice, depending on the operating system you have. Examples are: [Visual Studio Code](https://code.visualstudio.com/), [ Notepad++](https://notepad-plus-plus.org/), [Sublime Text](https://www.sublimetext.com/), [PyCharm](https://www.jetbrains.com/pycharm/), [Vim](https://www.vim.org/) (if you're using linux or MacOS, the last one is likely to be already available in your system). 


### 9. <a name="mariadb">MariaDB</a>

For our exercises in Data Management and Storage, we will use as DBMS the system MariaBD, which is free and opensource software, fully compatible with MySQL. The installation will depend on your Operating System (OS). To download the Community Server, link to [this page](https://mariadb.org/download/). For Windows or Linux OS, the link provides binaries for download. In the case of Linux, it is likely that you can install it with the package manager of your system. For MacOS, binaries can be installed using Homebrew (see more [here](https://mariadb.com/kb/en/installing-mariadb-on-macos-using-homebrew/)).

If your prefer to use MySQL, this is also possible.


### 10. <a name="dbeaver">DBeaver</a>

Interacting with the database can be done by many ways, but using an IDE (Integrated Development Environment) makes it more easy. We will use DBeaver, although you can use any other of your choice. DBearver Community is free and opensource software and can be downloaded [here](https://dbeaver.io/download/).


### 11. <a name="discord">Discord</a>

When working in teams, it is useful to use a tool to communicate with colleagues or the community, but within the context of specific channels. Discord is a tool useful to promote and follow discussions related to our projects, and keep them as an archive. We will use the Discord server GreenDS. Click [here](https://discord.gg/TaDQbsaNJK) to to join this Discord server.

### 12. <a name="fenix">Fenix</a>

The ISA's academics management tool that you already know. The link to our master degree page is https://fenix.isa.ulisboa.pt/degrees/mcdaafa.

### 13. <a name="fenix">Moodle</a>

For some course activities, we will use the e-learning platform Moodle at [https://elearning.ulisboa.pt/](https://elearning.ulisboa.pt/). You will be
asked by the teacher to autoregister to the respective course of the Green Data Science
Master. The list of courses can be found [here](https://elearning.ulisboa.pt/course/index.php?categoryid=2677). Use the [ULisboa User Account](https://www.ulisboa.pt/info/conta-utilizador-ulisboa) to login via the centralized authentication system.



## Support

If you have any issues with the installation of the software above, post your question on Discord -> GreenDS -> Software -> Issues channel. We can also support you directly during the student support hour (on Wednesdays, 14-15h, at the Herbarium building, with Rui Figueira (ruifigueira@isa.ulisboa.pt)).  