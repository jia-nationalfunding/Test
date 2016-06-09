/* CLI */
pwd
clear
ls -a
ls -al
cd
cd Documents
cd..
mkdir Documents
touch test_file /*create an empty file*/
cp test_file Documents /*Copy one file*/

mkdir More_docs
cp -r Documents More_docs /*Copy the contents of directories*/
rm test_file /*remove*/
rm -r More_docts

touch new_file
mv new_file Documents /*Move Files*/
mv new_file renamed_file /*Rename Files*/

echo Hello World!
Date

/*git*/

$ git clone git://git.kernel.org/pub/scm/git/git.git

git config --global user.name "Jia Lu"
git config --global user.email jia@nationalfunding.com

git config user.name
git config --list


git init
git status
git remote add origin https://github.com/jia-nationalfunding/Test.git
git remote set-url origin https://github.com/jia-nationalfunding/Test.git
git help remote
git clone https://github.come/jia-nationalfunding/Test.git

git add . /*add all new files*/
git add (-u) /* updates trakcing for files that changed names or were deleted */
git add (-A) /* does both of the previous */

git checkout -b branchname /*work on branches*/
git branch
git checkout master

git commit -m "Add Changes"
git log --summary

git push (-u) origin master

git diff HEAD

git stash
git stash apply

git reset <filename>
cd /c/Users/jia/Desktop/Git

