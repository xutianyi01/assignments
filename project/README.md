## Project

The project is an open-ended investigation into an NLP problem.

Project guidelines:

- The data used should be as raw as possible. E.g., you may not simply download a pre-processed dataset from the UCI repository.
- The groups may be up to size 2.
- Sample projects can be found [here](https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1194/project.html) or by reading recent papers published in ACL, the top computational linguistics conference: <https://www.aclweb.org/anthology/volumes/2020.acl-main/>
- You may use existing libraries (e.g., nltk, TensorFlow, theano), but your project should be your own.
- Any data needed for your project should be downloaded by the `nlp dl-data` command.
- After the Proposal survey is submitted (see below), a new private repository will be created for your group.
- See the [sample project repo](https://github.com/tulane-cmps6730/sample-project) for how your project will be structured.

### Proposal
Complete this survey, **one per team**, to submit your propsal:

<https://forms.gle/oSBmY7kjsop2mR3Y8>

You will specify the following:

1. Problem Overview: Describe the problem you are solving; what makes it interesting?
2. Data: Which data will you use? How will you collect it? What problems do you anticipate?
3. Method: What method or algorithm will you use? Will you use an existing library to do so? Do you plan to modify the code at all?
4. Related Work: List at least 5 references (with links) to research papers that are related to your project (use Google Scholar to search).
5. Evaluation: How will you evaluate your results? What baseline method will you compare against? What are the key plots or tables you will produce? What performance metrics will you use? What descriptive evaluation will you do (e.g., look at specific predictions made by your system; visualizations)?

Once you've submitted the form, I will create github repositories for each team, with the appropriate access.

### Milestone

Your project milestone report will be 2 - 3 pages using the provided template in the `report` folder of your project repository. This is essentially a first draft of your final project, with many of the core results missing. The following is a suggested structure for your report:

1. Title, Author(s)
2. Problem Overview: Describe the problem you are solving. State it as precisely as you can.
3. Data: Which data are you using; how did you collect it?
4. Method: What method or algorithm are you using. Are you using an existing library to do so? Did you introduce any new variations to these methods? How will you evaluate the results? Which baselines will you compare against?
5. Intermediate/Preliminary Experiments & Results: State and evaluate your results up to the milestone
6. Related work: Summarize at least five related research papers related to your project. How is your project similar/different?
7. Division of Labor: State which group member is responsible for which aspects of the project.
8. Timeline: What are the remaining steps you plan to complete, and when do you plan to complete them?
9. References: list of references cited in your report.


Compile and push to `report/report.pdf` in your project repo.

### Report

A 6-8 page summary of your project. Examples are [here](http://nlp.stanford.edu/courses/cs224n/).

1. Title, Author(s)
2. Abstract: It should not be more than 300 words. What did you do and what was the main conclusion?
3. Introduction: Describe the problem precisely and why it is important.
4. Background/Related Work: Summarize at least five related research papers related to your project. How is your project similar/different?
5. Approach: What method or algorithm are you using. Are you using an existing library to do so? Did you introduce any new variations to these methods? This section details the framework of your project. Be specific, which means you might want to include equations, figures, plots, etc
6. Experiment: What kind of experiments did you do; what kind of dataset(s) you're using; what baseline method are you comparing against; and how you will evaluate your results. Report the results of your experiments in detail, including both quantitative evaluations (show numbers, figures, tables, etc) as well as qualitative evaluations (show images, example results, example errors, etc).
7. Conclusion: What have you learned? Suggest future ideas.
8. References: list of references cited in your report.

Compile and push to `report/report.pdf` in your project repo.

### Presentation

A **maximum** ten minute presentation summarizing your project, following a similar template as the report. Use the `docs/` folder of your project to make your slides using Markdown. The slides should be visible at https://tulane-cmps6730.github.io/project-alpha, where `project-alpha` is your project name.


### Grading

The project is worth 100 points total, consisting of:
- Proposal (10%)
- Milestone (15%)
- Report:
  - Clarity, related work, discussion (15%)
  - Technical correctness and depth (15%)
  - Evaluation and results (15%)
- Project presentation (15%)
- Code quality and thoroughness (15%)

