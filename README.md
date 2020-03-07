# Geometry 2020
## Git Command Line Instructions
### First Time Setup
1. Install git for your OS https://git-scm.com/downloads
2. Sign in to git
```
git config --global user.name "Your Name"
git config --global user.email "Your E-Mail"
```
3. Set directory `cd ~/Desktop`
4. Clone Geometry 2020 Repository `git clone https://github.com/SupposeNot/Geometry2020.git`
### Updating Tex File
1. Set directory `cd ~/Desktop/Geometry2020`
2. Pull latest changes to repository `git pull`
3. Make changes to the tex file
4. Add changes to the commit `git add Summary\ of\ Geometry.tex`
5. Commit with useful message `git commit -m "Added Section 1.1"`
6. Push your changes to the repository `git push`

#### Helpful Tips
1. Use tab to autofill file names
2. If you get stuck in VIM press escape key and type `:q`
3. Read the error messages. Git will tell you what to do
4. Run `git status` anytime to see changes to the repository
5. Only run `git clone` once!!!
6. If you forget to pull before you make changes just add and commit changes then run `git pull`. Git will automatically merge files.
7. If you get lost check out a basics tutorial, like this one https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/   

