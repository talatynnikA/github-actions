# github-actions
Task on Github Actions

Main task:
1. Create a new repository on the GitHub platform;
2. Implement GitHub Actions Workflow in the repository, which can be launched by two
   ways:
   a. Manually - by selecting a branch/tag to build and with the ability to specify in a separate field
   build version;
   b. Automatically – after creating a new tag in the repository.
3. Create a local GitHub Action:
   a. Action must take a folder path as an argument;
   b. Using the received path to the folder, action creates a file in which it writes the name
   all files in this folder and child folders;
   c. As a result of execution, action should return the path to the created text file.
4. Workflow should use the created local GitHub Action by transferring the folder from the project;
5. Workflow must create a release and attach the generated file from the previous one to it
   step.