
# EGramProject

Add remote to your project directory:
git remote add origin "https://github.com/Yash-Ainapure/EGramProject.git"

Follow these steps before starting your  work on the codebase:
1) Fetch the project 
2) Rebase or Merge
(Use Rebase Highly Recommended)
when you have no additional changes and just want the remote changes you can use  <b>merge</b>, but if there are any local  changes that use <b>REBASE</b>


## Rebase steps :
- Fetcher side:-
  1) git fetch origin main or git fetch
  2) git add .
  3) git commit -m "message"
  4) git rebase origin/main or git rebase (if origin already set)

## Merge Steps :
- Fetcher side:-
  1) git fetch origin main or git fetch
  2) git add .
  3) git commit -m "message"
  4) git merge origin/main or git merge (if origin already set)

## Push remote steps :
- Pusher side:-
  1) git add .
  2) git commit -m "message"
  3) git push origin or git push



# Rules for Project 
## 1) Add Comments  in every file where necessary.

Give both starting and ending comment of a block, so that it is easy for others to understand what you are doing.
//Nabar Started
//Navbar Ended

Add Comments in HTML , CSS , JS and PHP files

## 2) Follow proper indentation and coding style
## 3) Use Proper Keywords while writing functions, classes ,id etc.
## 4) Don't Work on Same File at a time to AVOID MERGE CONFLICTS
## 5) In CSS don't create additional extra colors anywhere use the colors in :root selector and follow the theme 
    IF there is need to of some new color add it in :root with proper naming so that it is easy to understand what that color does

    
    :root{
         --primary-color: #007bff;
    }
    how to access color:
    h1{
      color: var(--primary-color);
    }


## 6) Always keep your code clean by removing unnecessary lines / comments / spaces

