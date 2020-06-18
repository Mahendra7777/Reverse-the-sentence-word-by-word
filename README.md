# Reverse-the-sentence-word-by-word

def rev_sentence(sentence)
words = sentence.split(‘ ’)
reverse_sentence = ‘ ’.join(reversed(words))
return reverse_sentence

if _name_ = “_main_”:
input = ‘I am a good programmer’
print rev_sentence(input)
