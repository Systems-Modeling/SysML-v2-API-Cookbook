# SysML-v2-API-Cookbook
The SysML v2 API Cookbook repository is a collection of API recipes to demonstrate patterns and examples for using the [SysML v2 API & Services](https://github.com/Systems-Modeling/SysML-v2-API-Services).

In the current release, the cookbook contains recipes that use the SysML v2 REST/HTTP API (PSM). Each recipe is a [Jupyter notebook](https://jupyter.org/) with a sequence of API calls to the SysML v2 REST/HTTP API. 

## Description of recipes

### Requirement, Structure, Behavior decomposition recipe
This recipe shows patterns and examples for navigating the decomposition of requirements, structure, and behavior elements using the SysML v2 API. The SysML v2 meta-model has harmonized the concepts related to element decomposition and the same concepts are used when decomposing requirements, structure, and behavior releated elements. This recipe shows the use of a common recursive function to navigate the decomposition of requirements, structure, and behavior elements.

See the Jupyter notebook **Req_Str_Beh_Decomposition_Recipe.ipynb** for details.

### Project, Commit, Branch, and Tag recipe
This recipe shows patterns and examples for fetching and creating commits, branches, and tags in a project. It shows an example scenario for SysML v2 project evolution over time with concurrent users working on different branches, creating new commits, and creating tags for baseline or milestone releases of the project.

See the Jupyter notebook **Project_Commit_Branch_Tag_Recipe.ipynb** for details.

### Queries recipe
This recipe shows patterns and examples for formulating and executing queries in a project.

See the Jupyter notebook **Project_Commit_Branch_Tag_Recipe.ipynb** for details.
