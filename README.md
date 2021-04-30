# Is This Fake News? Using machine learning to identify fake news articles

### Live Demo: [www.isthisfakenews.ai](http://www.isthisfakenews.ai) (*NOTE*: this is currently running on a free Heroku instance, so it may take a minute to boot up / for the page to load)

<p float="left">
  <img src="https://github.com/malwaredllc/is-this-fake-news/blob/main/static/images/real-prediction.png?raw=true.png" width="400" />
  <img src="https://github.com/malwaredllc/is-this-fake-news/blob/main/static/images/fake-prediction.png?raw=true" width="400" />
</p>

### How it works:

[Read the paper here!](https://github.com/malwaredllc/is-this-fake-news/blob/main/Final_Report.pdf)

## Running the Research Notebooks

The research notebooks (`/research-notebooks`) were developed on Kaggle, using the [Fake and real news dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset/code). 

To run these yourself:

- Sign into Kaggle.com
- Visit one of the links below to view the noteboook
    - [Multi-layer perceptron](https://www.kaggle.com/danielvegamyhre/fake-vs-real-news)
    - [BERT Fine-tuning](https://www.kaggle.com/danielvegamyhre/classifying-fake-news-with-bert)
- Click the "Copy and edit" button at the top-right (which will launch a Kaggle notebook instance containing this code with the dataset ready to go)
- Run the notebook (*Warning*: running these notebooks takes a long time due to the amount of computation required for the data pre-processing and training loop)

## Running the web app locally

- Install Python 3.7+
- Install the required packages with the command: `python3 -m pip install -r requirements.txt`
- Launch the web app with the command `python3 -m flask run`
- Navigate to `http://127.0.0.1:5000` in your browser
- Enjoy :)

