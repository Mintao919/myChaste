# A template user project for use with Chaste.

You now simply log in to github, then click the big green "Use this template" button to use a copy of this repository as the basis of your own new repository under your github username/organisation (this 'template' status avoids complications with forks all being linked back to this repo).

Alternatively, if you aren't a github user, you can download a zip (see Releases button) and start your own repository with that.

Then see the [User Projects](https://chaste.github.io/docs/user-guides/user-projects/) guide page on the Chaste website for more information.

If you clone this repository, you should make sure to rename the template_project folder with your project name and run the 'setup_project.py' script to avoid conflicts if you have multiple projects.

Altenatively: change the project names within Cmakelists.txt and choose the suitable modules for compiled this project, and add the test into teh ContinuousTestPack.


Add TestCommandLineVertexMeshTutorial.hpp with two parameters as argument along with a simple .sh file based on Jack's files. The Commandline relavent files have been sucessfully run.

The next step: change time step sizes for running simulations

Then running simulations to collect data within python file, connected with GP stuffs.