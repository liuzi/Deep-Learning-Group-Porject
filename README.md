# Deep-Learning
#### 1.Clone remote repo to your local, you can firstly enter the folder for saving this repo: cd $your_folder
```
##[User_name@current_dir]$ cd your_dir
[User_name@current_dir/your_dir]$ git clone https://github.com/liuzi/Deep-Learning-Group-Porject.git
[User_name@current_dir/your_dir]$ cd Deep-Learning-Group-Porject/
```
#### 2.Pull remote repo to update changes in your local repo
```
[User_name@Deep-Learning-Group-Porject]$ git pull
```
#### 3.create a new branch and switch to it, any name for branch is acceptable
```
[User_name@Deep-Learning-Group-Porject]$ git checkout -b $your_branch_name
## or you can firstly 'git branch branch_name' and then "git checkout branch_name"
```
#### 4.Add your changes
```
[User_name@Deep-Learning-Group-Porject]$ git add .
[User_name@Deep-Learning-Group-Porject]$ git commit -m "test" 
## this step may lead you to a editing file, enter whtatever you want and save it
```
#### 5.push your branch to remote repo
```
git push origin $your_branch_name
```
#### 6.create pull requests and merge your branch to master
>Then your can refresh the github page of this repo in your browser and enter your branch link on the top of the page, enter buttons to create pull requests and merge your branch into the master. After merging, you can delete your branch


