Web application and API for managing and monitoring [Spring Batch](http://static.springsource.org/spring-batch) jobs.  The application consists of a web UI using Spring MVC, a Java service API and a RESTful (JSON) API.  The web application is highly customizable, and is an ideal platform for deploying Spring Batch jobs.  It can also be used to monitor jobs running in other processes. See the main [project website](http://static.springsource.org/spring-batch-admin) for more details.

# Getting Started Using SpringSource Tool Suite (STS)

  This is the quickest way to get started.  It requires an internet connection for download, and access to a Maven repository (remote or local).

* Download STS version 2.5.* (or better) from the [SpringSource website](http://www.springsource.com/products/sts).  STS is a free Eclipse bundle with many features useful for Spring developers.
* Go to `File->New->Spring Template Project` from the menu bar (in the Spring perspective).
* The wizard has a drop down with a list of template projects.  One of them is a "Spring Batch Admin Webapp".  Select it and follow the wizard.
* A project is created with all dependencies and a simple input/output job configuration.  It can be run using a unit test, or on the command line (see instructions in the pom.xml).

# Getting Help

Read the main project [website](http://www.springsource.org/spring-batch-admin) and the [User Guide](http://www.springsource.org/spring-batch-admin/reference). Look at the source code and the Javadocs.  For more detailed questions, use the [forum](http://forum.springsource.org/forumdisplay.php?f=41).  If you are new to Spring as well as to Spring Batch, look for information about [Spring projects](http://www.springsource.org/projects).

# Contributing to Spring Batch Admin

Please help out on the [forum](http://forum.springsource.org/forumdisplay.php?f=41) by responding to questions and joining the debate.  Create [JIRA](https://jira.springsource.org/browse/BATCHADM) tickets and comment and vote on the ones that you are interested in.  Github is for social coding: if you want to write code, we encourage contributions through pull requests from [forks of this repository](http://help.github.com/forking/).

