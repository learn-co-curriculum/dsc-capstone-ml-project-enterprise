# Capstone Project Description

One last project to go before graduation!

In this project description, we will cover:

* Project Overview
* Deliverables

## Project Overview

For the Capstone project, you and your team members will engage in one more **supervised machine learning** process from start to finish. The choice of topic, dataset, target, and type of model is yours.

### Business Problem and Data

You are responsible for identifying an appropriate business problem and dataset. Be sure that you choose a dataset that is publicly available to ensure that you are not sharing any sensitive information. For this project **your group must utilize supervised machine learning**. Other components like unsupervised learning and data dashboards may be part of the overall process but are not sufficient to pass this project.

In other words, you need to find a business problem where you can frame the question as:

> Using `data`, can we predict `target`? This would be useful because `rationale`.

Let's break that question down further:

1. **Data:** What are the *inputs* to your model? Think about the contexts where this information would be available
2. **Target:** What is your model trying to *predict*? Is this something that would realistically be unknown in a context where the above features are known?
3. **Rationale:** Why would it be valuable to be able to predict this target? Who would find this model useful? How accurate does the model need to be in order to serve the stated purpose?

Other questions like "what is the relationship between `a` and `b`" or "how much does `c` factor into `d` outcomes" may be incidentally possible, but make sure you have that predictive framing first.

### Key Points

#### Project Management

Project management is key. You have a lot of freedom in this project - this can feel liberating, but also means that you can accidentally lose a lot of time if you're not careful. Map out a rough daily project plan with key milestones and due dates for deliverables - you can adjust this as needed as you progress. And make sure to coordinate with your team members about who's responsbile for what! Use this to make sure you're making timely progress towards successful completion. Ask for help if you find yourself struggling to keep up with your plan.

## Deliverables

At this point, the project deliverables should be familiar:

* A **non-technical presentation**
* A **Jupyter Notebook**
* A **GitHub repository**

The checklist of requirements is similar to what you saw previously as well.

### Non-Technical Presentation

As a reminder, the graded elements of the presentation are:

- Presentation Content
- Slide Style
- Presentation Delivery and Answers to Questions

### Jupyter Notebook

Feel free to make multiple notebook as you explore data and models. Just make sure that there is one final notebook that is clearly designated as such for grading.

As a reminder, the graded elements of the notebook are:

- Business Understanding
- Data Understanding
- Data Preparation
- Modeling
- Evaluation
- Code Quality

### GitHub Repository

Ensure that it contains accessible, inviting, professional content.

#### Overall Repository Requirements

As a reminder, a professional GitHub repository has:

1. `README.md`
    * A file called `README.md` at the root of the repository directory, written in Markdown; this is what is rendered when someone visits the link to your repository in the browser
2. Commit history
   * Progression of updates throughout the project time period, not just immediately before the deadline
   * Clear commit messages
3. Organization
   * Clear folder structure
   * Clear names of files and folders
   * Easily-located notebook and presentation linked in the README
4. Notebook(s)
   * Clearly-indicated final notebook that runs without errors
   * Exploratory/working notebooks (can contain errors, redundant code, etc.) from all team members (if a group project)
5. `.gitignore`
   * A file called `.gitignore` at the root of the repository directory instructs Git to ignore large, unnecessary, or private files
     * Because it starts with a `.`, you will need to type `ls -a` in the terminal in order to see that it is there
   * GitHub maintains a [Python .gitignore](https://github.com/github/gitignore/blob/master/Python.gitignore) that may be a useful starting point for your version of this file
   * To tell Git to ignore more files, just add a new line to `.gitignore` for each new file name
     * Consider adding `.DS_Store` if you are using a Mac computer, as well as project-specific file names
     * If you are running into an error message because you forgot to add something to `.gitignore` and it is too large to be pushed to GitHub [this blog post](https://medium.com/analytics-vidhya/tutorial-removing-large-files-from-git-78dbf4cf83a?sk=c3763d466c7f2528008c3777192dfb95)(friend link) should help you address this

#### README Deep Dive

The README is the "home page" of your Capstone project. Other than the *Attention to Detail* objective, all rubric objectives for this project will focus on the README.

Ideally, your README should include:

1. A **project title**
    * Choose a title that reflects the project domain and presents you as a data scientist, not as a student. The title should not include words like "capstone" or "school"
    * Some title formats to consider:
       * "Predicting `target`"
       * "`target` Prediction"
       * "`target` Detection"
       * "Classifying `target`"
       * etc.
    * Feel free to add "with `data`" or "using `data`" to the end of any of those. For example, *Detecting Fake Reviews with NLP* or *Classifying Skin Lesions Using Neural Networks*
    * You also might want to start the title with a catchy phrase or quote, followed by a more-standard title. For example, *Where To, First?: an Airbnb Destination Predictor* or *Stay in Your Lane! Automated Bike Lane Enforcement*
      * You can always add this element later, so don't get hung up on it if you can't think of something right away! Just start with the straightforward title
2. An **elevator pitch**
    * Immediately after the title, write a very short description of the problem you are solving, the data you are using to solve it, and how well your model solves the problem
    * This should be no more than a couple of sentences
3. A **header image**
    * This image can be anything you want, so long as it is professional and aligns with your project
    * Ideal dimensions are 1280x640 pixels, but any image with landscape orientation (wider than it is tall) will work
    * Image sourcing ideas to consider:
      * Use a stock image from a source like [Wikimedia Commons](https://commons.wikimedia.org/wiki/Main_Page) or [Unsplash](https://unsplash.com/)
         * Make sure you double-check the usage license and attribution requirements
      * Create visualizations with code (Matplotlib, Seaborn, etc.)
    * As a reminder, the Markdown notation for an image is `![alt text](path/to/image.png)`
4. **Business Understanding and Data Understanding**
    * Explain the project context, using at least one citation to demonstrate your domain understanding
    * Consider including visualizations here as well
5. **Modeling and Evaluation**
    * What kind of model(s) did you use?
    * How well did your final model perform, compared to the baseline?
6. **Conclusion**
    * How would you recommend that your model be used?
7. **Repository Navigation**
    * An explanation of the repository organization
    * Links to the final notebook and presentation
    * Reproduction instructions (or a link to them)


### Getting Started

Please start by reviewing the contents of this project description. If you have any questions, please ask your instructor ASAP.

To get started with project development, create a new repository on GitHub. For this project, we recommend that you do not fork the template repository, but rather that you make a new repository from scratch, starting by going to [github.com/new](https://github.com/new).

## Summary

This is your final project in the DS program, the "crown jewel" of your portfolio. Let's do this!
