# OOP Analysis of AI Frameworks
Caleb and Kevin

## Environment
1. We used conda to create this environment, so download conda from their website and follow their setup instructions
    * https://www.anaconda.com/download/success
2. Once youve done that you can then safely run the code cells in the jupyter notebook
   * I recommend opening a csel or google collab env for this
   * depending on the cloud env or ide you use some extra steps may include
     * installing the notebook package
     * install the ipywidget package

## Hosted Services
All frameworks require a hosted or local service to run fully. Right now the cells are code that shows the
application of the OOP concepts in the framework (point of the paper). If you wish to uncomment the lines with the 
connected services you must do the following
* Open csel or a google collab environment, import the notebook there
* Langchain/LlamaIndex require an LLM to be able to run, so we will use Ollama as its free
    * here is a link to the ollama website and how to install it
    * https://ollama.com/
* For elasticsearch, instructions on how to deploy locally are here as well
    * https://www.elastic.co/search-labs/tutorials/search-tutorial/full-text-search/connect-python

## HuggingFace
Hugging face will pull metadata about models onto your machine or into the cloud env you use.
* If you do not have enough space or ram it will not work
* Usually hugging face pulls the smallest available model

## ElasticSearch
Some of the functions need documents to be able to run
