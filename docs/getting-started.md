## Getting Started

Please use the following outline to get started with a new AIOps Data Science Project. If you run into problems or need additional support, please ______.
**where should users go when they need help? slack or somewhere else?**

### Define a Project Document

1. Review our project workflow document [here][1].

2. Create a new project description using our [template][2]. For reference, you can review an example project document [here][3].

3. Put your project document into a subfolder of this [shared directory][4]. 

### Create Git Repository from a Template

Next, create a [CookieCutter][5] formatted data science project repository from this [template][6]. To do so, please follow these [instructions][7] for creating a new repository from a template.

### Set Up AICoE Continuous Integration (CI)

To set up CI for your project repository, follow these steps.

* insert documentation for this here

### Create Project Boards and Issues

Copy this [project board][8] to a new organization level project board including automation. For instructions on how to copy a project board, review [this page][9].

Once your project board is created, begin to create issues and populate the board with them
* Create an issue for every task you plan to work on
    * Break issues down into smaller pieces if they cannot be completed in a timely manner
    * See guidance for issues 
* Add the issues to the *New* column of you project board
    * Provide some sort of acceptance criteria for when the issue can be closed
* When you're almost ready to begin working on an issue, move it to the *To Do* column
* Once you start work on an issue, move it to the *In Progress* column

For more information of the remainder of our GitHub workflow, please visit [this page][10]. 

### Develop on Operate First Jupyterhub

The following resources are available for use to develop your project on Operate First JupyterHub:
* Access the public [JupyterHub instance][11] on the Massachusetts Open Cloud (MOC) by selecting moc-sso and then signing in with your Google Account 
    **not sure if this is correct**
* Monitor workloads using grafana dashboards
* [Troubleshooting Runbooks](https://www.operate-first.cloud/users/sre/runbooks/jupyterhub.md)
* link currrently existing dashboards
* link Espresso video (in progress)

### Managing Dependencies

* create documentation

### Contributing via Pull Requests

* include short description

**does this refer to contributing to other projects that aren't your own? if so, does this belong in how to contribute?**

### Reviewing Pull Requests
The documentation below provides the top principles and guidelines that our team uses to review data science code. 

[Guidlines for Reviewing Data Science Code](docs/guidelines-for-reviewing-datascience-code.md)

**same question as above, does review process apply to users bringing their ds projects?**

### Deliverables

Here are potential ways to contribute and showcase work you have completed.
* Slide decks
* Blog posts
* Videos 

### Creating Jupyterhub Images
JH images can be created for projects.
[Guide](docs/create_and_deploy_jh_image.md)

### Creating Automated Model Workflows

Information on creating automated model workflows and serving models. 
[Video]


[1]: https://docs.google.com/document/d/1LqVXQbd81IdPfoXw2B0iCcnb-ygCVvdy_8vejY08zZ4/edit
[2]: https://docs.google.com/document/d/1CIFlKiVbNX3CKC-tD7kVDkP1S8eDfDEibdLM6jgIj2g/edit
[3]: https://docs.google.com/document/d/1prfyxHAQq60IU_K_f-eTNVCB6FKV2q00YAbmY-jI_HE/edit
[4]: https://drive.google.com/drive/folders/17nhASQZUbGISFQswUb-ft3V1dxbD7dtX
[5]: https://drivendata.github.io/cookiecutter-data-science/#cookiecutter-data-science
[6]: https://github.com/aicoe-aiops/project-template
[7]: https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template
[8]: https://github.com/orgs/aicoe-aiops/projects/2
[9]: https://help.github.com/en/github/managing-your-work-on-github/copying-a-project-board
[10]: docs/how-to-contribute.md
[11]: https://oauth-openshift.apps.zero.massopen.cloud/oauth/authorize?response_type=code&redirect_uri=https%3A%2F%2Fjupyterhub-opf-jupyterhub.apps.zero.massopen.cloud%2Fhub%2Foauth_callback&client_id=system%3Aserviceaccount%3Aopf-jupyterhub%3Ajupyterhub-hub&state=eyJzdGF0ZV9pZCI6ICI0NjQzNjI0NDY5OTY0MmUxOWJhMzM5OTA0ZDZhZDcwZiIsICJuZXh0X3VybCI6ICIvaHViLyJ9&scope=user%3Ainfo
