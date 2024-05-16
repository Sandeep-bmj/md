# BMJ International Forum
### Key Details:
**Prod GitHub Repository**:   https://github.com/BMJ-Ltd/wp-internationalforum.bmj.com 

**Stg GitHub Repository**: https://github.com/BMJ-Ltd/wp-stg-internationalforum.bmj.com 

**Staging Site**: https://stg-internationalforum.bmj.com  

**Live Site**: https://internationalforum.bmj.com/

## BMJ International Forum Production
This repository, wp-internationalforum.bmj.com, exclusively holds live production data for our internationalforum.bmj.com website. It's important to note that this is a special scenario where we maintain separate data for both staging and live environments.

## How should I begin working in this repository?
If you're starting any work in this repository, it's best to first clone it locally, then switch to the developer branch to make your changes. After modifying any files, add them, commit the changes, and push them to the repository. Once you push the code into the repository, GHA will run automatically, and you can see the changes reflected on the site. This is the current workflow that we are using.

## Below are some useful commands for your reference:
### Clone the repository to your local system.
``` git clone <repo url> ```
### Change directory and navigate inside.
``` cd <diretory-name>```
### Check all branches inside the repository for confirmation.
``` git brach -a ```
### Switch to the branch according to your task.
``` git checkout "<your-branch-name>" ```
### Once your changes are done, you can use the 'add' command. where dot (.) represents the current directory.
``` git add . ```
### Commit your changes with a proper commit message, according to your task.
``` git commit -am "<your-commit-message>" ```

### Push your code or files to the repository.
```git push``` or ```git push --set-upstream origin <your-branch-name> ```

### Navigate to the repository's page and select the 'Actions' tab. Here, you can access your CI/CD pipeline's deployment logs. A green checkmark indicates a successful CI/CD process.






