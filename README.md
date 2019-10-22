# 0-Syllabus
#### `Programming and Data Science for Biology -- EEEB 4050`  
Spring 2018; Mondays: 2:10-4pm  
E3B Department Columbia University  
Instructor: Dr. Deren Eaton (de2356@columbia.edu)  
Teaching Assistant: Patrick McKenzie (p.mckenzie@columbia.edu)  

#### Office Hours:
Professor Eaton: Fridays, 10am-12pm in 1007 Schermerhorn Ext.  
Patrick McKenzie: Tuesdays 2-4pm in student room, Schermerhorn Ext.

#### Bulletin:  
Programming and Data Science for Biologists (PDSB) will introduce students to fundamental computational skills and concepts for working with large biological data sets. This will include an introduction to several programming languages (Python, R, Julia), and in-depth training in one language in particular (Python). We will cover tools for collaboration and version control (git, GitHub), and how these tools can be used to host and share code, data, and websites. A core focus throughout the course will be reproducibility and learning tools (jupyter) and practices for this purpose. We will learn to organize and structure data for statistical analyses (DataFrames, arrays, datatypes), and explore tools for scientific analyses (scipy, pymc3, scikit-learn, keras) and visualization (matplotlib, toyplot, bokeh). Exercises and assignments will introduce students to large empirical datasets used in the biological sciences, from studies of genomics to biodiversity. The latter half of the class is organized around individual projects, in which students will be guided to design a command-line program and/or API for performing a specific type of analysis. Computer programs are ubiquitous in biology, but few biologists receive formal training in designing and writing software. This course offers a deeper introduction to computational techniques and algorithms commonly applied to biological datasets.

#### Organization:  
The course meets on Mondays from 2:10-4pm. Each meeting will be a mix of lecture, in-class "active" learning, and group activities. In addition there will be a lot of work outside of clas to complete individual and group assignments, as well as a final project. In class activities will include group problem solving and code comparisons. All software and materials for the course are open access (available online for free) including assigned readings. An example session would include a lecture to introduce a general concept with examples from biological research, followed by a group active-learning exercise in which students implement the method applied to real datasets. 

#### Assignments:  
There will be code-based assignments for nearly every class period. These will require completing assignments outside of class in addition to performing "code reviews" of submissions by classmates based on assigned criteria. For example, check that their code works, that it follows proper style, and describe how the implementation differs from your own code. Both code and code reviews will be graded. A course project will be developed by each student and defended through a formal proposal process and later presented as a final project. Projects will be developed and published as open source code on github and evaluated on the basis of documentation, task-completion, and examples. 

#### Basis for grading:  
Grades will be composed of 13 assignments (35%) and code reviews (20%), a project proposal (5%), project presentation (5%), and project grade (20%), as well as on class participation (15%). 

#### Statement on Academic Integrity:  
Academic dishonesty is a serious offense and will not be tolerated in the class. Students are expected to reference sources appropriately in any work, including references to open source code found on-line, forum discussions, or third party software tools used in assignments or projects. Violation of the rules of academic integrity (e.g., plagiarism) from Columbia College or the Graduate School of the Arts and Sciences, will result in automatic failure of the course. Rules and consequences are outlined in Columbia College's Faculty Statement on Academic Integrity: [http://www.college.columbia.edu/faculty/resourcesforinstructors/academicintegrity/statement](http://www.college.columbia.edu/faculty/resourcesforinstructors/academicintegrity/statement). 

#### Statement on policy for students with disabilities:  
[http://www.college.columbia.edu/rightsandresponsibilities](http://www.college.columbia.edu/rightsandresponsibilities)

#### Syllabus outline: 

------------
**Session 1:** 1/22/2018  
**Lecture:** introduction, syllabus, unix, bash, markdown, github  
**Assigned tasks:** [Link to session 1 repo](https://github.com/programming-for-bio/1-Shell-Basics).   
**Reading due:** None   
**Assignment due:** None  
**Code Review due:** None  

-------------

**Session 2:** 1/29/2018  
**Lecture:** git, GitHub, installation, conda  
**Assigned tasks:** [Link to session 2 repo](https://github.com/programming-for-bio/2-git-and-more).   
**Reading due:** Chapter 1-2: [https://git-scm.com/book/en/v2](https://git-scm.com/book/en/v2)     
**Assignment due:** [Link to session 1 repo](https://github.com/programming-for-bio/1-Shell-Basics).   
**Code Review due:** None  

-------------

**Session 3:** 2/5/2018  
**Lecture:** git, GitHub, conda, jupyter, Python strings, lists.  
**Assigned tasks:** [Link to session 3 repo](https://github.com/programming-for-bio/3-Python-basics).   
**Reading due:** [Python basics chapters 1-4](http://www.greenteapress.com/thinkpython2/html/index.html).  
**Assignment due:** [Link to session 2 repo](https://github.com/programming-for-bio/2-git-and-more).   
**Code Review due:** None

-------------

**Session 4:** 2/12/2018  
**Lecture:** Python dicts, hashing, mapping, '.py' files, importing  
**Assigned tasks:** [Link to session 4 repo](https://github.com/programming-for-bio/4-Python-advanced)    
**Reading due:** [Python basics chapters 5-13](http://www.greenteapress.com/thinkpython2/html/index.html)  
**Assignment due:** [3-Python-Basics](https://github.com/programming-for-bio/3-Python-basics).  
**Code Review due:** [3-Python-Basics](https://github.com/programming-for-bio/3-Python-basics/tree/master/Code-review).   

-------------


**Session 5:** 2/19/2018  
**Lecture:** Packaging, API, CLI, argparse, sublimetext.  
**Assigned tasks:** [5-packaging/](https://github.com/programming-for-bio/5-packaging)   
**Reading due:** [Python basics chapters 14-18](http://www.greenteapress.com/thinkpython2/html/index.html) and [*Pythonista* style guide](http://python.net/~goodger/projects/pycon/2007/idiomatic/handout.html).  
**Assignment due:** [4-Python-advanced/Assignment](https://github.com/programming-for-bio/4-Python-advanced)  
**Code Review due:** [4-Python-advanced/Code-Review](https://github.com/programming-for-bio/4-Python-advanced/tree/master/Code-review).   

--------------


**Session 6:** 2/26/2018  
**Lecture:** Scientific Python, numpy, scipy, pandas.  
**Assigned tasks:** [Link to session 6 repo](https://github.com/programming-for-bio/6-scientific-python)  
**Reading due:** [Numpy & Pandas user guide](https://jakevdp.github.io/PythonDataScienceHandbook/)  
**Assignment due:** 5-Python-Packaging    
**Code Review due:** 5-Python-Packaging    

---------------


**Session 7:** 3/5/2018  
**Lecture:** Python as glue; subprocess, jupyter-tunneling, SSH  
**Assigned tasks:** [Link to session 7 repo](https://github.com/programming-for-bio/6-scientific-python)   
**Reading due:** None  
**Assignment due:** 6-scientific-python  
**Code Review due:** 6-scientific-python (revised)   

---------------

SPRING BREAK
[see project proposal guide here](https://github.com/programming-for-bio/project-proposal-guide)  
**PROJECT PROPOSALS DUE: 3/21/2018**

---------------

**Session 8:** 3/19/2018  
**Lecture:** web-scraping, HTML, requests, REST  
**Assigned tasks:** [Link to session 8 repo](https://github.com/programming-for-bio/8-python-web)     
**Reading due:** No reading due   
**Assignment due:** Project proposals due 3/21  
**Code Review due:** None  

---------------

**Session 9:** 3/26/2018  
**Lecture:** Analysis I: intro to machine learning
**Reading due:** Chapters 4 & 5 of [Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)  
**Assigned tasks:** Notebooks 9.1-9.2  
**Assignment due:** 'Records' repository from noteook 8.2 due 3/23  
**Code Review due:** Fixed up 'Records' repository by 3/26  


---------------

**Session 10:** 4/2/2018  
**Lecture:** Analysis II: intro to maximum likelihood and Bayesian statistics  
**Assigned tasks:** Notebooks 10.1-10.6    
**Reading due:** [gentle intro to Bayesian stats](https://www.analyticsvidhya.com/blog/2016/06/bayesian-statistics-beginners-simple-english/); [Getting started page of pymc3 tutorial](http://docs.pymc.io/notebooks/getting_started).  
**Assignment due:** machine learning applied to `records` dataframes.   
**Code Review due:** None.   

---------------

**Session 11:** 4/9/2018  
**Lecture:** plotting in Python, plotting for the web, and plotting in general.  
**Assigned tasks:** Notebooks 11.1-11.5   
**Reading due:**   
+ [Chapter 4 of Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
+ [Toyplot Tutorial & User Guide](http://toyplot.readthedocs.io/en/stable/)  
+ Bokeh example app guide: 
	[Part I](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwjin_iP4JvaAhXyqFkKHaQAD8sQFggpMAA&url=https%3A%2F%2Ftowardsdatascience.com%2Fdata-visualization-with-bokeh-in-python-part-one-getting-started-a11655a467d4&usg=AOvVaw1OfPgwhpgT4YlJw8SeNV77), 
	[Part II](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=0ahUKEwjin_iP4JvaAhXyqFkKHaQAD8sQFgg1MAI&url=https%3A%2F%2Ftowardsdatascience.com%2Fdata-visualization-with-bokeh-in-python-part-ii-interactions-a4cf994e2512&usg=AOvVaw08iiC0OOTZCi3BKdu79RwA), 
	[Part III](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=0ahUKEwjin_iP4JvaAhXyqFkKHaQAD8sQFggvMAE&url=https%3A%2F%2Ftowardsdatascience.com%2Fdata-visualization-with-bokeh-in-python-part-iii-a-complete-dashboard-dc6a86aa6e23&usg=AOvVaw1s-ZbUCRqVW3maXdy00-VA). 

**Assignment due:** Notebook 10.7 in assignment directory of the repo.   
**Code Review due:** Notebook 10.7  

---------------

**Session 12:** 4/16/2018  
**Lecture:** genomics and parallel programming  
**Assigned tasks:** Notebooks 12.1-12.5  
**Reading due:**   
+ [at least skim the ipyrad tutorial](http://ipyrad.readthedocs.io/features.html)  
+ [ipyrad-API-example](http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/cookbook-empirical-API-1-pedicularis.ipynb)  

**Assignment due:** Notebook 11.5  
**Code Review due:** Code-review 11.5  

---------------

**Session 13:** 4/23/2018  
**Lecture:** Project Presentations and genomics part II  
**Assigned tasks:** Notebooks 13.2-13.3  
**Reading due:** 
+ [brief ipyparallel tutorial](http://nbviewer.jupyter.org/github/dereneaton/ipyrad/blob/master/tests/ipyparallel-tutorial.ipynb) 
+ [brief HPC tunneling review](http://ipyrad.readthedocs.io/HPC_Tunnel.html)
+ [See notebooks links for ipyrad analysis tools](http://ipyrad.readthedocs.io/analysis.html)  

**Assignment due:** Notebooks 12.4 and 12.5  
**Code Review due:** Code review 12.5  

---------------

**Session 14:** 4/30/2018  
**Lecture:** Project Presentations and genomics part III  
**Assigned tasks:** Note  
**Reading due:** None  
**Assignment due:** None  
**Code Review due:** 13-applied-Python-machine-learning  

---------------

**No Classes:** 5/7/2018  
**No Classes:** 5/11/2018  
**Final Projects due online:** 5/11/2018  
