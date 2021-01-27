# arches-data
Arches data packages, branched by version.


After cloning down this repo, check available package branches with:

    git branch -a

    e.g.

      C:\Development\repos\arches-data>git branch -a
      * main
        remotes/origin/HEAD -> origin/main
        remotes/origin/sheep50x 
        remotes/origin/sheep510  
        remotes/origin/sheep51x  
        remotes/origin/main
      
From here, the desired package branch can be downloaded in the arches-data directory with:
    
    git checkout -b <local_branchname> <origin/branchname>
    
    e.g.
    
      C:\Development\repos>cd arches-data
    
      C:\Development\repos\arches-data>git checkout -b kh_fooBranch origin/sheep51x
    

Alternatively, if branch is known, then both cloning and package choice can be completed with:

    git clone -b <branchname> https://github.com/HistoricEngland/arches-data.git
    
    e.g.
    
      C:\Development\repos>git clone -b sheep510 https://github.com/HistoricEngland/arches-data.git


Note: Branches are protected as it is not anticipated that data changes will be made to the packages.
      New packages should be added as new branches when available.
