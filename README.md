# SSC_GIT_DEMO

## Step 1
Open Your IDE Of Choice (VS CODE For Example)

## Step 2
Open A Directory Where You Want To Save This Demo (I use a folder called working_directory)

## Step 3
Clone This Repository Using SSH
<br><br>
This can be done by clicking the Code button on the top right of this repo on GitHub, copying the url shown and then using the command 
> git clone git@github.com:arron-ritchie/SSC_GIT_DEMO.git

in the terminal window of your IDE. 

**NOTE:** You will be asked to provide a password to access this repo if you set one up for your SSH KEY earlier.

## Step 4
Create a new branch with your name as the name of the branch. 
<br><br>
This can be done by using the command 
> git checkout -b *YOUR NAME HERE*-branch

in the terminal window of your IDE. (e.g git checkout -b arron-branch)

## Step 5
Open the file called my_favourite_food.txt and replace "My Favourite Food: Garlic Chili Chicken Curry" with "My Favourite Food: *Your Favourite Food* and save the file. 

## Step 6
Run the following command in your IDE terminal window 
> git add .

This will add all of the changes you have made to the staging area.

## Step 7
Run the following command in your IDE terminal window
> git commit -m "*YOUR MESSAGE HERE*"

e.g. (git commit -m "added arrons favourite food")
<br><br>
This commit message is there to provide information about what changes have occured, in this case that my favourite food was updated. 

## Step 8
Run the following command in your IDE terminal window
> git push

and enter your password when prompted.

## Step 9
Go back to GitHub.com and in the SSC_GIT_DEMO repo go to the tab marked "Pull Requests" and click the green button marked "New Pull Request" 

## Step 10
Near the top of the screen you will see two drop down menus one saying **"base:main"** and the other saying **"compare:main"** click the dropdown marked "compare:main" and select the branch you created earlier. 
<br><br>
You may see "Able to merge. These branches can be automatically merged." when you select your branch or you may see something different. Both are ok and you should proceed to Step 11. 

## Step 11
Give your Pull Request a title, preferably one which describes what changes you have made and leave a comment if you want to go into more details. This is useful when working with teams when you may have lots of information to convey to team members, the click the button marked "Create Pull Request"
<br><br>
If you can't remember what changes you've made scroll to the bottom of the page to see the changed files. 

## Step 12
Your Done - You now get to sit and watch Arron act as the Code Protector and handle the pull requests you've created. 
