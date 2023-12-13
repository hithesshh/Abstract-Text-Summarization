# Abstract-Text-Summarization
Using Pegasus pretrained ML model we pass pieces of text into this model for it to be summarized "abstractly" . "Abstractly" as in the model doesnt pick the most impotant line in the dataset but rather gives you a summary based on important pieces of text spread throughout the dataset.
In the ipynb file attached we use the following piece of text data:
'''This year, Rajinikanth gave 'Jailer' which changed the landscape of Tamil cinema by earning more than Rs 600 crore. Rajinikanth is the only actor from the South whose two Tamil films have collected more than Rs 500.
Even at this age, Rajinikanth is a mainstream hero and single-handedly takes charge of the film and creates records. Rajinikanth is also the highest-paid actor not only in South India but also in India, who took a fee of Rs 210 crore for the film 'Jailer'.
As per reports, Rajinikanth was given a remuneration of Rs 210 crore to play the lead role of Muthuvel Pandian in 'Jailer' and with an addition of Rs 100 crore for being part of the film, he has become the highest-paid actor in Indian cinema. In total, Rajinikanth earned Rs 310 crore and a branded car for 'Jailer' which the producer gifted him after the film's success. '''
The model proceeds to give us the following output:
'''Tamil superstar Rajinikanth has become the highest-paid actor in Indian cinema.'''

Its important and interesting to notice that the output string given cannot be found anywhere in the input text which shows how amazing the google/pegasus-xsum model really is.
