# find-close-meteorites
A Demo Project that uses Python


Running Command line
'python3 find_meteors.py'



pip3 install requests
python -m pip install --upgrade pip
pip3 install requests
pip3 install pipenv
pipenv --three
pipenv shell
-- exit
pipenv run python find_meteors.py
pipenv install requests
pipenv run python find_meteors.py


git status
git add find_meteors.py README.md
git status
git commit (:q to quit)
git commit -m "Added find_meteors.py file and modified the Readme file"
git push
git push origin master


git add .gitignore README.md Pipfile
git commit -m "Use pipenv to manage dependecies"
git push
mkdir meteors

git mv find_meteors.py meteors/
pipenv run python meteors/find_meteors.py

git add README.md
git commit -m "Moved file to meteors directory"
git push


git log (press q to quit)
pipenv install -d ipython

pipenv run ipython
from meteors import find_meteors
find_meteors.calc_dist(0,0,5,5)
