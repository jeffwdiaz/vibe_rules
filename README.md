# Vibe Rules

A collaborative platform where communities, creators, and individuals can showcase, share, and discover community rules and guidelines. Whether you're running a Discord server, managing a social media community, or organizing an event, Vibe Rules helps you create, display, and share your community's principles in a beautiful and engaging way.

# Instructions

1. Clone this repo.

Open the cmd line

cd ~/yourfolder                             # move to the folder where you want it, ex: yourfolder
git clone https://github.com/jeffwdiaz/vibe_rules.git

2. Make a folder with your username.

cd vibe_rules                              # change your directory to the cloned repo
mkdir YOURUSERNAME                             # make your folder

3. Put your rules inside of a folder that is named after your github username.
    Good Example: jeffwdiaz/global_rules.mdc
    Bad Example: jeffwdiaz/.cursor/.rules/global_rules.mdc

4. Stage, commit and push/pull request.

Create a new branch
git checkout main                                  # make sure your on the main branch
git pull origin main                                # sync your clone with the main repository
git checkout -b "YOURUSERNAME/rules"                # make your branch

Commit regularly as you complete tasks
git add .                                           # stage your rules
git commit -m "added YOURUSERNAME rules"            # commit your staged files
git push --set-upstream origin YOURUSERNAME/rules   # create a copy of your branch in main once
git push                                            # push

Merge into main when finished
git checkout main
git pull origin main
git merge feature/example
git push origin main

4. Nice to do: Write a short description at the top of the rules that describe the ruleset.

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
