## Github Contributions Bot

Before reading please remember this script was made for educational purposes. 
Github-Commit is a tool that can give you fake contributions to your github account by making fake commits. 

We Take The Following Inputs:

         Number Of Commits -   To Generate That Amount Of Fake Commits
         Repository URL    -   To Push And Pull Code To/From That Repository
                               (Must be from the account You Want To Increase Contributions)
         Github Username   -   Sometimes Github Asks For UserName (Enter A Real One) ...
         Github Email      -   Sometimes Github Asks For Email (Enter A Real One) ...

We Never Keep You Github Username, Email or Password...
If you do not trust us to push the repository ourselves you may do it yourself, after a successful commit run command:
```git push -u --force origin master```

# Requirements

- An empty repository
- Any Linux Terminal
- python2 and git must be installed
	For Linux```sudo apt-get python git```
	For Termux```pkg install python2 git```

- ProgressBar2 must be installed
Run ```pip install progressbar2```
Or  ```easy_install progressbar2```

- An Internet Connection
- Basic Knowledge Of Using Git

# How To Install

To USE the script type the following commands

```git clone https://github.com/cakecable/Contribution-Bot.git```

```cd github-commit```

```python2 bot.py```

Now the Script Will Execute..

# NOTE
 NOTE: It is Only For Educational Purposes.

- ALWAYS USE AN EMPTY REPOSITORY WITH AN INITIAL COMMIT FOR COMMIT BOT

- REMEMBER TO ENTER CORRECT USERNAME AND PASSWORD WHEN THE BOT IS PUSHING YOUR REPO TO GITHUB
    - AN INCORRECT PASSWORD OR USERNAME COULD LEAD TO LOSS YOUR COMMITS BY BOT, UNLESS PROPERLY HANDLED
   
- If you want To Increase Commits of a non-empty repo:
  - Backup Your Code To Another Place
  - Make Sure Repository Size Is Not Too Big
   
[*]If You Don't See Your Commits/Contributions in Github Site:
   [-] Go Into test Directory inside Github-bot directory
   [-] Push the Code With ```git push -u --force origin master```


 Github-Commit Was Created By cake
