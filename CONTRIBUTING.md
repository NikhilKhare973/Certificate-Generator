
**1.**  Clone your forked copy of the project.

```
git clone https://github.com/<your_user_name>/certificate-generator.git
```

**2.** Navigate to the project directory :file_folder: .

```
cd certificate-generator
```

**3.** Add a reference(remote) to the original repository.

```
git remote add upstream https://github.com/vedant-jain03/certificate-generator.git 
```

**4.** Check the remotes for this repository.

```
git remote -v
```

**5.** Always take a pull from the upstream repository to your master branch to keep it at par with the main project(updated repository).

```
git pull upstream main
```

**6.** Create a new branch.

```
git checkout -b <your_branch_name>
```

**7.** Perfom your desired changes to the code base.

**8.** Track your changes:heavy_check_mark: .

```
git add . 
```

**9.** Commit your changes .

```
git commit -m "Relevant message"
```

**10.** Push the committed changes in your feature branch to your remote repo.

```
git push -u origin <your_branch_name>
```

**11.** To create a pull request, click on `compare and pull requests`.

**12.** Add appropriate title and description to your pull request explaining your changes and efforts done.

**13.** Click on `Create Pull Request`.


**15** Voila :exclamation: You have made a PR to the awesome-javascript-projects :boom: . Wait for your submission to be accepted and your PR to be merged.
