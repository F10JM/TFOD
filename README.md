
python -m venv tfod

source tfod/bin/activate # Linux

.\tfod\Scripts\activate # Windows 

python -m pip install --upgrade pip

pip install ipykernel

python -m ipykernel install --user --name=tfodj
