# Open Source Contributions with Git

## Making a contribution
1. Fork the repo which you want to work on (eg. https://github.com/take2rohit/sih_number_plate is original repo where you want to contribute) 
2. Clone the forked repository from your own profile (**NOT** the original repository)
`git clone https://github.com/your_userid/sih_number_plate`
3. Do the changes and commit.
`git add file1 file2`
`git commit -m "Adding my contribution"`
4. Push changes to GitHub. This updates your forked repo.
`git push origin master`
5. Create a pull request.
6. If the owner finds your changes correct, he will merge it with his original repo.
7. Congratulations! You just contributed to the original repo.

Resources: [Link](https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940)

## Creating a new contribution to the same repo
1. Delete the old fork (if the master is ahead of your fork).
2. Create a new fork and do all changes there.
3. Create a Pull Request and repeat above steps.
4. Thats it!

This is an oversimplified way of contributing
For more advanced usage we can use branches and commands like adding upstream url and doing `git fetch`. Please read online about these concepts. Some great explanations can be found [here](https://gist.github.com/Chaser324/ce0505fbed06b947d962) and [here](https://stackoverflow.com/questions/7244321/how-do-i-update-a-github-forked-repository). They're a must read for everyone.
