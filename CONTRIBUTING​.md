# Contributing

:+1::tada: First of all, thanks for taking the time to contribute! :tada::+1:

We welcome all contributions to this project. The contribution can include improvement to the translation or translation to a new language or simply fixing a typo.

By contributing,
you agree that we may redistribute your work under [our license](LICENSE.md).
Everyone involved in this project
agrees to abide by our [code of conduct](CODE_OF_CONDUCT.md).


## Using GitHub


1. Check that there isn't [already an issue](https://github.com/open-life-science/ols3-cohort-talks-and-transcripts/issues) about your idea to avoid duplicating work.
    * If there isn't one already, please create one so that others know you're working on this

2. Fork the [open-life-science/ols3-cohort-talks-and-transcripts](https://github.com/open-life-science/ols3-cohort-talks-and-transcripts) to your GitHub account.

3. Clone the forked repository on your local machine.

 ```bash
 
 git clone https://github.com/<your-local-repo>/ols3-cohort-talks-and-transcripts.git
 
 ```
4. Sync the fork, to avoid merge conflicts. 

```bash

    git remote add upstream https://github.com/open-life-science/ols3-cohort-talks-and-transcripts.git
    git fetch upstream
    git pull upstream master
    git push
    
```

5. Create a new branch with your github username as its name.

 ```bash
 
    git checkout -b <your-github-username>
    
 ```

6. Make the necessary changes / additions within your forked repository.

7. Add and commit changes made.

 ```bash
 
    git add .
    git commit -m "commit message"
    
 ```
8. Push the changes to forked repository.

 ```bash
 
    git push origin <branch-name>
    
 ```

9. Submit a Pull Request against the `master` branch and wait for the code to be reviewed and merged.

If you're not used to this workflow with git, you can start with some [basic docs from GitHub](https://help.github.com/articles/fork-a-repo/).
