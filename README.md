# DSCI 524: Collaborative Software Development

How to exploit practices from collaborative software development techniques in data scientific workflows. Appropriate use of the software life cycle, unit testing / continuous integration, and packaging for use by others.

## Learning Outcomes

By the end of the course, students are expected to be able to:
- complete a project that demonstrates appropriate use of collaborative software development processes and tools, including:
    - packaging code for use by others, including the specification of dependencies/requirements
    - using advanced distributed version control workflows and features (e.g., GitHub flow, master branch protection, code reviews, project boards and issue tracking) to effectively manage a multi-person project
    - writing comprehensive test suites
    - carrying out continuous integration via GitHub Actions
    - deploying packaged software using semantic versioning
    - writing clear and helpful documentation
    - selecting software licenses that best suit the project
    - critically evaluating work of others and providing constructive feedback

## Course Format
This is a project-based course where you will work collaboratively in groups to develop a Python and a R software package. In lecture and lab, we'll work on the skills and concepts that you need to learn to complete the project. 

## Teaching Team

| Position | Name  | Slack Handle | GHE Handle |
| :------: | :---: | :----------: | :--------: |
| Lecture Instructor | Tiffany Timbers  | `@tiffany` | `@timberst` |
| Lab Instructor | Varada Kolhatkar | `@varada`  | `@kvarada`  |
| Teaching Assistant | Javier Castillo-Arnemann | `@Javier` | NA |
| Teaching Assistant | Siddhesh Khandelwal  | `@Siddhesh` | NA |
| Teaching Assistant | Andy Tai| `@Andy Tai` | NA |
| Teaching Assistant | Jie Xiang | `@Doris Xiang ` | NA |


*Note: See [Calendar](https://ubc-mds.github.io/calendar/) for office hour location and exact dates.*


## Lecture Schedule
| Lecture  | Topic | Required pre-work | Readings and Resources|
|----------|-------|-------------------|-----------------------|
| 1  | Introduction to collaborative software development (and my goodness more Git!) | <ul><li>[Setting up your system for R packages](https://r-pkgs.org/setup.html)</li><li>[Setting up your system for creating Python packages](https://ubc-mds.github.io/py-pkgs/setup.html)</li></ul> | <ul><li>[GitHub project boards](https://help.github.com/en/github/managing-your-work-on-github/about-project-boards)</li><li>[How To Use Git Branches](https://www.digitalocean.com/community/tutorials/how-to-use-git-branches)</li><li>[GitHub flow](https://githubflow.github.io/)</li><li>[Configuring protected branches](https://help.github.com/en/github/administering-a-repository/configuring-protected-branches) |
| 2 |  Introduction to R & Python packages  | |  <ul><li>[The Whole Game (R)](https://r-pkgs.org/whole-game.html)</li><li>[The Whole Game (Python)](https://ubc-mds.github.io/py-pkgs/whole-game.html)</li></ul> |  
| 3 | Code reviews, integration testing (using `testthat` & `pytest`) & testing complex things (*e.g.,* plots, images) |  |  |
| 4 | Debugging & package documentation |   |  |
| 5 | Continous integration and GitHub Actions |  |  |
| 6 | Versioning & publishing your package on the package indices (CRAN & PyPI) |  |  |
| 7 | Peer review of data science R & Python packages |  |  |
| 8 | Working with other teams (specifications, opening issues, how to ask for help, etc) & Licenses |  |  |


Time and location: Mondays and Wednesdays 10:30am- 11:50am in DMP 110

## Assessment
| Deliverable | % grade | Due date |
|------------|----------|----------|
| Project proposal + Milestone 1 | 20% | 2020-02-29 18:00 |
| Create your own toy R & Python packages (graded for completion) | 3% | 2020-02-29 18:00 |
| Milestone 2 | 20% |  2020-03-07 18:00 |
| Milestone 3  | 20% | 2020-03-14 18:00 |
| Individual Peer review | 15% | 2020-03-21 18:00 |
| Milestone 4 | 20% | 2020-03-26 18:00 |
| Team work reflection (graded for completion) | 2% | 
| Team work multiplier | NA | NA | 

## Labs

| Lab | topic | 
|-----|------|
| 1 | Project Proposal and Milestone 1: Coming up with a topic and setting up package structure |
| 2 | Milestone 2: writing the code and tests for the package  |
| 3 | Milestone 3: Setting up continuous integration and all the other bells and whistles |
| 4 | Peer review |
| NA | Team work reflection |
