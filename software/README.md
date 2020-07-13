# Software 

## Linux Productivity
- If you are a beginner then you must go through [Linux Journey](https://linuxjourney.com/) website. It is an intutive website which covers all basic commands.
- [Great linux productivity tips: "Missing Semester" from MIT](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J) is good for people who likes video lecture. After doing this course you will have a good working knowledge about Linux.
- [Org Mode Intro: Execellent note taking tool in emacs](https://www.youtube.com/watch?v=S4f-GUxu3CY&t=121s)
- [Tiling Window Managers: Tmux for all windows beyond the terminal!](https://www.youtube.com/watch?v=j1I63wGcvU4&list=PL5ze0DjYv5DbCv9vNEzFmP6sU7ZmkGzcf)

## Open Source Contributions with Git

### Making a contribution
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

**Resources:** [Link](https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940)

### Creating a new contribution to the same repo
1. Delete the old fork (if the master is ahead of your fork).
2. Create a new fork and do all changes there.
3. Create a Pull Request and repeat above steps.
4. Thats it!

### Courses
- [Introduction to Git and GitHub](https://www.coursera.org/learn/introduction-git-github#syllabus) 
This is a highly recommended course for anyone new to Git. It also covers a few advanced topics. 

This is an oversimplified way of contributing.
For more advanced usage, we can use branches and commands like adding upstream url and doing `git fetch`. Please read about these concepts online. Some great explanations can be found [here](https://gist.github.com/Chaser324/ce0505fbed06b947d962) and [here](https://stackoverflow.com/questions/7244321/how-do-i-update-a-github-forked-repository). They're a must read for everyone.
