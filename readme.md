# create rep
echo "# test2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/OtabekQarshiboyev/test2.git
git push -u origin main

# git push all files
git remote add origin https://github.com/OtabekQarshiboyev/test2.git
git branch -M main
git push -u origin main

# test code
git status
git add -A
git add .
git status
git commit -m "first commit"

git config

git config user.email 0212otabek@gmail.com
git config user.name OtabekQarshiboyev
  
git config --global user.email "you@example.com"
git config --global user.name "Your Name"

git config --local user.email "you@example.com"
git config --local user.name "Your Name"
