Basic Command
-------------------------
cd 
pwd  - print working directory
mkdir
cp index.html ../../index-copied
rm
touch -update timestamp of file (or create if it doesnot exist)
open  .   - open folder, dot represent current directory
ls    - list file in the current directory
History  - using upand down arrow keys to navigaye


Git and GitHub
-------------------------
- Create a new repos on command line
touch README.md
git init
git add README.md - dot (every file)
git commit -m 'my first file'
git remote add origin "http.xx.git"
git remote -v   (get remote verify)
git push origin master

git clone  'htto.xx.git' my project



Web 's Scaffolding tool for modern webapps
-------------------------
npm install -g yo
npm install -g generator-refactoru-html

mkdir projectName
cd projectName
yo refactor-html   // to create whatever file such html,jquery,underscore

// it will ask you to create
