# CarpentryWorkshop061216
Software carpentry workshop at the University of Arizona 06/11-12/2016. 
Additional descriptions here. 

How to move file from computer to GitHub in Shell
   1  git clone https://github.com/CWhite27/CarpentryWorkshop061216.git
   2  pwd
   3  ls
  11  cd day_2/ #Move to directory in which file is located. 
  12  ls
  13  cd titanic_data_exploration/
  14  ls
  15  mv titanic_walkthrough.ipynb #File we moved to GitHub. 
  16  cd .
  17  cd ..
  18  ls
  19  mv titanic_walkthrough.ipynb ..
  20  cd ..
  21  ls
  22  mv titanic_walkthrough.ipynb CarpentryWorkshop061216/
  23  cd CarpentryWorkshop061216/
  24  ls
  25  git add titanic_walkthrough.ipynb
  26  git status
  27  git commit -m "Added titanic_walkthrough"
  28  git config --global user.email "Corin.White@ucsf.com"
  29  git config --global user.name "Corin White"
  30  git commit -m "Added titanic_walkthrough"
  31  git status
  32  git push
  33  history
