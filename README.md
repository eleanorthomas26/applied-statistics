# applied-statistics

# Make sure to download the necessary NLTK resources if you haven't already
import nltk
from collections import Counter

nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')

def analyze_text(text):
    #remove punctuation
    cleaned_text = text.translate(str.maketrans('', '', string.punctuation))
    
    # Tokenize the text into words
    words = nltk.word_tokenize(text.lower())
    
    # Count the frequency of each word
    word_freq = Counter(words)

    # Create a nested dictionary
    word_info = {}
    
    for word, freq in word_freq.items():
        length = len(word)
        word_type = nltk.pos_tag([word])[0][1]  # Get part of speech
        
        # Add to the nested dictionary
        word_info[word] = {
            'length': length,
            'frequency': freq,
            'type': word_type
        }

    return word_info

# Example usage
text = "Hello world! This is a test. Hello again, world."
word_analysis = analyze_text(text)

print(word_analysis)
