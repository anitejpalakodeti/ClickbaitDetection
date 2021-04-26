# ClickbaitDetection
An attempt on the Clickbait Detection Challenge by Webis by making use of Glove word embeddings for clickbait prediction

# Clickbait_Detection
https://zenodo.org/record/3346491/files/clickbait17-train-170630.zip?download=1

1. Clone the repository into a directory of your choice
2. `cd ClickbaitDetection` 
3. Set up a virtual environment (venv recommended - `python3 -m venv venv` and `source venv/bin/activate`).
4. Once in venv, run `pip install -r requirements.txt` to install all packages
5. Run `jupyter lab` (with `--no-browser` on WSL). 
6. Run the `PreProcess.ipynb` notebook first to download the data and create the preprocessed Clickbait dataset

Now you can run the embedding notebook, which will automatically download the pretrained embeddings.
