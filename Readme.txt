mkdir test
git init
vim Readme.txt

# dhanraju - dhanraju cloned dhanuhangout/test repo and named it as
# cloned_dhanuhangout. Below lines are used to clone existing repo of
# dhanuhangout.
mkdir dhanraju_proj
cd dhanraju_proj
git init
git config user.name dh****ju
git config user.email dh*******.**ju@gmail.com
git clone https://github.com/dhanuhangout/test cloned_dhanuhangout
# now the cloned folder got created.
cd cloned_dhanuhangout
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
