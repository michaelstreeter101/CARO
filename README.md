# CARO
Child Assessment and Reporting Online

Preschool teachers are required to produce reports about the children they look after. There is a lot of paperwork around checklists, the format, what needs to be checked and when, as well as scheduling followup observations. At the end of each term a report needs to be sent to the parents. There is also a standard two-year check.

There is an app to do this already, but the preschools cannot afford the licence. This is a free implementation.

Setup instructions

1. Add a new SSH key to your GitHub account (https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)

2. $ git clone git@github.com:michaelstreeter101/CARO.git (ref: media/books/Version Control with GIT.pdf)
   $ git pull
   $ git branch [branch-name] # e.g. requirements/add_business_rule
   $ git checkout [branch-name] # e.g. requirements/add_business_rule
   ... change file1, filen etc.
   $ git add [file1] [filen] ...
   $ git commit
   $ git push
   $ git pull