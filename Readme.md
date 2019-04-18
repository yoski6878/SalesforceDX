#Read Me 

## Setup

Terminal
–	pwd                                          // this will show the current directory 
–	cd  Desktop                                  // this will  open desktop directory 
–	mkdir  testfolder                           // this will create a folder to the selected cd, test folder is the                                                                                  name
–	ls                                             // this will show all the folders on the cd you are on  
–	cd testfolder                        // this will take you to the testfolder you created 
–	cd ..                                       // this will take you back one folder back which will be desktop
–	cd Desktop/testFolder       // this will take you directly to the testfolder from desktop inside of using cd twice 
–	touch test.txt                         // this will make a file on the folder selected 
–	rm touch test.txt.                // this will remove the folder. You can use ls to check if its removed
–	rm testfolder                      // this will try to remove folder but you will get is a directory error 
–	rm -rf testfolder                 // this will remove the folder overcoming the error above

Salesforce DX
–	sfdx force:auth:web:login -d -a DefaultHub   // -d this will tell sfdx that we want this to be our default hub org -a  will set an alias 
                                     to the org. DefaultHub is the alias name.  This command will authorize Salesforce org 
–	sfdx force:org:list            // this will list org information  on scratch org and other details 
–	mkdir SalesforceDX     // this will create a folder 
–	cd  SalesforceDX              // this will open  the Salesforce DX folder 
–	sfdx force:project:create -n learnSfdx  // this will create sfdx project on the folder you selected 
–	ls                            // to see files of the folder
–	cd learnSfdx                         // go to the learnSfdx folder
–	sfdx force:org:create -s -f config/project-scratch-def.json -a learnScrachorg   // will create a scratch org with alias name 
–	sfdx force:org:list                                    // will list all scratch org 
–	sfdx force:org:open                                         // will open the scratch org 
–	sfdx force:source:pull                        // will pull anything created on the scratch org 
–	sfdx force:source:push                       // will push any changes made on the code to the scratch org 
–	clear                                                      // will clear everything  you wrote  on terminal 

Git Command 
–	git config —global user.email “your@email.com”                        //set user email with in git 
–	git clone https://github.com/yoski6878/SalesforceDX.git                      // clone git from git 
–	git status                                                                                            // will show untracked changes 
–	git add Readme.md                                                                         // will add the read me file
–	git commit -m "added Read me"                                                   // commits the added git 
–	git push                                                                                              // will push our committed git to git
–	git branch                                                                                         // will show git branch. Will show master branch
–	git  branch readMeUpdate                                                         // this will create a new readMeUpdate branch
–	git branch                                                                                      // will show all the commands 
–	git checkout readMeUpdate                                                          // will switch from master to readMeUpdate git branch 



