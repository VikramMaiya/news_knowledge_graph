# news_knowledge_graph
CREATING SUMMARY AND KNOWLEDGE GRAPHS FROM NEWS ARTICLES

pip uninstall neuralcoref
git clone https://github.com/huggingface/neuralcoref.git
cd neuralcoref
pip install -r requirements.txt
pip install -e .
pip uninstall spacy
pip install spacy
python -m spacy download en_core_web_lg
