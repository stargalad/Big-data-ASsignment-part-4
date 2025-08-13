# Big-data-ASsignment-part-4
1) Environment (Python 3.10+)
python -m venv .venv
source .venv/bin/activate   
pip install -r requirements.txt

2) view on any platform -
   ctrl + R - to run the code and view outputs
Alternate way
 3) Evaluate + plots
python src/evaluate.py --config configs/config.yaml --split test
python src/plot_curves.py --config configs/config.yaml --out figures/
python src/plot_importance.py --config configs/config.yaml --out figures/
