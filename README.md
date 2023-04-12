# NLP-notes
𝗪𝗼𝗿𝗱 𝗲𝗺𝗯𝗲𝗱𝗱𝗶𝗻𝗴 in NLP is an important term that is used for representing words for text analysis in the form of real-valued vectors. It is an advancement in NLP that has improved the ability of computers to understand text-based content in a better way.

There are several word embedding methods which can be divided into two major categories : 𝗖𝗼𝗻𝘁𝗲𝘅𝘁-𝗶𝗻𝗱𝗲𝗽𝗲𝗻𝗱𝗲𝗻𝘁 and 𝗖𝗼𝗻𝘁𝗲𝘅𝘁-𝗱𝗲𝗽𝗲𝗻𝗱𝗲𝗻𝘁

✅ Context-independent methods are characterized by being unique and distinct for each word without considering the word’s context.

𝗕𝗮𝗴-𝗼𝗳-𝘄𝗼𝗿𝗱𝘀: This method represents a text, such as a sentence or a document,  as the bag of its words, disregarding grammar and even word order but keeping multiplicity.

𝗧𝗙-𝗜𝗗𝗙:  This gets this importance score by getting the term’s frequency (TF) and multiplying it by the term inverse document frequency (IDF).

𝗪𝗼𝗿𝗱𝟮𝗩𝗲𝗰:  A shallow, two-layer neural networks that are trained to reconstruct linguistic contexts of words, utilize either of two model architectures: continuous bag-of-words (CBOW) or continuous skip-gram. 

𝗚𝗹𝗼𝗩𝗲: This performs training on aggregated global word-word co-occurrence statistics from a corpus, and the resulting representations showcase interesting linear substructures of the word vector space.

𝗙𝗮𝘀𝘁𝗧𝗲𝘅𝘁: This method embeds words by treating each word as being composed of character n-grams instead of a word whole. This feature enables it not only to learn rare words but also out-of-vocabulary words.

✅ Context-dependent learns different embeddings for the same word based on its context.

𝗘𝗟𝗠𝗢: learns contextualized word representations based on a neural language model with a character-based encoding layer and two BiLSTM layers.

𝗖𝗼𝗩𝗲: uses a deep LSTM encoder from an attentional sequence-to-sequence model trained for machine translation to contextualize word vectors.

𝗕𝗘𝗥𝗧: This is a transformer-based language representation model trained on a large cross-domain corpus, which uses a masked language model to predict words that are randomly masked in a sequence.

𝗫𝗟𝗠: Another transformer based model which pretrained using next token prediction, masked language modeling and a translation objective.

𝗥𝗼𝗕𝗘𝗥𝗧𝗮: This is built on BERT and modifies key hyperparameters, removing the next-sentence pretraining objective and training with much larger mini-batches and learning rates.

𝗔𝗟𝗕𝗘𝗥𝗧: This is a parameter-reduction techniques to lower memory consumption and increase the training speed of BERT.
