unalias python
conda activate xgb214  

conda install --file requirements.txt 

python -c "import xgboost; print(xgboost.__version__)"