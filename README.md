# Deconstructing Ranking Abilities of Language Models 
## Abstract ([Full PDF here](main.pdf))
Nowadays, information retrieval plays an important role in our daily lives. Whether we’re
searching the web, shopping for products online, or trying to find our favorite movies on a
streaming platform: An information retrieval system will be responsible for tackling these
tasks. As a consequence of recent advances in natural language processing, employing
large pre-trained language models as part of a text retrieval pipeline has become a
common approach. However, despite their proven effectiveness, these neural network
based models are functional black boxes, meaning it is not clear to us as to how they
arrive at certain decisions. To get a better understanding of the inner workings of such
a model, we apply the recently emerging probing paradigm. By employing a diagnostic
classifier, this approach enables us to analyze how certain properties are encoded within
a model’s hidden representations. Unlike previous research that has focused on general
linguistic properties, we explicitly study the layer-wise distribution of ranking related
knowledge throughout the popular BERT model, a large neural network that has been
trained on massive amounts of text data. In this thesis, we provide evidence that BERT
not only stores ranking related concepts, but also orders them in a hierarchical manner.
Moreover, we leverage our findings to design a multi-task learning setup which infuses
task specific information at different layers of BERT, in order to improve the model’s
ability to rank.
