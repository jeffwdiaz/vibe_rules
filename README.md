# Vibe Rules

A collaborative platform where communities, creators, and individuals can showcase, share, and discover community rules and guidelines. Whether you're running a Discord server, managing a social media community, or organizing an event, Vibe Rules helps you create, display, and share your community's principles in a beautiful and engaging way.

# Git Knowledge
Follow this guide to learn the basics of using github.

<br>

## 1. Clone this repository

Open the cmd line and use `cd` to change directory to the path where you want to clone the repo.    
`cd ~/REPLACE-WITH-PATH`  

When in the directory you want to clone  
`git clone https://github.com/jeffwdiaz/vibe_rules.git`

## 2. Make a change to the repository

Change your directory to the cloned repo and make a folder with your username.
`cd vibe_rules`  

Make a folder with the format first_last  
`mkdir first_last`

Put your rules, prompts, guidelines, etc. inside.  

Good Examples:  
`jeff_diaz/global_rules.mdc`  
`jeff_diaz/image_prompts.txt`  

Bad Example:  
`my_prompting_technieques/.cursor/.rules/global_rules.mdc`

## 3. Stage > commit > pull request

Change to the main branch  
`git checkout main`

Sync your clone with the main repository  
`git pull origin main`

Create your branch  
`git checkout -b "YOUR_USERNAME-rules"`

***Commit regularly as you complete tasks by using the following workflow.***  

Stage your rules  
`git add .`  
Commit your staged files  
`git commit -m "added YOUR_USERNAME rules"`  
Create a copy of your branch in main once  
`git push --set-upstream origin YOURUSERNAME/rules`  
Push to github  
`git push` 

< - - STILL FIXING BELOW - - >  
< - - STILL FIXING BELOW - - >  
< - - STILL FIXING BELOW - - >  
< - - STILL FIXING BELOW - - >  

Merge into main when finished
git checkout main
git pull origin main
git merge feature/example
git push origin main

4. Nice to do: Write a short description at the top of the rules that describe the ruleset.

![Github cheat sheet](https://github.com/jeffwdiaz/vibe_rules/blob/main/images/git_cheat_sheet.png "Github Cheat Sheet")

## License

MIT License 

Github workflow after you have created and linked your local and remote repositories.
Bold = basic workflow (just use this if starting)
Unbold = more professional workflow?
Using Git While Working on the Search Integration Feature
Create a new branch
git checkout main
git pull origin main
git checkout -b feature/search-integration
Commit regularly as you complete tasks
git add .
git commit -m "Checkpoint 6: Connected search bar to endpoint"
Test the feature locally before merging
Merge into main when finished
git checkout main
git pull origin main
git merge feature/example
git push origin main
Delete the feature branch if no longer needed
git branch -d feature/search-integration
git push origin --delete feature/search-integration
