SpaCy Garden Path Sentences Analysis
This Python script analyzes a set of garden path sentences using spaCy, a powerful natural language processing library.

Project Description
The script utilizes spaCy's pre-trained English model (en_core_web_sm) to perform tokenization and named entity recognition (NER) on several garden path sentences. Garden path sentences are grammatically correct but can be initially confusing due to their structure. By analyzing these sentences, we can explore the challenges of natural language processing and how spaCy tackles them.

Running the Script
Ensure you have Python and spaCy installed. You can install spaCy using:

bash
Copy code
pip install spacy
Clone or download this repository.

Open a terminal or command prompt and navigate to the directory containing the script.

Run the script using:

bash
Copy code
python garden_path_analysis.py
Replace garden_path_analysis.py with the actual script name if different.

Expected Output
The script will print the following for each sentence:

The original sentence
A list of tokens, including their text, part-of-speech (POS) tag, dependency label (DEP), and named entity type (ENT_TYPE_)
Explanations for the entity labels:

FAC (Facility): Highlights how spaCy might identify relevant entities even if they don't directly map to single words. For example, "FAC" is associated with "cotton clothing" because it could be manufactured in facilities.
GPE (Geopolitical Entity)
Additional Information
SpaCy documentation: https://spacy.io/
Garden path sentences: https://en.wikipedia.org/wiki/Garden-path_sentence
