git pull
git remote -v
git remote add upstream git@github.com:vfarcic/k8s-specs.git
git remote -v
git fetch upstream
git checkout master
git merge upstream/master
