  d 888  ,8,"88e                                                                       d8                    
 d8 888   "  888D      e88'888 888 88e  888 88e       e88'888 888,8,  ,e e,   ,"Y88b  d88    e88 88e  888,8, 
d88 888e     88P  888 d888  '8 888 888b 888 888b 888 d888  '8 888 "  d88 88b "8" 888 d88888 d888 888b 888 "  
""" 888"    ,*"       Y888   , 888 888P 888 888P     Y888   , 888    888   , ,ee 888  888   Y888 888P 888    
    888   8888888      "88,e8' 888 88"  888 88"       "88,e8' 888     "YeeP" "88 888  888    "88 88"  888    
                               888      888                                                                  
                               888      888                                                                  

This is a script focuses on helping the 42 students in their cpp proyects. This script was developed between me (jsanfeli in 42 intra) and @RobertoRobrodri
on github (robrodri in 42 intra).

#What it does

CPP Creator recieves the name of the desired cpp class and then proceess to copy from the templates provided the two files required: .cpp and .hpp.
It also generates a very simple makefile.
Then, CPP Creator sets the proper name replacing "Template" with the name you provided.
*This script provides an starting point for your classes. If another template better suits your needs you can always modify the templates from the templates directory

  git clone git@github.com:KiriamBlu/42-cpp-creator.git
  
  cd 42-cpp-template-creator
  
  cd cpptempcreate

  ./cppcreator.sh $Name_of_class

# How to make it work.

There are two ways to execute this script:

  -The first way is just execute:
    
    bash User/$USER/cpptempcreator/cppcreator.sh $Name_of_class
   
  -The recomended way is to add a alias to the scrip to be able to use it anywhere you want:
  
  Go to the root directory and edit the .bashrc file and in the last line add.
  
    alias $Desired_Name='/Users/$USER/cpptempcreator/cppcreator.sh
  
  Then, with the name you chooser for the cmd you can execute the script.
  
  #We recommend to hide the directory with a '.' before the directory name.
  
    
  
    
