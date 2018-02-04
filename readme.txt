cd ~/projects

mkdir -p ip-tsp

cd ip-tsp

virtualenv -p python3 env

source env/bin/activate

python -V

pip install -r requirements.txt

...

deactivate
