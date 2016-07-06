mkdir test
git init
vim Readme.txt

# dhanuhangout - created a repo using below commands.
git config user.name dh******out
git config user.email ha*********10@gmail.com
git add .
git commit -m "Adding Readme file"

# Now, create a master branch in github.com website under user dh*******out.
# Then follow below commands.
git remote add origin https://github.com/dh********out/test.git
git push -u origin master
