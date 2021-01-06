#  Data Science Resource Inventory :computer:

<u>*A  Data Science repository to facilitate studies.*</u>

**[WARNING]** *The links cited here were extracted from various sites and are for study use, I am sharing them so that as well as I can learn, I hope I have not infringed any copyright; and if your website, repository or any other link is here and the owner would not like it to be, please contact us so you can withdraw* **!THANKS FOR UNDERSTANDING!**

<u>*This part is for Young Padawans or Jedi in  Data Science*</u>

<br />

## [Index](#index)

- [TO-DO](#to-do)
- [Motivation](#motivation)
- [Introductory Area](#introductory-area)
- [What is Data Science](#what-is-data-science)
- [Mentors and Role Models](#mentors-and-role-models)
- [Themes](#themes)
  - [Mathematics](#mathematics)
  - [API PSI](#api-psi)
  - [Visualization](#visualization)
  - [Competitions](#competitions)
  - [Front End Development](#front-end-development)
  - [Back End Development](#back-end-development)
  - [Big Data](#big-data)
  - [Theory](#theory)
  - [Development Environment](#development-environment)
  - [Learning](#learning)
  - [Bussiness](#bussiness)
  - [Security](#security)
- [Learning Platforms](#learning-platforms)
  - [Open and Massive Online Course](#open-and-massive-online-course)
  - [Books](#books)
  - [Course Links](#course-links)
    - [Data Science Academy](#data-science-academy)
    - [Course](#course)
  - [Blogs](#blogs)
  - [YouTube](#youtube)
  - [Magazines](#magazines)
  - [Medium](#medium)
  - [Poadcast](#poadcast)
- [Searches](#searches)
  - [Datasets](#datasets)
  - [Tutorials](#tutorials)
    - [Binder](#binder)
    - [Jupyterlab on AWS](#jupyterlab-on-aws)
  - [Tools](#tools)
  - [Download](#download)
- [GitHub Projects](#gitHub-projects)
- [Good Separate Texts](#good-separate-texts)
- [Awesome Lists](#awesome-lists)
- [Notes](#notes)
- [Images](#images)

</br>

## TO-DO

repository updates:

- [ ] Open sites and verify that they are active and that they are part of the repository.
- [ ] Add [EN-US] or [PT-BR] to the links

[GO TO INDEX](#index)

<br />

## Motivation

This is a repository of shortcuts to start studying **Data Science**.

**An important addendum is that I intend to focus on the security area. So, in this repository I will have a part where I will leave some links and information sheets focused on Information Security.**

We start with a What is Data Science ?. Basic readings for you to understand more about what Data Science is and what I must study to be a professional desired by companies.

The next steps are separated into Courses (MOOCs), for learning; Data set for study; Blogs that bring together the hottest and most up-to-date topics in the area, computer links for general knowledge; Youtube links to the best courses mentioned by the community; tools for producing analysis; online magazines; links to books for study and to buy; sites that gather competitions to increase the skills of Data Scientist; Main tool tutorials; Some of the best lists and repositories for studying Data Science; search links.

The idea of the list is not to make me a Unicorn Data Scientist, but when I am a Data Scientist I have a In the hall of everything that encompasses the area, and can talk to the various professionals involved in the area so that manage to define the best projects and approaches to which I will work.

References have been gathered here that have appeared throughout the studies and from various researches to facilitate studies and understanding. It is not a step by step to become a Data Scientist, but it serves as a Guide for those seeking knowledge in the field, and a repository for easy access without having your browser full of disorganized favorites.

So it follows a structure where I will address about:

- Data Engineer
- Data Scientist
- Machine Learning Engineer

**Data Engineer**
Responsible for taking raw data from various sources and placing the data in a Data Lake, a database where other team members will access. Responsible for bringing, processing and making data available from different sources in one place for the team. In some places known as Big Data Developer, who would be a Data Engineer, someone who will make the data available, but who has knowledge in Big Data, that is, has knowledge of programs that will work with large data sets such as Apache Spark or Apache Hadoop. The function of the Data Lake is only to store the data, the treatment will be done at the time of reading the data. The idea of Data Lake is because a Data Warehouse has data processed and cleaned, it would take longer and consequently lose data / value. A Data Pipeline architecture supports batch and processing and real-time. When talking about a distributed system, we are not necessarily talking only about the Hadoop architecture.

**Data Scientist**
Responsible for taking the data provided by the Data Engineer and rationalizing that data. Take the data and create Machine Learning models to solve the problems. Create Prediction Models or Classification Algorithms to solve some things. You take the information that is likely to be inside a Data Lake, and the Data Scientist will streamline these things, streamline these models and try to find the best model possible to improve the results. It is the guy who will be trying to rationalize the data, think about the best solutions and try to solve the problems.

**Machine Learning Engineer**
He comes to put the model that Data Scientist created in Production. It basically takes the model that the Data Scientist and puts it in a scalable way.

[GO TO INDEX](#index)

<br />

## Introductory Area

**First**
Learn Python:

You don't need to know Python in PRO mode, for example, but to enter this world you need certain basic knowledge:

- Don't you know Python? I highly recommend Gustavo Guanabara from [Curso em Vídeo](https://www.cursoemvideo.com/course/curso-python-3/)
- All about Python [Real Python](https://realpython.com/)
- Tools link to learn: [developer script](https://github.com/kamranahmedse/developer-roadmap)

**Second**
Prepare the PC:

I suggest Anaconda Navigator for those who are starting their studies in this field. It is Open Source for the programming languages Python and R. And it has all the necessary tools.

- Python can be downloaded through the Anaconda distribution: [Download Anaconda](https://www.anaconda.com/download/)

- Now, you can also use an IDE. I particularly recommend [Visual Studio Code](https://code.visualstudio.com/)

**Third**
Libraries:

The following are some libraries dedicated to the study of Data Science. There are several libraries that can be used, facilitating data analysis. Some must-have libraries for learning:

- [**Numpy**](https://pypi.python.org/pypi/numpy) - Library for arrays and mathematical functions.
- [**Matplotlib**](https://matplotlib.org/downloads.html) - For plotting graphs and visualizing data.
- [**OpenCV**](https://opencv.org/releases.html) - For viewing and editing images via Python.
- [**Virtualenv**](https://virtualenv.pypa.io/en/stable/) - It is a tool to create isolated Python environments. The basic problem to be solved is one of the dependencies and versions and indirectly permissions.
- [**Pandas**](https://pandas.pydata.org/) - It is an Open Source library, licensed by BSD, that provides high-performance, easy-to-use data structures and data analysis tools for the Python programming language.
- [**CharmPy**](https://charmpy.readthedocs.io/en/latest/) - It is a high level parallel and distributed programming framework with a simple and powerful API, based on Python migrable objects and remote method invocation; built on top of an adaptable C / C ++ runtime system that provides speed, scalability and dynamic load balancing.
- [**Pip**](https://pypi.org/project/pip/) - It is a package management system used to install and manage software packages written in the Python programming language.
- [**SciPy**](https://www.scipy.org/) - It is an Open Source library in Python language that was made for mathematicians, scientists and engineers.
- [**Urllib**](https://docs.python.org/3/library/urllib.html) - It is a Python module for searching URLs.
- [**Beautiful Soup**](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - It is a Python package for analyzing HTML and XML documents.
- [**Papermill**](https://github.com/nteract/papermill) - A tool to parameterize, execute and analyze Jupyter Notebooks.
- [**Nteract**](https://github.com/nteract/nteract) - It is a dynamic tool to give flexibility when writing code, exploring data and creating text to share insights about the data.
- [**RISE**](https://damianavila.github.io/RISE/installation.html) - "Live" Reveal.js Jupyter / IPython slide show extension.
- [**Scikit-learn**](http://scikit-learn.org/stable/install.html) - Python library with all kinds of algorithms.

**Note:**
For those who want to deal with neural networks / Deep Learning, it is another trail. There are four major frameworks: TensorFlow, Keras, PyTorch and Theano. TensorFolw being the most known and used.

**Fourth**
TensorFlow:

First, get to know [Playground Tensorflow](http://playground.tensorflow.org/)

After reading this material, it's time for installation:

  - Install CUDA Toolkit, and check that the system variables are correct.
  - Install CUDA Toolkit drivers
  - Install cuDNN
  - Install TensorFlow, CPU or GPU version (preferably only one installation)

When installing, follow own step-by-step instructions  [TensorFlow](https://www.tensorflow.org/install/)

> **An addendum: as you can see, the focus is on NVIDIA. Regarding the AMD GPU, I am unaware.**

Installed? Tested it? Did it roll? Now you don't know where to start? Here are tips:

  - There are own tutorials on [TensorFlow](https://www.tensorflow.org/tutorials/)
  - A tutorial for base [MNIST](https://www.tensorflow.org/tutorials/layers)
  - A tutorial for base [CIFAR-10](https://www.tensorflow.org/tutorials/deep_cnn)

In the tutorials this is clear, but I reinforce: learn to use the TensorBoard, manager and viewer of the TensorFlow neural networks. Until you save the current network status to reload later, you can:

  - [TensorFlow Summaries and Tensorboard](https://www.tensorflow.org/guide/summaries_and_tensorboard)
  - [Swiss AI Lab IDSIA](http://ischlag.github.io/about/)

**Fifth:**
Some more things

- Your account [Kaggle](http://www.kaggle.com/) is mandatory.
- Short list of databases to use as a guide. It has on [Wikipedia](https://en.wikipedia.org/wiki/List_of_datasets_for_machine_learning_research)
- Historical and classic databases. It has in the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/)

**Valuable Tips **
Below are some tips for you to go on your way:

1. Know the trail made by Leonardo Ferreira who in 1 year and a half became a data scientist and is in the 30th position worldwide as a data scientist [Kaggle] (https://www.linkedin.com/pulse/data-science- from-zero-kaggle-kernel-master-leonardo-ferreira /).
2. Organize your studies and don't mix or try to absorb many of the teachings.
3. Have profiles on Linkedin, GitHub, Kaggle and Hacker Rank. Have a Twitter developer account for text mining.
4. Go deeper by drinking teaching from various sources! example: when studying Python, read e-books and several other materials from different sources because each course has a different didactic and if you "pack" in some ok subject, it is common: look for other didactics until you understand.
5. If you want and can, invest in paid courses and specializations.
6. Use and learn with concept maps

***

**Kind of obligatorily, understand:**

- Predictive modeling.
- Naive Bayes.
- Time Series Analysis and Visualization.
- Exploratory data analysis.
- Statistics.
- Univariate analysis.
- Bivariate analysis.
- Graphics for when and how to use.
- Qualitative and Quantitative Variables.
- Basic mathematical requirements ..
- Notions of analytical and numerical optimization.
- Discover tools for data extraction on the web.
- Basics of linear algebra, eigenvectors, eigenvalues, base changes, among others.
- Basic probability and statistics: conditional probability, basic formulas, most common distributions, basic metrics, regression, rˆ2, p-value, inference, among others.
- It is worth knowing the least about: Amazon AWS server and Amazon QuickSight and Microsoft Power BI.
- And also: version control, markdown, git, GitHub, R and RStudio.

Like anything you want to learn, you should get involved with it, and a tip is always do not try to understand everything at once, take it easy. Frequent communities. The Python community in Brazil is one of the strongest and most active I have ever seen.

And that's it: this is the Area's Introductory Package. You are now able to start experimenting with the area.

***

**Comments:**

- The above script is not the only and not necessarily the best way to learn; it reflects what I intend to acquire as knowledge and I have noted in meetings and lectures and conversations in my career in the area.

[GO TO INDEX](#index)

<br />

## What is Data Science

Below is a list of favorite sites that have a variety of topics related to computing in general:

- [How to create your Data Scientist portfolio and publicize your work](https://paulovasconcellos.com.br/como-criar-seu-portfolio-de-data-scientist-cc7e6b23b996) [PT-BR]
- [After all, what is Data Science](http://www.abgconsultoria.com.br/blog/afinal-o-que-e-data-science/) [PT-BR]
- [Becoming a data scientist - Resume via Metromap](http://nirvacana.com/thoughts/2013/07/08/becoming-a-data-scientist/) [EN-US]
- [What is Data Science](http://www.datascientists.net/what-is-data-science) [EN-US]
- [Theories behind Data Science](http://www.becomingadatascientist.com/2014/02/14/what-is-a-data-scientist/) [EN-US]
- [Data Science from Zero to Kaggle Kernels Master](https://medium.com/ensina-ai/ci%C3%AAncia-de-dados-do-zero-%C3%A0-kaggle-kernels-master- 7f735d7fceb2) [PT-BR]
- [12 common mistakes in Data Science that compromise decision making](https://cio.com.br/12-erros-comuns-em-ciencia-de-dados-que-comprometem-a-tomada-de -decision /) [PT-BR]
- [10 types of data professionals: from data engineers to big data DevOps and data analysts, which of these classifications would you fit in?](Https://medium.com/@luis.anderson.sp/10-tipos-of-data-professionals-of-data-engineers-to-big-data-devops-and-analysts-of-94259531270f? ref = datahackers) [PT-BR]
- [What is Machine Learning and how to learn without spending anything](https://paulovasconcellos.com.br/o-que-e-machine-learning-e-como-aprender-sem-gastar-nada-2e612f13102b) [ PT-BR]
- [TO START IN DATA SCIENCE](http://colaboradados.com.br/blogposts/para-inicando-em-data-science.html) [PT-BR]
- Through this text: [Jupyter is now a full-fledged IDE](https://towardsdatascience.com/jupyter-is-now-a-full-fledged-ide-c99218d33095). Learn and put into practice: [nbdev](https://github.com/fastai/nbdev) and [@ jupyterlab / debugger] (https://github.com/jupyterlab/debugger)

[GO TO INDEX](#index)

<br />

## Mentors and Role Models

It is always nice to add a short column for role models nearby that inspire you:

- [Paulo Vasconcellos - Brazilian Data Scientist](https://paulovasconcellos.com.br/) [PT-BR]
- [Déborah Mesquita](https://www.deborahmesquita.com/) [PT-BR]
- [Lucas Caton](https://www.lucascaton.com.br/) [PT-BR]
- [Greg Reda](http://www.gregreda.com/) [EN-US]
- [Kevin Davenport](http://kldavenport.com/) [EN-US]
- [Julia Evans](http://jvns.ca/) [EN-US]
- [Meta Analysis](http://www.metabrown.com/blog/) [EN-US] 
- [Sentdex](http://sentdex.com/)
- [Deepkapha](http://tarrysingh.com/) [EN-US]
- [The File Drawer](http://chris-said.io/) [EN-US]
- [Hilary Parker](https://hilaryparker.com/) [EN-US]
- [Kenny Bastani](http://www.kennybastani.com/) [EN-US]
- [Adventures in Data Land](http://blog.smola.org) [EN-US]
- [Shane Lynn](https://www.shanelynn.ie/) [EN-US]
- [John Myles White](http://www.johnmyleswhite.com/) [EN-US]
- [Daniel Forsyth](http://www.danielforsyth.me/) [EN-US]
- [Learning Lover](http://learninglover.com/blog/) [EN-US]
- [Data-Mania](http://www.data-mania.com/blog/) [EN-US]
- [Noah Weber](https://www.kaggle.com/zikazika/notebooks)
- [ClaoudML](https://www.claoudml.com/)
- [Shane Lynn](https://www.shanelynn.ie/)

[GO TO INDEX](#index)

<br />

## Themes

Study Links.

<br />

### Mathematics

Computer Science study projects:

- [Mathematics](https://arxiv.org/archive/math) [EN-US] - E-prints from Cornell University related to Mathematics.
- [Quantitative Finance](https://arxiv.org/archive/q-fin) [EN-US] - E-prints from Cornell University related to Quantitative Finance.
- [Statistics](https://arxiv.org/archive/stat) [EN-US] - E-prints from Cornell University related to Statistics.
- [Econometrics](https://www.dicionariofinanceiro.com/econometria/) [PT-BR] - Econometrics is a study that uses mathematical and statistical methods to evaluate theories on economics and finance.
- [Math and Science Done Right](https://brilliant.org/) [EN-US] - Studies in Mathematics, Science and Engineering through small interactive learning experiences.

[GO TO INDEX](#index)

<br />

### API PSI

The *Protocols and Structures for Inference* (PSI) project aims to develop an architecture for presenting machine learning algorithms:

- [Research- protocols and structures for inference a res tful api for machine learning - James Montgomery](https://pt.slideshare.net/papisdotio/research-protocols-and-structures-for-inference-a-res-tful-api-for-machine-learning-james-montgomery) [EN-US] - Build Machine Leaning API structure.
- [Protocols and Structures for Inference Project](https://github.com/psi-project) [EN-US] - GitHub Project.
- [Evolutionary Database Design](https://www.martinfowler.com/articles/evodb.html#everything_refactoring) [EN-US] - Databases structure.
- [PSI RESTful API](http://psi.cecs.anu.edu.au/spec/rest.html)

[GO TO INDEX](#index)

<br />

### Visualization

Below is a list of Tools, Environments and Libraries for Data Scientists:

- [Scikit-Learn](http://scikit-learn.org/stable/) - Machine learning in Python.
- [NumPy](http://www.numpy.org/) - It is fundamental for scientific computing with Python. It supports large, multidimensional arrays and arrays and includes a variety of high-level math functions to operate on these arrays.
- [SciPy](https://www.scipy.org/) SciPy works with NumPy arrays and provides efficient routines for numerical integration and optimization.
- [Tensor Flow](https://www.tensorflow.org/) - TensorFlow is an open source software library for machine intelligence.
- [nbviewer](https://nbviewer.jupyter.org/) - Render Jupyter Notebooks as static web pages.
- [Matplotlib](https://matplotlib.org/) - 2D plotting library in Python that produces quality publication numbers in a variety of printed formats and interactive environments across platforms.
- [seaborn](https://seaborn.pydata.org/) - Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphs.
- [Auto PY to EXE](https://pypi.org/project/auto-py-to-exe/) - Convert .py to .exe using a simple graphical interface.
- [plot.ly](https://plot.ly/) - Data visualization library for Python.
- [Caffe](http://caffe.berkeleyvision.org/) - Deep learning structure made with expression, speed and modularity in mind.
- [Albumentations](https://github.com/albu/albumentations) - A fast and agnostic image augmentation library framework that implements a diverse set of augmentation techniques.
- [Ember Charts](http://opensource.addepar.com/ember-charts/#/overview) - A powerful and easy to use graphics library for Ember.js.
- [amCharts](https://www.amcharts.com/) - Libraries and tools for all your Data Visualization needs.
- [AnyChart](http://www.anychart.com/) - It's a set of flexible HTML5 JavaScript libraries for all your data visualization needs.
- [cartodb](http://cartodb.github.io/odyssey.js/) - Mapping tool.
- [Cube](http://square.github.io/cube/) - System to collect timestamp events and derive metrics.
- [d3plus](http://d3plus.org/) - Data visualization made easy.
- [D3js - Data-Driven Documents ](https://d3js.org/) - JavaScript library for manipulating documents based on data.
- [dygraphs](http://dygraphs.com/) - Flexible and fast open source JavaScript graphics creation library.
- [exhibit](http://www.simile-widgets.org/exhibit/) - Allows you to easily create web pages with advanced text search and filtering features, with interactive maps, timelines and other visualizations.
- [Gatherplot](http://www.gatherplot.org/) - Generalized scatter plots for nominal data.
- [ggplot2](http://ggplot2.org/) - System for declaratively creating graphics, based on The Grammar of Graphics.
- [Glue](http://www.glueviz.org/en/latest/) - Python library for exploring relationships within and between related data sets.
- [Google Chart Gallery](https://developers.google.com/chart/interactive/docs/gallery) - Provides a variety of charts designed to meet your data visualization needs.
- [jqplot](http://www.jqplot.com/) - Plot and graphics plugin for the jQuery JavaScript framework.
- [nvd3](http://nvd3.org/) - Build reusable graphics and graphics components.
- [Opendata-tools](http://opendata-tools.org/en/visualization/) - List of tools to explore, publish and share public data sets.
- [Openrefine](http://openrefine.org/) - A powerful and free tool for working with confusing data.
- [raw](http://rawgraphs.io) - The missing link between spreadsheets and data visualization.
- [techanjs](http://techanjs.org/) - A visual and technical analysis and graphics library based on D3. Create interactive financial charts for modern and mobile browsers.
- [Timeline](http://timeline.knightlab.com/) - Open source tool that allows anyone to build interactive and visually rich timelines.
- [variancecharts](http://variancecharts.com/index.html) - Allows engineers, designers, journalists, scientists and analysts to create elegant and personalized data graphics for the Web, using only HTML and CSS.
- [life](https://vida.io/) - Visualization of open source data.
- [Wrangler](http://vis.stanford.edu/wrangler/) - Interactive tool for cleaning and transforming data.
- [r2d3](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) - It is an experiment in expressing statistical thinking with interactive design.
- [NetworkX](https://networkx.github.io/) - Python package for creating, manipulating and studying the structure, dynamics and functions of complex networks.
- [Redash](https://redash.io/) - Built to allow quick and easy access to billions of records.
- [C3](https://c3js.org/) - D3-based reusable graphics library.
- [Heroku](www.heroku.com/) - It is a platform as a service (PaaS) that allows developers to create, run and operate applications entirely in the cloud.
- [OpenStack](https://www.openstack.org/) - It is open source software, capable of managing the components of multiple virtualized infrastructures.
- [DigitalOcean](https://www.digitalocean.com/) - Provides developers and companies with a reliable and easy-to-use cloud computing platform for virtual servers (Droplets), object storage (Spaces) and more.
- [Google Cloud Platform](https://cloud.google.com/) - It is a cloud computing suite offered by Google, operating on the same infrastructure that the company uses for its products aimed at users, including Google Search and YouTube.
- [Amazon Web Services Cloud](https://aws.amazon.com/en/) - It is a platform for cloud computing services, which form a cloud computing platform offered by Amazon.
- [nbextensions](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) - This repository contains a collection of extensions that add functionality to the Jupyter notebook.
- [tqdm](https://pypi.org/project/tqdm/) - Instantly make your loops show an intelligent progress meter.
- [hchart](http://jkunst.com/highcharter/hchart.html) - This generic function can graph various R objects in real time.
- [pyswarms](https://github.com/ljvmiranda921/pyswarms) - A research toolkit for optimizing particle swarms in Python.
- [MoviePy](https://zulko.github.io/moviepy/) - Python module for video editing, video composition, video processing or to create advanced effects.
- [requests-toolbelt](https://pypi.org/project/requests-toolbelt/)
- [nltk](https://github.com/nltk/nltk)
- [stanza](https://github.com/stanfordnlp/stanza)
- [Nbviewer](https://nbviewer.jupyter.org/)
- [Auto PY to EXE](https://pypi.org/project/auto-py-to-exe/)
- [SciPy](https://www.scipy.org/index.html)
- [chartjs](https://github.com/dendory/chartjs)

[GO TO INDEX](#index)

<br />

### Competitions

Below is a list of sites to put the knowledge of Data Analysis into practice:

- [Exercise List for Python](https://wiki.python.org.br/ListaDeExercicios) [PT-BR] - This is a list with suggestions for programs for beginners in programming.
- [URI Online Judge](https://www.urionlinejudge.com.br/judge/pt/login) [EN-US] - The main objective is to promote the practice of programming and knowledge sharing.
- [Kaggle](https://www.kaggle.com/) [EN-US] - Kaggle is the place to do Data Science projects.
- [DrivenData](https://www.drivendata.org/) [EN-US] - Data Science competitions to save the world.
- [Analytics Vidhya](http://datahack.analyticsvidhya.com/) [EN-US] - The last battleground for Data Scientists.
- [The Data Science Game](http://www.datasciencegame.com/) [EN-US] - An international student challenge.
- [InnoCentive](https://www.innocentive.com/) [EN-US] - Global pioneer in crowdsourcing innovation.
- [TuneedIT](http://tunedit.org/challenges) [EN-US] - Challenges of Machine Learning Algorithms and Data Mining.

[GO TO INDEX](#index)

<br />

### Front End Development

Machine learning studies addressing Front-End:

- [TEXT](LINK)
- [TEXT](LINK)

[GO TO INDEX](#index)

<br />

### Back End Development

Machine learning studies addressing Back-End:

- [TEXT](LINK)
- [TEXT](LINK)

[GO TO INDEX](#index)

<br />

### Big Data

Machine learning studies addressing Big Data:

- [TEXT](LINK)
- [TEXT](LINK)

[GO TO INDEX](#index)

<br />

### Theory

Machine learning studies addressing Theory:

- [TEXT](LINK)
- [TEXT](LINK)

[GO TO INDEX](#index)

<br />

### Development Environment

Data Science Desktop:

- [TEXT](LINK)
- [TEXT](LINK)

[GO TO INDEX](#index)

<br />

### Learning

Study related links to learn first:

- [TEXT](LINK)
- [TEXT](LINK)

[GO TO INDEX](#index)

<br />

### Business

Data Science for business study:

- [TEXT](LINK)
- [TEXT](LINK)

[GO TO INDEX](#index)

<br />

### Security

Data Science Security study:

- [Awesome Machine Learning for Cyber Security](https://github.com/jivoi/awesome-ml-for-cybersecurity)
- [data_hacking](https://github.com/SuperCowPowers/data_hacking)
- [Machine Learning for Cybersecurity 101](https://towardsdatascience.com/machine-learning-for-cybersecurity-101-7822b802790b)

[GO TO INDEX](#index)

<br />

## Learning Platforms

Study Links.

<br />

### Open and Massive Online Course

Below is a list of sites that offer a variety of free and paid courses:

- [edX](https://www.edx.org) [EN-US] - Flexible programming learning.
- [Coursera](https://www.coursera.org) [EN-US] - Learn skills from the best universities for free.
- [Udacity](https://br.udacity.com/) [EN-US] - Courses and Certifications.
- [Edraak](https://www.edraak.org/en/) [EN-US] - Edraak, is a massive open online course platform (MOOC), which is an initiative of the Queen Rania Foundation (QRF).
- [Open HPI](https://www.openhpi.de) [EN-US] - MOOC´S for Reading and Learning.
- [MIT OPEN COURSEWARE](https://www.ocw.mit.edu) [EN-US] - It is a web-based publication of virtually all MIT course content, open and available to the world.
- [cK-12](https://www.ck12.org) [EN-US] - 100% free and personalized learning for each student.
- [Udemy](https://www.udemy.com) [EN-US] - The largest selection of courses in the world.
- [SKILLSHARE](https://www.skillshare.com) [EN-US] - Skillshare is an online learning community with thousands of classes in design, business, technology and more.
- [Codecademy](https://www.codecademy.com) [EN-US] - Learn the technical skills you need for the job you want.
- [P2PU](https://www.p2pu.org) [EN-US] - connects educational resources open to career paths in an equitable and empowering way.
- [Saylor Academy](https://www.saylor.org) [EN-US] - Saylor Academy is a non-profit initiative working since 2008 to offer free and open online courses for everyone who wants to learn.
- [Academic Earth](https://www.academicearth.org) [EN-US] - Find free online courses, lectures and videos from top colleges like Yale, MIT and Stanford.
- [Learn To Be](https://www.learntobe.org) [EN-US] - Non-profit organization that brings 1-on-1, online tutoring for young people.
- [Floqq](https://www.floqq.com) - FLOQQ is the largest Spanish-language video search engine course.
- [Course Talk](https://www.coursetalk.org) [CA-ES] - Discover the best courses on the web based on your interests and student feedback.
- [Marginal Revolution University](https://www.mruniversity.com) [EN-US] - Creates free and engaging economic videos taught by top professors.
- [Alison](https://www.alison.com) [EN-US] - Free online courses with certificates.
- [Data Science Academy](https://www.datascienceacademy.com.br/) [PT-BR] - Community of experts in Data Science.
- [SOLYD](https://solyd.com.br/) [PT-BR] - Online training and courses.
- [DataCamp](https://www.datacamp.com/) [EN-US] - Learn Data Science online.
- [Google for Education](https://developers.google.com/edu/python/) [EN-US] - Google's Python class.
- [VEDUCA](https://veduca.org/) [PT-BR] - Here you study for free
  and you can earn your certificate for a price that fits in your pocket.
- [Fundação Bradesco](https://www.ev.org.br/) [PT-BR] - Escola Virtual is an educational portal that offers free courses, free of charge, in the distance mode.
- [Khan Academy](https://www.khanacademy.org/) [EN-US] - Offers hands-on exercises, instructional videos and a personalized learning panel that enables students to study at their own pace inside and outside the classroom of class.
- [EADCCNA](http://eadccna.com.br/index.html) [PT-BR] - Variety of online courses in IT.
- [Teaching Channel](http://canaldoensino.com.br/blog/) [PT-BR] - Free courses and books in the public domain.
- [4Linux](https://www.4linux.com.br/) [PT-BR] - Linux and open software courses.
- [Impacta](https://www.impacta.com.br/) [PT-BR] - IT, Management and Design Courses.
- [Microsoft Academy](https://academy.microsoft.com/en-us/professional-program/tracks/artificial-intelligence/) [EN-US] - Microsoft Professional Program for Artificial Intelligence.
- [Microsoft Virtual Academy](https://mva.microsoft.com/) [EN-US] - Free Microsoft training provided by experts.
- [Universia](http://noticias.universia.com.br/destaque/especial/2013/07/10/1035282/8/700-cursos-online-gratis-das-melhores-universidades-do-mundo/cursos -online-gratis-de-ci% C3% Computer-science% C3% A7% C3% A3o-e-intelig% C3% AIncia-artificial.html) [EN-BR] - Universia Brasil brought together 700 online courses free from the best universities in Brazil and the world. Check out courses in Computer Science and Artificial Intelligence.
- [Duolingo](https://www.duolingo.com/) [EN-US] - Learn languages for free, forever.
- [e-stude](http://e-stude.com/site/) [EN-US] - E-learning platform aimed at training software development teams.
- [Google Developers](https://developers.google.com/machine-learning/crash-course/) [EN-US] - The Machine Learning Learning Course.
- [Acclaim](https://www.youracclaim.com/skills/data-science/related_badges) [EN-US] - Complete a series of online Data Science courses.
- [Data School](https://www.dataschool.io/) [EN-US] - Data Science Courses.
- [Dataquest](https://www.dataquest.io) [EN-BR] - Learn Python, R, SQL, data visualization, data analysis and machine learning.

[GO TO INDEX](#index)

<br />

### Books

Below is a list of paid and free books:

- [Artificial Intelligence: A Machine Learning Approach](https://www.amazon.com.br/gp/product/8521618808/ref=as_li_tl?ie=UTF8&tag=mineradores-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=8521618808&linkId=7454c1981bbb0ba214951a2da88fc029) [PT-BR]
- [Data Science from Zero. First Rules with Python](https://www.amazon.com.br/gp/product/857608998X/ref=as_li_tl?ie=UTF8&tag=mineradores-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=857608998X&linkId=ca962763fa0115715ca78099451bbfde) [PT-BR]
- [Python For Data Analysis](https://www.amazon.com.br/gp/product/8575226479/ref=as_li_tl?ie=UTF8&tag=mineradores-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=8575226479&linkId=46bee8242a50) PT-BR]
- [Introduction to Data Mining. Basic Concepts, Algorithms and Applications](https://www.amazon.com.br/gp/product/8547200983/ref=as_li_tl?ie=UTF8&tag=mineradores-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=8547200983&linkId=d12ad14d791724c8293c6dd2f19d8afd) [PT-BR]
- [Introduction to Data Mining With Applications in R](https://www.amazon.com.br/gp/product/853528446X/ref=as_li_tl?ie=UTF8&tag=mineradores-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=853528446X&linkId=58d0ec345411ec471d23c642b12121fc) [PT-BR]
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) [EN-US]
- [The Data Science Handbook](http://www.thedatasciencehandbook.com/) [EN-US]
- [The Art of Data Usability](https://www.manning.com/books/the-art-of-data-usability) [EN-US]
- [Think Like a Data Scientist](https://www.manning.com/books/think-like-a-data-scientist) [EN-US]
- [R in Action, Second Edition](https://www.manning.com/books/r-in-action-second-edition) [EN-US]
- [Introducing Data Science](https://www.manning.com/books/introducing-data-science) [EN-US]
- [Practical Data Science with R](https://www.manning.com/books/practical-data-science-with-r) [EN-US]
- [Exploring Data Science](https://www.manning.com/books/exploring-data-science) [EN-US]
- [Exploring the Data Jungle](https://www.manning.com/books/exploring-the-data-jungle) [EN-US]
- [Python® for R Users: A Data Science Approach](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119126805) [EN-US]
- [Classic Computer Science Problems in Python](https://www.manning.com/books/classic-computer-science-problems-in-python) [EN-US]
- [R for Data Science](http://r4ds.had.co.nz/index.html) [EN-US]
- [An Introduction to Statistical Learning - with Applications in R](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf) [EN-US]
- [Pattern Recognition and Machine Learning (Information Science and Statistics)](https://www.amazon.com/Pattern-Recognition-Learning-Information-Statistics/dp/0387310738) [EN-US]
- [R for Data Science](https://r4ds.had.co.nz/index.html) [EN-US]
- [Syncfusion - Ebooks](https://www.syncfusion.com/ebooks) [EN-US]
- [Free Programming Books](https://github.com/EbookFoundation/free-programming-books) [EN-US]
- [Free Software Testing Books](https://github.com/ligurio/awesome-software-quality) [EN-US]
- [Go Books](https://github.com/dariubs/GoBooks) [EN-US]
- [R Books](https://github.com/RomanTsegelskyi/rbooks) [EN-US]
- [Mind Expanding Books](https://github.com/hackerkid/Mind-Expanding-Books) [EN-US]
- [Book Authoring](https://github.com/TalAter/awesome-book-authoring) [EN-US]
- [Elixir Books](https://github.com/sger/ElixirBooks) [EN-US]

[GO TO INDEX](#index)

<br />

### Course Links

Courses related to computing:

<br />

#### Data Science Academy

Courses related to computing:

- [Free Microsoft Power BI Course (Workload: 54 Hours)](https://www.datascienceacademy.com.br/course?courseid=microsoft-power-bi-para-data-science)
- [Free Big Data Fundamentals Course (Hours: 8 Hours)](https://www.datascienceacademy.com.br/course?courseid=big-data-fundamentos)
- [Free Python Fundamentals Course for Data Analysis (Hours: 54 Hours)](https://www.datascienceacademy.com.br/course?courseid=python-fundamentos)
- [Free Course on Introduction to Data Science (Hours: 8 Hours)](https://www.datascienceacademy.com.br/course?courseid=introduo--cincia-de-dados)
- [Free Course on Fundamentals of Artificial Intelligence (Hours: 8 Hours)](https://www.datascienceacademy.com.br/course?courseid=inteligencia-artificial-fundamentos)

[GO TO INDEX](#index)

<br />

#### Course

Courses related to computing:

- [Python Fundamentals for Data Analysis](http://www.datascienceacademy.com.br/pages/curso-python-fundamentos-para-analise-de-dados)
- [Data Analysis and Interpretation Specialization (Wesleyan University)](https://www.coursera.org/specializations/data-analysis)
- [Data Management and Visualization](https://pt.coursera.org/learn/data-visualization)
- [Data Analysis Tools](https://pt.coursera.org/learn/data-analysis-tools)
- [Regression Modeling in Practice](https://pt.coursera.org/learn/regression-modeling-practice)
- [Machine Learning for Data Analysis](https://pt.coursera.org/learn/machine-learning-data-analysis)
- [Data Analysis and Interpretation Capstone](https://pt.coursera.org/learn/data-analysis-capstone)
- [Introduction to Computer Science and Programming Using Python (MIT)](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-9)
- [Using Python for Research (Harvard)](https://www.edx.org/course/using-python-research-harvardx-ph526x)
- [Intro to Python for Data Science](https://www.datacamp.com/courses/intro-to-python-for-data-science)
- [Deep Learning Prerequisites: The Numpy Stack in Python](https://www.udemy.com/deep-learning-prerequisites-the-numpy-stack-in-python/)
- [Making Graphs in Python using Matplotlib for Beginners:](https://www.udemy.com/making-graphs-in-python-using-matplotlib-for-beginners/)
- [Google's Python Class](https://developers.google.com/edu/python/)

[GO TO INDEX](#index)

<br />

### Blogs

Below is a list of data science issues:

- [Blog Mining Data](http://minerandodados.com.br/) [PT-BR] - This project aims to help you learn more about Data Science and related areas in a practical and quick way.
- [The Statistician](https://oestatistico.com.br/) [PT-BR] - Blog with the mission is to promote statistics in a simple, fun and affordable way, like you've never seen before.
- [Pizza de Dados](http://pizzadedados.com/) [PT-BR] - The Brazilian podcast on Data Science.
- [Post-Graduate](http://posgraduando.com/blog/) [PT-BR] - Content and daily humor for graduate students.
- [Hackernoon](https://hackernoon.com/) [EN-US] - Hacker Noon is everything that hackers need at noon.
- [Towards Data Science](https://towardsdatascience.com/) [EN-US] - Towards Data Science, Sharing concepts, ideas and codes.
- [Data Science Central](https://www.datasciencecentral.com/) [EN-US] - Industry online resource for data professionals.
- [Mining the Social Web](https://miningthesocialweb.com/) [EN-US] - A complement to the book with the simple objective of integrating the mainstream social mining of the web.
- [Becoming a Data Scientist](http://www.becomingadatascientist.com/) [EN-US] - Documenting the path of SQL Data Analyst seeking a Master of Engineering for Data Scientist.
- [AllThings Data Science](https://allthingsds.wordpress.com/) [EN-US] - All things about Data Science.
- [MDM - A Geeks Point Of View](http://www.mdmgeek.com/) [EN-US] - Technology blog on master data management and every buzz around it.
- [The Open Source Data Science Masters](http://datasciencemasters.org/) [EN-US] - The open source curriculum for learning Data Science.
- [Data Science London](http://datasciencelondon.org/) [EN-US] - Data Science London is a non-profit organization dedicated to the free and open dissemination of Data Science.
- [Open Source Research](https://openresearch.wordpress.com/) [EN-US] - PhD student in the field of Operations Research at Berkeley.
- [Louis Dorard](http://www.louisdorard.com/blog/) [EN-US] - A tech guy with a penchant for the web and data, big and small.
- [Machine Learning Mastery](http://machinelearningmastery.com/) [EN-US] - About helping professional programmers to confidently apply machine learning algorithms to solve complex problems.
- [Data Science Weekly](https://www.datascienceweekly.org/) [EN-US] - A free weekly newsletter with curated news, articles and works related to Data Science.
- [Revolution Analytics](http://blog.revolutionanalytics.com/) [EN-US] - Daily news on the use of open source R for big data analysis, predictive modeling, data science and visualization.
- [R Bloggers](https://www.r-bloggers.com/) [EN-US] - R-Bloggers.com is an aggregator of content blogs contributed by bloggers who write about R.
- [Datascope Analytics](https://datascopeanalytics.com/blog/) [EN-US] - Data-driven consulting and design.
- [Yet Another Data Blog](http://yet-another-data-blog.blogspot.com.tr/) [EN-US] - Reflections on Collective Intelligence, Data Disputes, Data Science, Predictive Modeling, Start -ups and a repository of ideas.
- [KDNuggets](http://www.kdnuggets.com/) [EN-US] - Leader in Business Analysis, Big Data, Data Mining, Data Science and Machine Learning.
- [Data Scientist](http://www.datascientists.net/) [EN-US] - Developed for data scientists to collaborate in sharing knowledge and experiences.
- [What´s The Big Data](https://whatsthebigdata.com/) [EN-US] - Explores its impact on information technology, the business world, government agencies and our lives.
- [Decisions & Discovery](http://www.micfarris.com/) [EN-US] - Focusing on science, data science, business, technology,
- [New Data Scientist](http://newdatascientist.blogspot.com/) [EN-US] - How a social scientist jumps into the world of big data.
- [Data Science 101](http://101.datascience.community/) [EN-US] - Learning to be a Data Scientist.
- [Data Scientist Journey](https://datascientistjourney.wordpress.com/category/data-science/) [EN-US] - Digital nomad couple talking about Data Science.
- [Dataists](http://www.dataists.com/) [EN-US] - More than seeing your model there are no heteroscedastic errors.
- [Data-Magnum](https://data-magnum.com/blog/) [EN-US] - Provides the information, education and assessment necessary for the planning and successful implementation of Big Data projects .
- [The MapR Blog](https://www.mapr.com/blog) [EN-US] - Find insights, best practices and useful resources to help you leverage data more effectively in growing your business.
- [P-value](http://www.p-value.info/) [EN-US] - Reflections on data science, machine learning and statistics.
- [DATA MINERS BLOG](http://blog.data-miners.com/) [EN-US] - A place to read about topics of interest to data miners, ask questions to data mining experts at data miners .
- [FlowingData](http://flowingdata.com/) [EN-US] - Visualization and Statistics.
- [O'reilly Learning Blog](https://www.oreilly.com/learning) [EN-US] - Perspectives on learning tools, technologies and methods.
- [Dominodatalab](https://blog.dominodatalab.com/) [EN-US] - Includes the post on Data Science.
- [i am trask](http://iamtrask.github.io/) [EN-US] - Crafts for Machine Learning.
- [Vademecum of Practical Data Science](https://datasciencevademecum.wordpress.com/) [EN-US] - It aims to share some of the problems, solutions and alternative solutions and best practices of the authors who helped them on their journey of Dice.
- [Dataconomy](http://dataconomy.com/) [EN-US] - On the new emerging data economy.
- [Vidhya Analytics](https://www.analyticsvidhya.com/blog/) [EN-US] - A complete website on data science and analysis study material.
- [Colah's Blog](http://colah.github.io) [EN-US] - To understand neural networks.
- [Sebastian's Blog](http://ruder.io/) [EN-US] - To understand NLP and transfer of learning.
- [DATAVERSITY](http://www.dataversity.net/) [EN-US] - Data Education for Business and IT Professionals.
- [Science and Data](http://www.cienciaedados.com/) [PT-BR] - The objective is to talk about the fascinating adventure of Data Science.
- [Institute of Applied Artificial Intelligence](https://www.datah.com.br/) [PT-BR] - It is a non-profit organization where young students receive free education on artificial intelligence, develop projects.
- [BiaData Bussiness](http://www.bigdatabusiness.com.br/) [PT-BR] - Information about Big Data.
- [Portal Action](http://www.portalaction.com.br/) [PT-BR] - The largest statistical portal in Brazil.
- [HackerRank](https://www.hackerrank.com/) [EN-US] - It is a technology hiring platform that is the standard for assessing the skills of developers for more than 1,000 companies worldwide.
- [SQL Magazine Magazine](https://www.devmedia.com.br/revista-sql-magazine) [PT-BR] - Content about SQL.
- [DATAQUEST](https://www.dataquest.io/blog/) [EN-US] - Data science, data analysis and tutorials and data engineering articles.
- [Data Elixir](https://dataelixir.com/) [EN-US] - It is a curator of the best news, resources and inspirations from Data Science.
- [Simply Statistics](https://simplystatistics.org/) [EN-US] - News and texts on statistics.
- [ClaoudML](http://www.claoudml.co/) [EN-US] - Free data science and machine learning resources.
- [PyData](https://pydata.org/) [EN-US] - Forum for the international community of users and developers of data analysis tools to share ideas and learn from each other.
- [freeCodeCamp](https://medium.freecodecamp.org/) [EN-US] - Learn new developer skills.
- [Vooo](https://www.vooo.pro/insights/category/data-science/) [EN-US] - News and texts on Data Science.
- [Bitfactor](https://bitfactor.fi/en/blog/) [EN-US] - Thoughts about design, technology and other very important things.
- [The Fashion Robot](https://thefashionrobot.com/) [EN-US] - About inspiring technologies in the fashion industry.
- [OpenMined](https://openmined.org/) [EN-US] - An open source community focused on researching, developing and elevating tools for secure artificial intelligence.
- [Shivam Bansal's](http://www.shivambansal.com/) [EN-US] - Data Scientist and Kaggle Kernels Grandmaster.
- [7WDATA](https://www.7wdata.be/) [EN-US] - It's the Hotspot about new news of all things.
- [mathbabe](https://mathbabe.org//) [EN-US] - Exploring and venting on quantitative issues.
- [Hipsters Ponto Tech](https://hipsters.tech/primeiros-passos-em-data-science-do-excel-e-bi-ao-python-hipsters-134/) [PT-BR] - Podcast where the Caelum and Alura people enter into heated discussions about programming, design, ux, gadgets, startups and the latest technology.
- [Artificial Neural Networks](https://sites.icmc.usp.br/andre/research/neural/)
- [Statistical Handouts](http://www.portalaction.com.br/ambiente-virtual-de-aprendizado)
- [Simply Statistics](https://simplystatistics.org/)
- [Machine Learning Mastery](https://machinelearningmastery.com/blog/)
- [Acclaim Data Science](https://www.youracclaim.com/skills/data-science/related_badges)
- [Dataversity](https://www.dataversity.net/)
- [Khan Academy](https://pt.khanacademy.org/)
- [HackerRank](https://www.hackerrank.com/)
- [KDnuggets](https://www.kdnuggets.com/news/index.html)

[GO TO INDEX](#index)

<br />

### YouTube

Below is a list of YouTube Channels, Videos I liked and Playlist to study and keep up to date:

- Channel [Google Open Online Education](https://www.youtube.com/channel/UC6fUahKiPDn1-3476TU-ovA) [EN-US] - Online courses offered by Google and tools that allow you to create your own courses .
- Channel [Pycursos](https://www.youtube.com/user/PyCursos) [PT-BR] - Python specialists in the most diverse areas, from Web Development to Data Science and Big Data.
- Channel [Sentdex](https://www.youtube.com/user/sentdex) [EN-US] - Python programming tutorials, going beyond the basics, learn about machine learning, finance, data analysis, robotics , web development, game development and more.
- Channel [Professor Mateus Mota](https://www.youtube.com/channel/UC_VRFh8fm4whcLehJkCmcbg) [PT-BR] - - Tutorials on Python and Data Science.
- Channel [Chanel SANDECO](https://www.youtube.com/channel/UCIQne9yW4TvCCNYQLszfXCQ/featured) [EN-BR] - Develop Data Science, Machine Learning applications, using large masses of data contained in Big Data stores.
- Channel [Deep Learning Brazil](https://www.youtube.com/channel/UCWg0CObS-JnEtjW69eGh89A) [PT-BR] - Its objective is to promote the dissemination of the theme in Brazil.
- Channel [Siraj Raval](https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A/featured) [EN-US] - Learn to develop and build Artificial Intelligence, Games, music, chatbots, art, using Python.
- Channel [Data School](https://www.youtube.com/channel/UCnVzApLJE2ljPZSeQylSEyg) [EN-US] - Learning Data Science to get your first job as a Data Scientist.
- Channel [Professor Fernando Amaral](https://www.youtube.com/channel/UC6w56wRjrbbZk-cX46SuxPA) [PT-BR] - Channel with Machine Learning, Big Data, NoSQL and related subjects content.
- Playlist [USP Channel](https://www.youtube.com/playlist?list=PLAudUnJeNg4tvUFZ8tXQDoAkFAASQzOHm) [PT-BR] - Aulas USP | Artificial Intelligence in health: the use of Machine Learning.
- Playlist [Zurubabel](https://www.youtube.com/watch?v=plJw9QFew5A&list=PL4OAe-tL47sbzCgtBTthtX50T30CLToEZ) [EN-BR] - Programming Course R.
- Playlist [Hugo Larochelle](https://www.youtube.com/playlist?list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH) [EN-US] - Class of Neural Networks University of Sherbrooke.
- Playlist [Tomer Ben David](https://www.youtube.com/watch?v=cHzvYxBN9Ls&list=PLPqVjP3T4RIRsjaW07zoGzH-Z4dBACpxY) [EN-US] - Data Science Primer.
- Playlist [mrshmt](https://www.youtube.com/playlist?list=PLCA2C1469EA777F9A) [EN-US] - Learning from the Data.
- Playlist [Logo Code - Programming and Artificial Intelligence](https://www.youtube.com/watch?v=hQGeRCBTKGs) [EN-US] - Python Natural Language Processing - Intro to spaCy.
- Playlist [sentdex](https://www.youtube.com/watch?v=7uhMemi2mFc&index=4&list=PLQVvvaa0QuDcg7v9OIyT-DWXX4WOjmJ9I) [EN-US] - Introduction and Basics - Python Reddit API Wrapper (PRAW) tutorial.
- Playlist [Google Developers](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal) [EN-US] - Machine Learning Recipes with Josh Gordon.
- Video [What is machine learning?](Https://www.youtube.com/watch?v=WXHM_i-fgGo) [EN-US] - AI's goals are to create a machine that mimics the human mind and, for this, she needs learning resources.
- Video [Andrew Ng: Deep Learning, Self-Taught Learning and Unsupervised Feature Learning] (https://www.youtube.com/watch?v=n1ViNeWhC24) [EN-US] - Self-Learning and Resource Learning Unsupervised.
- Video [Deep Learning: Intelligence from Big Data](https://www.youtube.com/watch?v=czLI3oLDe8M) [EN-US] - A machine learning approach inspired by the brain.
- Video [Introduction to Deep Learning with Python](https://www.youtube.com/watch?v=S75EdAcXHKk) [EN-US] - Talks about deep learning.
- Video [What is machine learning, and how does it work?](Https://www.youtube.com/watch?v=elojMnjn4kk) [EN-US] - Definition, provide some examples of machine learning and explain in high level of how machine learning works.
- Video [Neural Nets for Newbies by Melanie Warrick (May 2015)](https://www.youtube.com/watch?v=Cu6A96TUy_o) [EN-US] - This talk is aimed at anyone who is passionate about understanding algorithms and codes to define and leverage standards in data.
- Video [What comes after NoSQL? NewSQL: a new era of challenges in scalable data processing](https://www.youtube.com/watch?v=uBCTtfUq2XQ) [EN-BR] - This talk is about NewSQL.
- Video [Deep Learning: Intelligence from Big Data from Big Data](https://www.youtube.com/watch?v=czLI3oLDe8M) - A machine learning approach inspired by the brain.

[GO TO INDEX](#index)

<br />

### Magazines

Below is a list of favorite sites to stay informed:

- [The Future of Things](https://ofuturodascoisas.com/) [EN-BR] - The future visible to all, Artificial Intelligence, Robotics, innovations and new medical technologies.
- [Chupadados](https://chupadados.codingrights.org/) [EN-BR] - This project brings together Latin American stories about the massive collection and processing of data by governments, companies and ourselves to monitor cities, homes, pockets and bodies.
- [PCWorld](http://pcworld.com.br/) - Technology consultant, with analysis and product guide, tests, reviews, tips and download.
- [GSTI Portal](https://www.portalgsti.com.br/) - Content, area to answer questions, information on job vacancies, competitions and certifications.
- [The Next Web](https://thenextweb.com/) - Original and proudly opinionated perspectives on notable stories for Generation T.
- [Intel IT Center](https://www.intel.la/content/www/xl/es/it-management/intel-it/it-managers.html) - Resources for IT Leaders.
- [indy100: discover](https://www.indy100.com/discover) - Various news about everything.
- [Skynet Today](https://www.skynettoday.com/) [EN-US] - Accessible and informed coverage of the latest AI and Panic hype.
- [Hacker News Bulletin](http://www.hackersnewsbulletin.com/) [EN-US] - Discover the latest trends, interesting news and useful tips on hackers, hackers, cybersecurity, technology and anonymous worldwide.
- [Datatau](http://www.datatau.com/news) [EN-US] - Like Hacker News, but for data.
- [Fossbytes](https://fossbytes.com/) [EN-US] - Leading source of technology news, focusing on Linux distro releases, security and hacker news, tutorials, tips and tricks, VPNs and more more.
- [ICML](http://icml.cc/2015/) [EN-US] - International Conference on Machine Learning
- [EPJ Data Science](http://epjdatascience.springeropen.com/) [EN-US] - Publishing platform to address this evolution, bringing together all academic disciplines related to science.
- [Journal of Data Science](http://www.jds-online.com/) [EN-US] - An international magazine dedicated to the application of statistical methods in general.
- [Big Data Research](https://www.journals.elsevier.com/big-data-research) [EN-US] - It aims to promote and communicate advances in big data research, providing a quick and high quality for researchers, practitioners and policy makers from many different communities working on this topic.
- [Journal of Big Data](http://journalofbigdata.springeropen.com/) [EN-US] - Publishes high quality academic papers, methodologies and case studies covering a wide range of topics, from big data analysis to data-intensive computing and all big data research applications.
- [Big Data & Society](http://journals.sagepub.com/home/bds) [EN-US] - It is a peer-reviewed academic journal that publishes interdisciplinary works mainly in the social sciences, humanities and computing and their intersections with the arts and natural sciences about the implications of big data for societies.
- [Data Science Journal](https://www.jstage.jst.go.jp/browse/dsj) [EN-US] - Allows you to easily search, browse and cite the latest articles published by academic societies on Japan and you can access documents using the reference reference or the cited link.
- [Coding Coach](https://codingcoach.io/)
- [Vooo Data Science](https://www.vooo.pro/insights/category/data-science/)
- [Bitbay](https://bitbaysolucoes.com.br/blog/pages/about.html)
- [Quanta Magazine](https://www.quantamagazine.org/)
- [Playing Numbers](https://www.playingnumbers.com/)
- [Towards Data Science](https://towardsdatascience.com/)

[GO TO INDEX](#index)

<br />

### Medium

Magazine related links:

- [Hackernoon](https://hackernoon.com/) - Hacker Noon Rips Out Medium’s Software, Replaces it With Their Own.
- [The Startup](https://medium.com/swlh) - Medium's largest active publication, followed by +598K people. Follow to join our community.
- [Concretebr](https://medium.com/concretebr) - We develop digital products with innovation, agility and excellent practices, for the Brazilian and Latin American market.
- [freecodecamp](https://www.freecodecamp.org/news/) - Learn to code with free online courses, programming projects, and interview preparation for developer jobs.
- [geeksforgeeks](https://www.geeksforgeeks.org/) - A Computer Science portal for geeks.
- [Machine Learning for Everyone](https://vas3k.com/blog/machine_learning/?ref=datahackers)
- [Becoming Human](https://becominghuman.ai/)

[GO TO INDEX](#index)

<br />

### Poadcast

Below are lists with more content that increase the capacity to study:

- [Pizza de Dados](https://pizzadedados.com/)
- [Hipsters.Tech](https://hipsters.tech/category/podcast/)
- [Data Hackers](https://datahackers.com.br/podcast)

[GO TO INDEX](#index)

<br />

## Searches

Download Related Links.

<br />

### Datasets

Below is a list of sites that have a variety of datasets for study and learning:

- [DATAQUEST](http://www.dataquest.io/blog/free-datasets-for-projects/) [EN-US] - 18 places to find data sets for data science projects.
- [Quora's Big Datasets Answer](https://www.quora.com/Where-can-I-find-large-datasets-open-to-the-public) [EN-US] - Links to sites to find great data sets open to the public.
- [ISPDados](http://www.ispdados.rj.gov.br/) [PT-BR] - Open Data Page of the Public Security Institute. You will be able to access the databases of criminal records and police activity in the state of Rio de Janeiro.
- [BRAZILIAN OPEN DATA PORTAL](http://dados.gov.br/dataset) [PT-BR] - More than 6 thousand data sets.
- [Google Trends](https://trends.google.com.br/trends/?geo=BR) [EN-US] - See what the world is searching for.
- [Sorocaba Open Data](https://nave.wordpress.com/dados-abertos-sorocaba/) [PT-BR] - This portal makes publicly available data that is generated by municipal departments and agencies.
- [Sorocaba Transparency Portal](http://leideacesso.etransparencia.com.br/sorocaba.prefeitura.sp/Portal/desktop.html?410) [PT-BR] - Publication of data in open format.
- [Open Data of Capes](https://dadosabertos.capes.gov.br/) [PT-BR] - Here you will find data and information about Brazilian postgraduate courses, about the training of teachers for basic education and others themes related to education.
- [GEOCAPES](https://geocapes.capes.gov.br/geocapes/) [PT-BR] - Capes Georeferenced Information System.
- [Academic Torrents](http://academictorrents.com/) [EN-US] - We are a distributed repository maintained by the community for datasets and scientific knowledge.
- [Hadoop Illuminated](http://hadoopilluminated.com/hadoop_illuminated/Public_Bigdata_Sets.html) [EN-US] - Publicly Available Big Data Sets.
- [United States Census Bureau](http://www.census.gov/) [EN-US] - Economic indicators from the USA Census Bureau.
- [US Government Data Sources](http://usgovxml.com/) [EN-US] - US government web services and XML data sources.
- [Enigma] http://enigma.com/) [EN-US] - Browse the world of public data - Quickly search and analyze billions of public records published by governments, companies and organizations.
- [Datahub](https://datahub.io/) [EN-US] - Provides important and commonly used data as high quality, easy to use and open data packages.
- [Amazon - Open Data on AWS](https://aws.amazon.com/datasets/) [EN-US] - Open data search datasets.
- [re3data](https://www.re3data.org/) [EN-US] - Data sharing made easy.
- [DataCite](https://www.datacite.org) [EN-US] - Center for research data.
- [Quandl](https://www.quandl.com/)[ EN-US] - The main source of financial, economic and alternative data sets, serving investment professionals.
- [figshare](https://figshare.com/) [EN-US] - Get more citations for all your academic research results over 5000 citations of sharing content.
- [MAXMIND](http://dev.maxmind.com/geoip/legacy/geolite/) [EN-US] - GeoLite databases and legacies.
- [Kaggle Datasets](https://www.kaggle.com/datasets) [EN-US] - Dataset for use in Kaggle.
- [IGSR: The international genome sample resource](http://www.internationalgenome.org/data) [EN-US] - Providing ongoing support for the 1000 Genomas Project data.
- [World Bank Open Data](http://data.worldbank.org/) [EN-US] - Free and open access to global development data.
- [Open Data Philly](https://www.opendataphilly.org/) [EN-US] - It is a catalog of open data in the Philadelphia region.
- [Grouplens](https://grouplens.org/datasets/) [EN-US] - Sample of movie data sets (with ratings), book and wiki.
- [UC Irvine Machine Learning Repository](http://archive.ics.uci.edu/ml/) [EN-US] - Currently maintains 446 data sets as a service for the machine learning community.
- [NOAA - National Center for Environmental Information](https://www.ncdc.noaa.gov/) [EN-US] - They are responsible for preserving, monitoring, evaluating and providing public access to the nation's treasury of data and information and historical information about the climate.
- [MapLight](http://maplight.org/data) [EN-US] - MapLight tracks several sets of data that you can look for evidence of the influence of money on politics.
- [GHDx](http://ghdx.healthdata.org/) [EN-US] - A catalog of health and demographic data sets from around the world and including results from the HMI.
- [UNICEF Data](https://data.unicef.org/) [EN-US] - UNICEF data on statistics and monitoring.
- [UN Data](http://data.un.org/) [EN-US] - UN data on statistics and monitoring.
- [The GDELT Project](http://gdeltproject.org/) [EN-US] - GDELT project monitors worldwide broadcast, print and web news from almost every corner of every country.
- [San Fransisco Government Open Data](https://data.sfgov.org/) [EN-US] - Search hundreds of data sets for the city and San Francisco County.
- [Global Open Data Index](http://index.okfn.org/) [EN-US] - The Global Open Data Index provides the most comprehensive snapshot available of the state of publishing open government data.
- [GHTorrent](http://ghtorrent.org/) [EN-US] - A scalable, consultable and offline data mirror offered by the Github REST API.
- [Microsoft Research Open Data](https://msropendata.com/) [EN-US] - A collection of free Microsoft Research data sets to promote cutting-edge research in areas such as natural language processing, computer vision and science domain-specific.
- [Open Government Data Platform India](https://data.gov.in/) [EN-US] - It is a platform to support the Open Data initiative of the Government of India.
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.html) [EN-US] - Machine Learning Center and Intelligent Systems.
- [Google Dataset Search](https://toolbox.google.com/datasetsearch) [EN-US] - Google Data Sets.
- [Brazil Datasets](https://brasil.io/datasets) [EN-US] - Brazilian Data Set.
- [Kaggle Datasets](https://www.kaggle.com/datasets) [EN-US] - Kaggle Dataset.

[GO TO INDEX](#index)

<br />

### Tutorials

Data Science Tutorials:

- [Artificial Neural Networks](http://conteudo.icmc.usp.br/pessoas/andre/research/neural/) [PT-BR] - You will see on this page an introductory tutorial on Artificial Neural Networks, especially on the Multi Layer Perceptron networks trained with BackPropagation.
- [Data Science using Python and R](https://github.com/jadianes/data-science-your-way) [EN-US] - Ways to do Data Engineering and Machine Learning in R and Python

[GO TO INDEX](#index)

<br />

#### Binder

Project My Binder:

- [Binder Examples](https://github.com/binder-examples) [EN-US]
- [Amazon Elastic Container Service](https://aws.amazon.com/en/ecs/) [EN-US]
- [Docker basics for Amazon ECS](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/docker-basics.html) [EN-US]
- [AWS and dockerized applications](https://imasters.com.br/aws/aws-e-as-aplicacoes-dockerizados) [PT-BR]
- [Binder - - Transform a GitHub repository into a collection of interactive notebooks](https://mybinder.org/) [EN-US]
- [Using Binder](https://mybinder.readthedocs.io/en/latest/using.html#preparing-a-repository-for-binder) [EN-US]
- [Introducing Binder 2.0 - Share your interactive research environment](https://elifesciences.org/labs/8653a61d/introducing-binder-2-0-share-your-interactive-research-environment) [EN-US]
- Video [Running Containers Dockers on AWS](https://www.youtube.com/watch?v=m_ElzW6F44I) [PT-BR]
- Video [Jupyter, Jupyter Lab and Binder - Overview and associated technologies](https://www.youtube.com/watch?v=zVaMHGlSyh4) [PT-BR]

[GO TO INDEX](#index)

<br />

#### Jupyterlab on AWS

Jupyterlab Tutorials:

- [How to configure JupyterLab on AWS](https://bitfactor.fi/en/blog/2018/08/30/how-to-set-up-jupyterlab-in-aws/) [EN-US]
- Video [Google Compute Engine and Jupyter Notebook Setup: Part - 1](https://www.youtube.com/watch?v=zzMCKv1g5z0) [EN-US]
- Video [Google Compute Engine and Jupyter Notebook Setup: Part - 2](https://www.youtube.com/watch?v=gMDQZPoMECE) [EN-US]
- [JUPYTER - jupyter / docker-stacks](https://github.com/jupyter/docker-stacks) [EN-US] - Docker images ready to run containing Jupyter applications.
- [DOCKERHUB - jupyter / datascience-notebook](https://hub.docker.com/r/jupyter/datascience-notebook/) [EN-US] - Jupyter Notebook Data Science Stack.

[GO TO INDEX](#index)

<br />

### Tools

Below is a list of tools that make the job easier:

- [Jupyter](http://jupyter.org/) - Project Jupyter exists to develop open source software, open standards and services for interactive computing in dozens of programming languages.
- [neptune.ml](https://neptune.ml) - Community-compatible platform that supports data scientists in creating and sharing machine learning models. Neptune facilitates teamwork, infrastructure management, model comparison and reproducibility.
- [Steppy 1](https://github.com/neptune-ml/steppy) - Lightweight, Python library for experimenting with fast and reproducible machine learning. It features a very simple interface that allows for a clean machine learning pipeline project.
- [Steppy-toolkit 2](https://github.com/neptune-ml/steppy-toolkit) - Cured collection of neural networks, transformers and models that make your machine learning faster and more effective.
- [Cloud Datalab Google](https://cloud.google.com/datalab/docs/) - Easily explore, visualize, analyze and transform data using familiar languages, such as Python and SQL, interactively.
- [Hortonworks Sandbox](http://hortonworks.com/products/sandbox/) - It's a personal, portable Hadoop environment that comes with a dozen interactive Hadoop tutorials.
- [R](http://www.r-project.org/) - It is a free software environment for statistical computing and graphics.
- [RStudio](https://www.rstudio.com) - Powerful IDE for R, free and open source, works on Windows, Mac and Linux.
- [Weka](https://www.cs.waikato.ac.nz/ml/weka/downloading.html) - Application with graphical interface for reading data, pre-processing and machine learning algorithms.
- [Anaconda Cloud](https://anaconda.org/) - Anaconda Cloud is where data scientists share their work. You can search and download popular Python and R packages and notebooks to start your data science work.
- [Data Science Toolbox](http://datasciencetoolbox.org/) - It is a virtual environment based on Ubuntu Linux that is specifically suited for doing data science.
- [Datadog](https://www.datadoghq.com/) Solutions, code and devops for high-scale data science.
- [Kite Development Kit](http://kitesdk.org/docs/current/index.html) - It's a high-level data layer for Hadoop. It is an API and a set of tools that accelerate development. You configure how Kite stores your data on Hadoop, instead of creating and maintaining that infrastructure on your own.
- [Domino Data Labs](http://www.dominodatalab.com) - Run, scale, share and deploy your models without any infrastructure or configuration.
- [Apache Flink](http://flink.apache.org/) A platform for efficient, distributed and general purpose data processing.
- [Apache Hama](http://hama.apache.org/) - It is a high-level open source project from Apache, allowing you to do advanced analysis beyond MapReduce.
- [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - It is a collection of machine learning algorithms for data mining tasks.
- [Octave](https://www.gnu.org/software/octave/) - It is a high-level interpreted language, intended mainly for Free Matlab numerical calculations.
- [Apache Spark](https://spark.apache.org/) - Extremely fast cluster computing.
- [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - a service to expose Apache Spark analytics jobs and machine learning models as real-time, batch or reactive web services.
- [Torch](http://torch.ch/) - It is a scientific computing framework with extensive support for machine learning algorithms that puts GPUs first.
- [Neon - Nervana's Python based Deep Learning Framework](https://github.com/NervanaSystems/neon) - It is Intel's reference deep learning framework, committed to the best performance on all hardware. Designed for ease of use and extensibility.
- [Skale](https://github.com/skale-me/skale-engine) - High Performance Distributed Data Processing in NodeJS.
- [Aerosolve](http://airbnb.io/aerosolve/) - A machine learning package designed for humans.
- [Datawrapper 1](https://www.datawrapper.de/) - An open source data visualization platform that helps everyone to create simple, correct and embeddable graphics.
- [Datawrapper 2](https://github.com/datawrapper/datawrapper) - It's also on GitHub.
- [Natural Language Toolkit](http://www.nltk.org/) - It is a leading platform for creating Python programs to work with human language data.
- [nlp-toolkit for node.js](https://www.npmjs.com/package/nlp-toolkit) - This module covers some basic principles and implementations of nlp.
- [Julia](http://julialang.org) - High-level, high-performance dynamic programming language for technical computing.
- [IJulia](https://github.com/JuliaLang/IJulia.jl) - A Julia language backend combined with the Jupyter interactive environment.
- [Apache Zeppelin](http://zeppelin.apache.org/) - eb-based notebook that allows data usage, interactive data analysis and collaborative documents with SQL, Scala and more.
- [Featuretools](https://github.com/featuretools/featuretools/) - An open source framework for automated resource engineering written in Python.
- [Optimus](https://github.com/ironmussa/Optimus) - Cleaning, pre-processing, resource engineering, exploratory data analysis and easy ML with PySpark back-end.
- [DVC](https://github.com/iterative/dvc) - An open source data science version control system. It helps to track, organize and make data science projects reproducible.
- [Markdown](https://www.markdownguide.org/) - Markdown Guide is a free, open source reference guide that explains how to use Markdown, the simple and easy to use markup language that you can use to format almost any document.
- [Git](https://git-scm.com/) - It's a free, open source distributed version control system designed to handle everything from small to very large projects, with speed and efficiency.
- [Bitbucket](https://bitbucket.org/) - It's more than just Git code management. Bitbucket gives teams a place to plan projects, collaborate on code, test and deploy.
- [GitHub](https://github.com/) - Development platform inspired by the way you work. From open source to business, you can host and analyze code, manage projects and build software.
- [GitBook](https://legacy.gitbook.com/) - Documentation made easy. Helps your team to write, collaborate and publish content online.
- [Pivotal Tracker](https://www.pivotaltracker.com/) - It is the agile project management tool of choice for developers worldwide for real-time collaboration around a prioritized and shared backlog.
- [Stack Overflow](https://stackoverflow.com/) - It is the largest and most trusted online community for developers to learn, share their knowledge and build their careers.
- [NotABug](https://notabug.org/) - Open source code collaboration platform for freely licensed projects.
- [Kite](https://kite.com/) - It is a cloud-based co-pilot that increases your programming environment.
- [reddit](https://www.reddit.com/) - Offers the best of the internet in one place. Get a constant update of news, fun stories, photos, memes and videos just for you.
- [Online Box Plot Generator](http://www.alcula.com/calculators/statistics/box-plot/) - Box Plot Statistics Calculator.
- [Grafana](https://grafana.com/) - Data visualization and monitoring with support for Graphite, InfluxDB, Prometheus, Elasticsearch and many other databases.
- [Graph Viz](https://gephi.org/) - Leading platform for visualization and exploration for all types of graphics and networks. Gephi is open source and free.
- [Tableau](https://www.tableau.com/pt-br) - Visualization of interactive data focused on Business Intelligence.
- [Collaboratory](https://colab.research.google.com/notebooks/welcome.ipynb) - It's a free Jupyter notebook environment that requires no configuration and runs entirely in the cloud.
- [Vega](http://vega.github.io/) - Vega is a declarative format for creating, saving and sharing visualization projects. With Vega, visualizations are described in JSON and generate interactive visualizations using HTML5 Canvas or SVG.
- [Vega - VOYAGER](https://vega.github.io/voyager2/) - It is a visualization browser for exploring open data. It provides a gallery of recommended views, produced by the Compass view recommendation engine.
- [Python Anywhere](https://www.pythonanywhere.com/) - Host, run and code Python in the cloud.
- [Neo4j](https://neo4j.com/) - It is a graphical database management system.
- [Docker](https://www.docker.com/) - It is a software technology that provides containers, providing an additional layer of abstraction and automation of operating system level virtualization in Windows and Linux.
- [Binder](https://mybinder.org/) - It is a Git repository that has been equipped with the appropriate compilation files so that its content can be connected to a BinderHub instance. These repositories currently live mainly on GitHub, although we plan to support more online repositories, such as GitLab or BitBucket.
- [IPython](https://ipython.org/) - Interactive interpreter for several programming languages, but especially focused on Python.
- [Overleaf](https://en.overleaf.com/) - LaTeX, Evolved. The easy-to-use, online and collaborative LaTeX editor.
- [RED HAT - OpenShift](https://www.openshift.com/) - Deployment and management of container-based software. It is a supported distribution of Kubernetes using Docker and DevOps tools for accelerated application development.
- [InfluxData](https://www.influxdata.com/time-series-platform/telegraf/)
- [Apache PredictionIO](https://predictionio.incubator.apache.org/) - Machine learning as a service.
- [Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb)
- [Jupyter](https://jupyter.org/)
- [Anaconda](https://anaconda.org/account/login?next=%2Fthecomitre%2Fdashboard)
- [edgedb](https://edgedb.com/)

[GO TO INDEX](#index)

<br />

### Download

Below is a list of downloads:

- [LibGen](www.libgen.pw) ou [Library Genesis](http://libgen.rs/) - It's a search engine for scientific articles and fiction books, has more than 2 million scientific articles (which are published by researchers from universities around the world) and 2.7 million fiction books in several languages, mainly English, but it is possible to find content in Portuguese.
- [Sci-Hub](www.sci-hub.pw) - It's an online repository with more than 64 million scientific articles, available on its website. New documents are sent daily through the domains of educational institutions, which bypass systems that restrict access to Internet users without paid records on their websites. It was founded by a neuroscientist from Kazakhstan. To get a scientific article, just place the DOI (Digital Object Identifier - a standard for identifying digital objects) in the search field and the website will redirect you to purchase the article. A good website for picking up DOIs is at [ScienceDirect](https://www.sciencedirect.com/).
- [Scielo](www.scielo.org) - Scientific articles in Portuguese Scielo is a digital library of FAPESP, CNPq, Pan American Health Organization, Virtual Health Library and the Support Foundation to the Federal University of SP, where thousands of articles from all areas can be found in Portuguese and easily downloaded.
- [Z-Library](http://b-ok.xyz/) - The Z library is one of the largest online libraries in the world. We aim to make literature accessible to everyone.
- [startpage](https://www.startpage.com/por/?#hmb) - The world's most private search engine.
- [Open Library](https://openlibrary.org/) - This site allows you to borrow digital books in English.
- [ScanLibs](https://scanlibs.com/) - IT Ebooks Free Download PDF, EPUB, MOBI! Elearning Video For Programming Free Download MP4, AVI!
- [All IT ebooks](http://www.allitebooks.org/) - Free IT eBooks Download.
- [Free Online Books](https://hackmd.io/VASaLIb1Quunia9Nva7gpA)

[GO TO INDEX](#index)

<br />

## GitHub Projects

Projects to facilitate study:

- [The Data Science & Engineering Society](https://github.com/thedatasociety/)
- [restsims](https://github.com/cleder/restsims)
- [Netron ](https://github.com/lutzroeder/netron) -  Is a viewer for neural network, deep learning and machine learning models.
- [Data Visualization Curriculum](https://github.com/uwdata/visualization-curriculum)
- [Deep Learning Models](https://github.com/rasbt/deeplearning-models)
- [Data-Science--Cheat-Sheet](https://github.com/abhat222/Data-Science--Cheat-Sheet)
- [Digital Tools for Citizen Science](https://github.com/dylanrees/citizen-science)
- [Big List of Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings)
- [Progress Bar](https://github.com/rsalmei/alive-progress)
- [Computer Vision and Image Processing Tutorials](https://github.com/Grupo-OpenCV-BR/tutoriais-tecnologia)
- [Albumentations](https://github.com/albumentations-team/albumentations)
- [PyMatting: A Python Library for Alpha Matting](https://github.com/pymatting/pymatting)
- [Dask](https://github.com/dask/dask) - Is a flexible parallel computing library for analytics.
- [cookiecutter-spacy-fastapi](https://github.com/microsoft/cookiecutter-spacy-fastapi)

[GO TO INDEX](#index)

<br />

## Good Separate Texts

Links from different sites:

- [What is the importance of Exploratory Data Analysis?](Https://oestatistico.com.br/analise-exploratoria-de-dados/) [PT-BR]
- [Learning about web scraping in Python using BeautifulSoup](https://imasters.com.br/back-end/aprendi-sobre-web-scraping-em-python-using-beautifulsoup) [EN-US]
- [Docker images ready to run containing Jupyter applications](https://github.com/jupyter/docker-stacks) [EN-US]
- [Stanford - CS 229 - Machine Learning, Deep Learning - Professor Thiago Marques](https://stanford.edu/~shervine/teaching/cs-229.html) [EN-US]
- [Your company does not need a Data Lake to start a Machine Learning project](https://medium.com/@kunumi/sua-empresa-n%C3%A3o-precisa-de-um-data-lake-to-start-a-machine-learning-projectc1c1a4ba0f54) [PT-BR]
- [lambda, map and filter in Python](https://medium.com/@happymishra66/lambda-map-and-filter-in-python-4935f248593) [EN-US]
- [List comprehension in Python](https://hackernoon.com/list-comprehension-in-python-8895a785550b) [EN-US]
- [Faster Data Science Education - KAGGLE](https://www.kaggle.com/learn/overview) [EN-US]
- [Stanford Project and Poster Reports, Spring 2018](http://cs230.stanford.edu/proj-spring-2018.html) [EN-US]
- [These notes and tutorials are intended to complement material from Stanford's CS230 Deep Learning class](https://cs230-stanford.github.io/) [EN-US]
- [Guide: How to contribute in Open Source](https://willianjusten.com.br/guia-como-contribuir-em-open-source/)
- [Object Oriented Programming in Python: How to use inheritance in Python](https://professormarcolan.com.br/como-utilizar-a-heranca-em-python/) [PT-BR]
- [18 machine learning platforms for developers](https://dzone.com/articles/18-machine-learning-platforms-for-developers?edition=383284&utm_source=Weekly%20Digest&utm_medium=email&utm_campaign=Weekly%20Digest%202018-07-04) [EN-US]
- [5 quick and easy visualizations of Python data with code](https://towardsdatascience.com/5-quick-and-easy-data-visualizations-in-python-with-code-a2284bae952f) [EN-US]
- [The best guide to data classes in Python 3.7](https://realpython.com/python-data-classes/) [EN-US]
- [Starting a Python Project with Anaconda](https://roboticape.wordpress.com/2016/10/08/starting-a-python-project-with-anaconda/) [EN-US]
- [PEP 8 - Python Code Style Guide](https://www.python.org/dev/peps/pep-0008/) [EN-US]
- [The Python tutorial](http://turing.com.br/pydoc/2.7/tutorial/) [PT-BR]
- [Welcome to the Basemap Matplotlib 1 Toolkit documentation](https://matplotlib.org/basemap/) [EN-US]
- [Drawing a background map for the Basemap Matplotlib 2](https://matplotlib.org/basemap/users/geography.html) [EN-US]
- [How to use Jupyter Notebooks and pandas to analyze data](https://imasters.com.br/back-end/como-usar-notebooks-jupyter-e-pandas-para-analisar-dados) [EN-US]
- [Artificial Neural Networks](http://conteudo.icmc.usp.br/pessoas/andre/research/neural/) [PT-BR]
- [How to know if your Machine Learning model is really working](https://paulovasconcellos.com.br/como-saber-se-seu-modelo-de-machine-learning-est%C3%A1-funcionando-same-a5892f6468b) [PT-BR]
- [The mathematics of machine learning](https://towardsdatascience.com/the-mathematics-of-machine-learning-894f046c568) [EN-US]
- [When to use MLP, CNN and RNN neural networks](https://machinelearningmastery.com/when-to-use-mlp-cnn-and-rnn-neural-networks/) [EN-US]
- [24 Ultimate Data Science Projects boost your knowledge and skills to access for free](https://www.analyticsvidhya.com/blog/2018/05/24-ultimate-data-science-projects-to-boost-your-knowledge-and-skills/) [EN-US]
- [How to search efficiently](https://www.deborahmesquita.com/2017-08-04/como-pesearch-de-forma-eficiente) [PT-BR]
- [Graphic lies, misleading visuals: Reflections on the challenges and pitfalls of evidence-driven visual communication](https://miami.pure.elsevier.com/en/publications/graphics-lies-misleading-visuals-reflections-on-the-challenges-an) [EN-US]
- [A series of Jupyter notebooks to help data scientists get started with Python and Neo4j](https://github.com/nicolewhite/neo4j-jupyter) [EN-US]
- [Examples of Matplotlib Lines, Bars and Markers](https://www.kaggle.com/sskiing/matplotlib-lines-bars-and-markers-examples?scriptVersionId=1502597) [EN-US]
- [Bar Chart Annotations With Pandas and Matplotlib](http://robertmitchellv.com/blog-bar-chart-annotations-pandas-mpl.html) [EN-US]
- [HashTran-DNN: A framework to improve the robustness of deep neural networks against adverse malware samples](https://arxiv.org/abs/1809.06498) [EN-US]
- [What is this Apache Kafka?](Https://medium.com/@gabrielqueiroz/o-que-%C3%A9-esse-tal-de-apache-kafka-a8f447cac028) [EN-US]
- [First steps at InfluxDB](http://gcruz.com.br/blog/primeiros-passos-influxdb/) [PT-BR]
- [This notebook walks through basic code samples for integrating various packages with Neo4j, including py2neo, ipython-cypher, pandas, networkx, igraph, and jgraph](https://nicolewhite.github.io/neo4j-jupyter/hello-world.html) [EN-US]
- [Bar graph in matplotlib](https://plot.ly/matplotlib/bar-charts/) [EN-US]
- [How to use the FISH / QTCR / 5SS method to read scientific articles](http://posgraduando.com/fish-qtcr-5ss-leitura-artigos/) [PT-BR]
- [Top 20 Python Libraries for Data Science](http://datascienceacademy.com.br/blog/top-20-biblibraries-python-para-data-science/) [PT-BR]
- [How to Become a Data Scientist Before Graduating](http://berkeleysciencereview.com/how-to-become-a-data-scientist-before-you-graduate/) [EN-US]
- [Data Science career paths: different roles in the industry](https://www.springboard.com/blog/data-science-career-paths-different-roles-industry/) [EN-US]
- [12 Useful Python Techniques in Python for Data Manipulation](https://www.vooo.pro/insights/12-tecnicas-pandas-uteis-em-python-para-manipulacao-de-dados/) [PT- BR]
- [StackExchange Data Manager](http://data.stackexchange.com) [EN-US]
- [What to consider when choosing colors for data visualization](https://www.dataquest.io/blog/what-to-consider-when-choosing-colors-for-data-visualization/) [EN-US]
- [git and github part 1: what are they and how to use them?](https://www.ratamero.com/blog/git-e-github-parte-1-o-que-sao-e-como-usar/) [PT-BR]
- [Six open source panels to organize your data](https://www.astronomer.io/blog/six-open-source-dashboards/?ref=datahackers) [EN-US]
- [Laboratory of Immaterial Materials and Data Harvesting](https://labs.rs/en/facebook-algorithmic-factory-immaterial-labour-and-data-harvesting/) [EN-US]
- [The 10 most popular coding challenge sites for 2017](https://medium.freecodecamp.org/the-10-most-popular-coding-challenge-websites-of-2016-fb8a5672d22f) [EN-US]
- [Jupyter IPython Notebook quick start guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html) [EN-US]
- [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/latest/#) [EN-US]
- [IPython](https://ipython.readthedocs.io/en/stable/interactive/magics.html) [EN-US]
- [The PHP framework for the development of Chatbot](https://botman.io/) [EN-US]
- [At the end of the day: what is Kubernetes?](Https://www.treinaweb.com.br/blog/no-final-das-contas-o-que-eo-kubernetes/) [PT-BR ]
- [JupyterLab - your personal science data bank](https://skillsmatter.com/meetups/10726-jupyterlab-your-personal-data-science-workbench) [EN-US]
- [JupyterLab - a great tool for data scientists!](Https://bitfactor.fi/en/blog/2018/08/24/jupyterlab-a-great-tool-for-data-scientists/) [EN- US]
- [A curated list of amazing Jupyter projects, libraries and resources](https://github.com/markusschanta/awesome-jupyter) [EN-US]
- [Data Analysis in Python](https://www.analisededados.org/notebook2.html) [EN-US]
- [Hitchhiker's Guide to Exploratory Data Analysis](https://towardsdatascience.com/hitchhikers-guide-to-exploratory-data-analysis-6e8d896d3f7e) [EN-US]
- [Hitchhiker's Guide to Exploratory Data Analysis (Part 2)](https://towardsdatascience.com/hitchhikers-guide-to-exploratory-data-analysis-part-2-36ab72201e1d) [EN-US]
- [5945852-2 Connectionist Psychology - PG Psiciobiologia USP / RP - Prof. Antonio C. Roque](http://sisne.org/Disciplinas/PosGrad/PsicoConex/) [PT-BR]
- [Are we there yet? - Dataset](http://rodrigob.github.io/are_we_there_yet/build/) [EN-US]
- [Cornell University Library](https://arxiv.org/) [EN-US]
- [Kernel Eensity Estimation (KDE) ](https://en.wikipedia.org/wiki/Kernel_density_estimation) [EN-US]
- [Data Visualization Catalog - All Charts](https://datavizcatalogue.com/ES/index.html) [ES-ES]
- [Economics](https://arxiv.org/archive/econ) [EN-US]
- [Learn Computing with Python’s documentation!](Https://aprendendo-computacao-com-python.readthedocs.io/en/latest/index.html) [PT-BR]
- [Kaggle Github Plugin](https://www.kaggle.com/general/33266) [EN-US]
- [Understanding the kernel trick](https://towardsdatascience.com/understanding-the-kernel-trick-e0bc6112ef78) [EN-US]
- [The Art of Cleaning Your Data](https://towardsdatascience.com/the-art-of-cleaning-your-data-b713dbd49726) [EN-US]
- [datascience-br](https://github.com/datascience-br) [EN-US]
- [Particle Swarm Optimization from Scratch with Python](https://nathanrooy.github.io/posts/2016-08-17/simple-particle-swarm-optimization-with-python/) [EN-US]
- [PSO Resources](https://bee22.com/resources/) [EN-US]
- [Deep Learning Book](http://deeplearningbook.com.br/) [PT-BR]
- [Top Examples of Why Data Science is Not Just .fit().predict()](https://towardsdatascience.com/top-examples-of-why-data-science-is-not-just-fit-predict-ce7a13ef7663) [EN-US]
- [10 Data Science libraries for Python that nobody tells you](https://paulovasconcellos.com.br/10-biblibraries-de-data-science-para-python-que-ningu%C3%A9m-te-conta-706ec3c4fcef?Fbclid=IwAR2Zwl4FeFLYMoRsx6IX-hUMMEmy14U_8bbS4n4dii7x6bhb43NqRopna2w) [EN]
- [The (semi) definitive Guide for Data Lakes](https://medium.com/data-hackers/o-guia-semi-definitivo-para-data-lakes-461b1878697f) [EN-US]
- [Linear Regression and its role in Data Science](https://www.linkedin.com/pulse/regress%C3%A3o-linear-e-seu-papel-na-data-science-fillipe-marinho-mota/ ) [PT-BR]
- [Radial Basis Functions: sin x](https://www.kaggle.com/kabrol98/radial-basis-functions-sin-x) [EN-US]
- [How to run Linear regression in Python scikit-Learn](https://bigdata-madesimple.com/how-to-run-linear-regression-in-python-scikit-learn/) [EN-US]
- [19 Data Science and Machine Learning Tools for people who Don’t Know Programming](https://www.analyticsvidhya.com/blog/2018/05/19-data-science-tools-for-people-dont-understand-coding/) [EN-US]
- [How-to: Create a Simple Hadoop Cluster with VirtualBox](https://blog.cloudera.com/blog/2014/01/how-to-create-a-simple-hadoop-cluster-with-virtualbox/) [EN-US]
- [Hadoop for Beginners- Part 1](https://www.datasciencecentral.com/profiles/blogs/hadoop-for-beginners) [EN-US]
- [Teste Kolmogorov-Smirnov](https://pt.wikipedia.org/wiki/Teste_Kolmogorov-Smirnov) [EN-US]
- [Perform the Kolmogorov-Smirnov test for goodness of fit](https://docs.scipy.org/doc/scipy-0.14.0/reference/generated/scipy.stats.kstest.html) [EN-US]
- [Demystifying Data Science For All](http://businessoverbroadway.com/2017/10/29/demystifying-data-science-for-all/) [EN-US]
- [Web Face Recognition](https://github.com/pedrohenriquebr/web-face-recognition) [PT-BR]
- [Study plan for machine learning with content in Portuguese.](Https://github.com/italojs/awesome-machine-learning-portugues) [PT-BR]
- [23 data science and data enrichment startups](https://insights.liga.ventures/itstartups-ti/23-startups-data-science-enriquecimento-dados/) [PT-BR]
- [How to understand Machine Learning through food](https://medium.com/ensina-ai/como-entender-machine-learning-atrav%C3%A9s-da-comida-122bf6f84b35) [PT-BR]
- [Compressing and Extracting Files in Python](https://code.tutsplus.com/en/tutorials/compressing-and-extracting-files-in-python--cms-26816) [EN-US]
- [Play with neural networks!](http://playground.tensorflow.org) [EN-US]
- [Create smart AWS diagrams](https://cloudcraft.co/) [EN-US]
- [Tidymodels](https://www.datisticsblog.com/2018/12/tidymodels/#introduction) [EN-US]
- [Hitchhiker’s guide to Exploratory Data Analysis(Part- 2)](https://towardsdatascience.com/hitchhikers-guide-to-exploratory-data-analysis-part-2-36ab72201e1d) [EN-US]
- [Differences between segmentation and clustering](https://www.dadosaleatorios.com.br/post/diferen%C3%A7as-entre-segmenta%C3%A7%C3%A3o-e-clusteriza%C3%A7%C3%A3o/) [PT-BR]
- [Feature Selection a Silver Bullet](http://minerandodados.com.br/index.php/2018/05/21/feature-selection-bala-de-prata/) [PT-BR]
- [Classifying Spotify Songs with SVM (With Python Codes)](http://minerandodados.com.br/index.php/2018/04/04/spotify-svm-python/) [PT-BR]
- [How to Use Machine Learning to Predict Stock Prices on the Stock Exchange - The Complete Case Study.](Http://minerandodados.com.br/index.php/2017/05/19/prevendo-precos-de-shares-of-the-stock-exchange-with-machine-learning/) [PT-BR]
- [Time Series Modeling with Python - SciPy-SP](http://wilsonfreitas.github.io/posts/modelagem-de-series-temporais-com-python-scipy-sp.html) [PT-BR]
- [Linear Regression](https://medium.com/@avinicius.adorno/regress%C3%A3o-linear-a7d7d20f39ac) [PT-BR]
- [How to Create a Simple Model to Predict Time Series Using Machine Learning in Python](http://mariofilho.com/como-criar-um-modelo-simples-para-prever-series-temporais-usando-machine-learning-em-python/) [PT-BR]
- [Applying Linear Regression with Scikit-Learn](https://matheusfacure.github.io/2017/07/07/MQO-sklearn/) [PT-BR]
- [7 TECHNIQUES FOR REDUCING DIMENSIONALITY](https://mineracaodedados.wordpress.com/2015/06/13/7-tecnicas-para-reducao-da-dimensionalidade/) [PT-BR]
- [10 Machine Learning Algorithms you need to know](https://www.semantix.com.br/blog/10-algoritmos-de-machine-learning) [PT-BR]
- [Understand the types of machine learning algorithms and their applications](http://sas.itforum365.com.br/analytics-hub/entenda-os-4-algoritmos-de-machine-learning-e-suas-aplicacoes ) [PT-BR]
- [Python Serverless Microframework for AWS](https://github.com/aws/chalice) [EN-US]
- [8 Machine Learning Algorithms in Python – You Must Learn](https://data-flair.training/blogs/machine-learning-algorithms-in-python/) [EN-US]
- [10 simple hacks to speed up your data analysis in Python](https://towardsdatascience.com/10-simple-hacks-to-speed-up-your-data-analysis-in-python-ec18c6396e6b) [EN- US]
- [10 reasons why software development projects fail](https://medium.com/specstimate/10-reasons-why-software-development-projects-fail-7200e7c9ae2e) [EN-US]
- [Creating an NLP model for classifying tweets with fklearn](https://medium.com/data-hackers/criando-um-modelo-nlp-de-classifica%C3%A7%C3%A3o-de-tweets-com-fklearn-b8ff88b96cde) [EN-US]
- [Ludwig is a toolbox that allows you to train and test deep learning models without the need to write code.](Https://uber.github.io/ludwig/) [EN-US]
- [Do you want to become a data engineer? Here is a comprehensive list of resources to get started](https://www.analyticsvidhya.com/blog/2018/11/data-engineer-comprehensive-list-resources-get-started/?source=post_page---------------------------) [EN-US]
- [The Problemeter: A spreadsheet that helps startups solve the right problem](https://hackernoon.com/the-problemeter-a-sheet-that-helps-startups-solve-the-right-problem-qy7o34wv) [EN-US]
- [Beginners Guide to Modeling Python Topics](https://www.analyticsvidhya.com/blog/2016/08/beginners-guide-to-topic-modeling-in-python/) [EN-US]
- [Gensim Tutorial - A Complete Guide for Beginners](https://www.machinelearningplus.com/nlp/gensim-tutorial/) [EN-US]
- [Pre-processing of text data: A step by step in Python](https://www.kdnuggets.com/2018/03/text-data-preprocessing-walkthrough-python.html) [EN-US]
- [10 more Data Science libraries for Python that nobody tells you](https://medium.com/data-hackers/mais-10-biblibraries-de-data-science-para-python-que-ninguém-te-conta-1a636837a404) [EN-BR]
- [HTML microdata](https://www.w3.org/TR/microdata/) - Defines new HTML attributes to incorporate simple machine-readable data into HTML documents.
- [Stacked Capsule Autoencoders](http://akosiorek.github.io/ml/2019/06/23/stacked_capsule_autoencoders.html)
- [DuckDB is an embeddable SQL OLAP database management system](https://www.duckdb.org/)
- [nltk](https://www.it-swarm.dev/pt/nltk/)
- [Machine Learning Rest API in a Docker](https://juan-medina.com/2015/12/05/machine-learning-docker/)
- [Building a Movie Recommendation Service with Apache Spark & Flask - Part 2](https://www.codementor.io/@jadianes/building-a-web-service-with-apache-spark-flask-example-app-part2-du1083854)
- [Standardizing the World of Machine Learning Web Service APIs](https://www.kdnuggets.com/2015/07/psi-machine-learning-web-service-apis.html)
- [How to deploy ML models using Flask + Gunicorn + Nginx + Docker](https://towardsdatascience.com/how-to-deploy-ml-models-using-flask-gunicorn-nginx-docker-9b32055b3d0)
- [The Open Source Computer Science Degree](https://github.com/ForrestKnight/open-source-cs)
- [Banguroo](https://www.buguroo.com/)
- [MACHINE LEARNING FOR COMPUTER SECURITY](http://www.mlsec.org/)
- [MLSec Project](https://github.com/mlsecproject)
- [Fraud Detection](https://www.datacamp.com/search?q=fraus&__cf_chl_jschl_tk__=0b902699526f45630aab28dfee7d5414c70463c0-1607553643-0-AZgOfMpFzuSi3ha8UKgejbgUTjysiIxx4pMRez-hfBJp33z3e8WGuzbD7v5Bl3mnW8Fe97Q9VdmGjvT1aVIBuVxiQE9XDlUDm1b22MkwzNT4po5_94gSfgivNKg9OzSTyOdurjt54UrgeJNCKgcixKP5kMenaLiCDsiPZ5XRl5AAIMGtDk7BD8V5pSpGN0QmanOVjJ591RbBACIK5hDe62gvEaLe4xT2nM8K5pMSlrTq2pC5cQUIvvbpV-m4WFL2g3zzuKN2XOEYw7nH-SQ77zFmYjT7CJigOyvwPTKdlkY846sgH1ZqgfhSMmOKGQONk-l1HSVZfbk-gHrQ3bSHuL0)
- [10 Simple hacks to speed up your Data Analysis in Python](https://towardsdatascience.com/10-simple-hacks-to-speed-up-your-data-analysis-in-python-ec18c6396e6b)
- [How to deploy ML models using Flask + Gunicorn + Nginx + Docker](https://towardsdatascience.com/how-to-deploy-ml-models-using-flask-gunicorn-nginx-docker-9b32055b3d0)
- [How to Build a Simple Machine Learning Web App in Python](https://towardsdatascience.com/how-to-build-a-simple-machine-learning-web-app-in-python-68a45a0e0291)
- [dongweiming/data-analysis](https://github.com/dongweiming/data-analysis/tree/master/data_analysis)
- [Kyso](https://kyso.io/)
- [MapMyCab: How I Chose a Data Engineering Project](https://blog.insightdatascience.com/mapmycab-how-i-chose-a-data-engineering-project-75bd659c5eec)
- [INSIGHT DATA ENGINEERING FELLOWS PROGRAM](https://insightfellows.com/data-engineering)
- [The Data Engineering Cookbook](https://github.com/andkret/Cookbook)
- [Using iloc, loc, & ix to select rows and columns in Pandas DataFrames](https://www.shanelynn.ie/select-pandas-dataframe-rows-and-columns-using-iloc-loc-and-ix/)
- [Flask by Example – Text Processing with Requests, BeautifulSoup, and NLTK](https://realpython.com/flask-by-example-part-3-text-processing-with-requests-beautifulsoup-nltk/)
- [Data Engineering — the Cousin of Data Science, is Troublesome](https://towardsdatascience.com/data-engineering-the-cousin-of-data-science-is-troublesome-3a9332b532ae)
- [Scrapy Vs Selenium Vs Beautiful Soup for Web Scraping](https://medium.com/analytics-vidhya/scrapy-vs-selenium-vs-beautiful-soup-for-web-scraping-24008b6c87b8)
- [WIBD Workshops 2018](https://github.com/NFLX-WIBD/WIBD-Workshops-2018)
- [Predicting the Fake News using Python](https://morioh.com/p/cec8f7ad0c9a?f=5c21fb01c16e2556b555ab32)
- [EasyOCR](https://github.com/JaidedAI/EasyOCR)
- [CRISP-DM, SEMMA and KDD: find out the best techniques for data exploration](https://paulovasconcellos.com.br/crisp-dm-semma-e-kdd-conhe%C3%A7a-as-melhores-t%C3%A9cicas-para-explora%C3%A7%C3%A3o-de-data-560d294547d2)
- [Between causes and effects: how to identify causality amid correlations](https://medium.com/big-data-blog/entre-causas-e-efeitos-como-identificar-causalidade-em-meio-a-correlation%C3%A7%C3%B5es-8f6aad0a3790)
- [Recurrent Neural Networks: a brief introduction](https://dataml.com.br/redes-neurais-recorrentes-uma-breve-introducao/)
- [Python Fundamentals for Data Analysis](https://www.datascienceacademy.com.br/course?courseid=python-fundamentos)
- [Introducing New Relic’s Dynamic Baseline Alerts](https://blog.newrelic.com/2016/11/16/dynamic-baseline-alerts/) - Time series analysis.
- [TIME SERIES CHARACTERISTICS](https://operdata.com.br/blog/caracteristicas-das-series-temporais/)
- [Novelty and Outlier Detection](http://scikit-learn.org/stable/modules/outlier_detection.html) - Anomaly detection.
- [Anomaly Detection, a short tutorial using Python](https://aqibsaeed.github.io/2016-07-17-anomaly-detection/) - Anomaly detection.
- [mxGraph](https://github.com/jgraph/mxgraph) - Graph / data flow widgets.
- [Altair](https://altair-viz.github.io/) - Altair is a declarative statistical visualization library for Python, based on the powerful visualization grammar Vega-Lite -Visualization.
- [Bokeh](http://bokeh.pydata.org/en/latest/) - Bokeh is a Python interactive visualization library that targets modern browsers for presentation -View.
- [Matplotlib D3 (mpld3)](http://mpld3.github.io/) - The mpld3 project brings together Matplotlib, the popular Python-based graphics library, and D3js, the popular JavaScript library for creating data visualizations interactive for the web -View.
- [Data-Driven Documents](https://d3js.org/) - D3.js is a JavaScript library for manipulating documents based on data -View.
- [Using Flask to serve a machine learning model as a RESTful web service](https://www.youtube.com/watch?v=s-i6nzXQF3g) - Article.
- [How to Build a Simple Machine Learning Web App in Python](https://towardsdatascience.com/how-to-build-a-simple-machine-learning-web-app-in-python-68a45a0e0291)
- [docker-ml-api](https://github.com/juan-medina/docker-ml-api)
- [Springer has released 65 Machine Learning and Data books for free](https://towardsdatascience.com/springer-has-released-65-machine-learning-and-data-books-for-free-961f8181f189)
- [Python Data Streamer](https://github.com/initialstate/python_appender#python-data-streamer) [EN-US]
- [docker_django_mongodb](https://github.com/balanpradeepkumar/docker_django_mongodb) [EN-US]
- [There is a bot for](https://thereisabotforthat.com/)
- [Gartner Hype Cycle Data Science 2019](https://www.google.com/search?q=gartner+hype+cycle+data+science+2019&sxsrf=ALeKk03Tccr5JmdgeWWV3-_-cp3sPJtL1g:1593479859205&tbm=isch&source=iu&ictx=1&fir=eMwB4ob0w5I9SM%2CdnKluq0f3J2jSM%2C_&vet=1&usg=AI4_-kSkCPJJF7SNCBing2yC0uaxcqK9KQ&sa=X&ved=2ahUKEwjvntuHr6jqAhVFJLkGHQSfBBUQ9QEwBHoECAoQJA&biw=1366&bih=667)
- [Cookiecutter Data Science](https://www.google.com/search?q=cookiecutter%20data%20science)
- [Cheat Sheets for AI, Neural Networks, Machine Learning, Deep Learning & Big Data](https://becominghuman.ai/cheat-sheets-for-ai-neural-networks-machine-learning-deep-learning-big-data-678c51b4b463)
- [Gradient](https://gradient.paperspace.com/)
- [Standardizing Machine Learning World Web Service APIs](http://www.kdnuggets.com/2015/07/psi-machine-learning-web-service-apis.html) - Article.
- [Machine Learning Rest API on a Docker](https://juan-medina.com/2015/12/05/machine-learning-docker/) - Article.
- [Using Flask to serve a machine learning model as a RESTful webservice](https://www.youtube.com/watch?v=s-i6nzXQF3g)
- [Fastapi Vue.js - Python Javascript Integration](https://medium.com/@marciobbarbosa/fastapi-vue-js-integração-python-javascript-ddab7e6905a4)
- [Building a movie recommendation service with Apache Spark & Flask - Part 2](https://www.codementor.io/jadianes/building-a-web-service-with-apache-spark-flask-example-app-part2-du1083854) - Article.
- [Nvidia Fundamentals of Deep Learning for Computer Vision](https://courses.nvidia.com/courses/course-v1:DLI+C-FX-01+V2/info)
- [Complex Data Mining](https://ic.unicamp.br/~mdc/)
- [Amdahl's Law](https://en.wikipedia.org/wiki/Lei_de_Amdahl)
- [What mathematics do I need to become a data scientist?](Https://blog.skillfactory.ru/nauka-o-dannyh-data-science/math_for_ds/?utm_source=vk&utm_medium=social_add&utm_campaign=mashinnoe_obuchenie_ai_iguchdmdut_ut_data&ut_d_stata)
- [Downloadable: Cheat Sheets for AI, Neural Networks, Machine Learning, Deep Learning & Data Science PDF](https://becominghuman.ai/cheat-sheets-for-ai-neural-networks-machine-learning-deep-learning-big-data-science-pdf-f22dc900d2d7)
- [Awesome production machine learning](https://github.com/EthicalML/awesome-production-machine-learning) [EN-US] - This repository contains a curated list of amazing open source libraries that will help you deploy , monitor, version, scale and protect production machine learning.
- [Introduction to SVELTE](https://medium.com/swlh/introduction-to-svelte-cdfaba91700) - A JavaScript framework for building fast, beautiful and responsive user interfaces.
- [6 books ‘non-techs’ for Data Sciencea](https://medium.com/@paulopestanajunior/6-livros-n%C3%A3o-techs-para-data-science-7f95d972782) [EN-US]
- [TOP 20 PYTHON LIBRARIES FOR DATA SCIENCE](http://datascienceacademy.com.br/blog/top-20-biblibraries-python-para-data-science/)
- [Grafana with InfluxDB and Telegraf to generate graphics](https://www.dobitaobyte.com.br/grafana-com-influxdb-e-telegraf/)
- [DATA SCIENCE SCHOOL](https://escola.sigmoidal.ai/?utm_fbad=6239066007251&fbclid=PAAaYcFLrU3yhezUpPBNK3Q3KE9U1cZEX5NdKEt4pqpQav_Iu5RN3dBqYHiUs)
- [Open Source Government](https://amarabuco.github.io/governoopensource/)
- [Data Science for a Cause](https://sites.google.com/view/cienciacausa/a%C3%A7%C3%B5es-registradas)

[GO TO INDEX](#index)

<br />

## Awesome Lists

Below are lists with more content that increase the capacity of this list to x1000:

- [Awesome Deep Learning Project Ideas](https://github.com/NirantK/awesome-project-ideas)
- [Awesome production machine learning](https://github.com/EthicalML/awesome-production-machine-learning)
- [Starting a Python Project with Anaconda](https://roboticape.com/2016/10/08/starting-a-python-project-with-anaconda/)
- [Awesome Graph Classification](https://github.com/benedekrozemberczki/awesome-graph-classification)
- [Awesome Research Tools](https://github.com/emptymalei/awesome-research)
- [Awesome dataviz](https://github.com/fasouto/awesome-dataviz)
- [Awesome Microservices](https://github.com/mfornos/awesome-microservices)
- [Python Web Scraping](https://github.com/lorien/awesome-web-scraping/blob/master/python.md)
- [Awesome Data Engineering](https://github.com/igorbarinov/awesome-data-engineering)
- [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata)
- [Awesome Jupyter](https://github.com/markusschanta/awesome-jupyter)
- [Data Science IPython Notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) - Data Science: Python notebooks: Deep learning (TensorFlow, Theano, Caffe, Keras), scikit-learn, Kaggle, big data (Spark, Hadoop MapReduce, HDFS), matplotlib, pandas, NumPy, SciPy, Python essentials, AWS and several command lines.
- [Awesome R](https://github.com/qinwf/awesome-R) - A curated list of amazing R packages, frameworks and software.
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) - A topic-centric list of high quality open data sets in public domains.
  [Galaxy Data Scientist Guide](https://github.com/leportella/datascience-pizza/blob/master/README.md) - This repository was made by and for the community.
- [Awesome Indexed](https://awesome-indexed.mathew-davies.co.uk) - Search the Awesome data set.
- [Awesome Search](https://awesomelists.top) - Quick search for awesome listings.
- [Awesome Machine Learning On Source Code](https://github.com/src-d/awesome-machine-learning-on-source-code) [EN-US] - Legal links and research articles related to Learning Machine applied to the source code (MLonCode).
- [Awesome Data Science](https://github.com/bulutyazilim/awesome-datascience#motivation) [EN-US] - An open source data science repository to learn and apply in real-world problem solving.
- [Awesome](https://github.com/sindresorhus/awesome) [EN-US] - Curated list of impressive lists.
- [Open Data Sources](https://github.com/datasciencemasters/data) [EN-US] - Open Data Sources.
- [Github free data source list](http://www.datasciencecentral.com/profiles/blogs/great-github-list-of-public-data-sets) [EN-US] - Github's large list of sets public data.
- [Public Git Archive](https://github.com/src-d/datasets/tree/master/PublicGitArchive) [EN-US] - Public Git archive.
- [Datasharing](https://github.com/jtleek/datasharing) [EN-US] - The Leek group's guide to data sharing.
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness) [EN-US] - An impressive curated list.
- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) [EN-US] - A curated list of amazing Machine Learning structures, libraries and software.
- [Lists](https://github.com/jnv/lists) [EN-US] - List of useful, silly and impressive lists, selected on GitHub.
- [Awesome dataviz](https://github.com/fasouto/awesome-dataviz) [EN-US] - A curated list of libraries and impressive data visualization resources.
- [Awesome Python](https://github.com/vinta/awesome-python) [EN-US] - A curated list of impressive Python structures, libraries, software and resources.
- [Python Web Scraping](https://github.com/lorien/awesome-web-scraping/blob/master/python.md) - Awesome Github repository.
- [Data Science IPython Notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) [EN-US] - Data Science: Python notebooks: Deep learning (TensorFlow, Theano, Caffe, Keras) , scikit-learn, Kaggle, big data (Spark, Hadoop MapReduce, HDFS), matplotlib, pandas, NumPy, SciPy, Python essentials, AWS and several command lines.
- [Awesome R](https://github.com/qinwf/awesome-R) [EN-US] - A curated list of amazing R packages, frameworks and software.
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) [EN-US] - A topic-centric list of high quality open data sets in public domains.
- [Machine Learning & Deep Learning Tutorials](https://github.com/ujjwalkarn/Machine-Learning-Tutorials/blob/master/README.md) [EN-US] - This repository contains a curated list of topics from Machine Learning and Detailed Learning tutorials, articles and other resources. Other impressive lists can be found in this list.
- [Awesome Artificial Intelligence use cases](https://github.com/faktionai/awesome-ai-usecases) [EN-US] - A list of impressive and proven artificial intelligence cases and applications.
- [Top-down learning path: Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers) [EN-US] - A complete daily plan to study to become a machine learning engineer.
- [Data Science Tutorials and Courses](https://hackr.io/tutorials/learn-data-science) [EN-US] - Learn Data Science online from the best submitted Data Science courses and tutorials and voted by the programming community. Mathematics and Statistics courses required for Data Science are also included here.
- [The Free Big Data Sources Everyone Should Know](http://www.datasciencecentral.com/profiles/blogs/the-free-big-data-sources-everyone-should-know) [EN-US] - The sources free Big Data that everyone should know.
- [20 Big Data Repositories You Should Check Out](https://www.datasciencecentral.com/profiles/blogs/20-big-data-repositories-you-should-check-out-1) [EN-US] - 20 large data repositories that you should check out.
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets/blob/master/README.rst) [EN-US] - Public data sets.
- [Awesome Public Datasets](https://github.com/shubhamjn1/awesome-public-datasetst) [EN-US] - A list of high quality open data sets in public domains.
- [Galaxy Data Scientist Guide](https://github.com/leportella/datascience-pizza/blob/master/README.md) [EN-BR] - This repository was made by and for the community.
- [Awesome production machine learning](https://github.com/EthicalML/awesome-production-machine-learning) [EN-US] - This repository contains a curated list of amazing open source libraries that will help you deploy , monitor, version, scale and protect production machine learning.

[GO TO INDEX](#index)

<br />

## Notes

Space to add Data Science notes:

```
ADD NOTES HERE
```

[GO TO INDEX](#index)

<br />

## Images

Yes! More than a thousand words are worth ..

In the folder **image**, you will find a compilation of images referring to Data Science.

***

**Remember!**

**Copying everything from StackOverflow, doesn't make you understand anything, it just makes you a good copier!**

***
