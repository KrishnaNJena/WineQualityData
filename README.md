Create Environment

'''bash
conda create -n wineeqnew python=3.7 -y
'''


Activate
'''bash
activate wineeqnew
'''

Create new requirements and install
'''bash
pip install -r requirements.txt
'''

Download Data WineQuality Dataset

git init

dvc init

dvc add data_given/WineQality.csv

git add .

git commit -m "first Commit"
