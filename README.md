# SysML-v2-API-Cookbook
The SysML v2 API Cookbook repository is a collection of API recipes to demonstrate patterns and examples for using the [SysML v2 API & Services](https://github.com/Systems-Modeling/SysML-v2-API-Services).

In the current release, the cookbook contains recipes that use the SysML v2 REST/HTTP API (PSM). Each recipe is a [Jupyter notebook](https://jupyter.org/) with a sequence of API calls to the SysML v2 REST/HTTP API. 

## Description of recipes

### Requirement, Structure, Behavior decomposition recipe
This recipe shows patterns and examples for navigating the decomposition of requirements, structure, and behavior elements using the SysML v2 API. The SysML v2 meta-model has harmonized the concepts related to element decomposition and the same concepts are used when decomposing requirements, structure, and behavior releated elements. This recipe shows the use of a common recursive function to navigate the decomposition of requirements, structure, and behavior elements.

See the Jupyter notebook **Req_Str_Beh_Decomposition_Recipe.ipynb** for details.

### Requirement, Structure, Behavior decomposition recipe for Spacecraft example
This notebook shows the use of the Requirement, Structure, Behavior decomposition recipe (above) for a Spacecraft example. 

See the Jupyter notebook **Req_Str_Beh_Decomposition_Recipe_Spacecraft_Example.ipynb** for details.

### Project, Commit, Branch, and Tag recipe
This recipe shows patterns and examples for fetching and creating commits, branches, and tags in a project. It shows an example scenario for SysML v2 project evolution over time with concurrent users working on different branches, creating new commits, and creating tags for baseline or milestone releases of the project.

See the Jupyter notebook **Project_Commit_Branch_Tag_Recipe.ipynb** for details.

### Element Create, Update, Delete recipe
This recipe shows patterns and examples for creating, updating, and deleting elements in project commits.

See the Jupyter notebook **Element_Create_Update_Delete.ipynb** for details.

### Element Owned Elements recipe
This recipe shows patterns and examples to fetch the owned elements (immediate and recursive) for a given element in a given commit of a project.

See the Jupyter notebook **Element_Owned_Elements.ipynb** for details.

### Queries recipe
This recipe shows patterns and examples for formulating and executing queries in a project. Examples show queries with multiple constraints.

See the Jupyter notebook **Queries.ipynb** for details.




