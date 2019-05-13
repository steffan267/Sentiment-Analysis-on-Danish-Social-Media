# Sentiment-Analysis-on-Danish-Social-Media
This repo contains annotated data to do sentiment analysis with supervised learning in the danish language. The dataset was created specifically to classify sentences to the root comments of political articles on social media.

The dataset consists of fine-grained polarity in the range from -2 to 2 - negative to postive. The quality of the fine-grained is note cross-validated and is therefore subject to uncertainties; however, the polarity has been cross-validated.

[[https://raw.githubusercontent.com/steffan267/Sentiment-Analysis-on-Danish-Social-Media/master/DataStats.png|alt=octocat]]]
# Guide lines used for annotation

2:
Positive action with positive intensifier.
Direct positive sentiment towards topics, people or objects.
Many tokens that indicate positivity e.g 

1:
Turns something negative into something positive.
Something positive is being referred to.
Positive tone/message.
Wishes something positive without being eagerly formulated.
Subtle expression of positive attitude towards individuals/person/objects.
Few or no tokens that indicate positivity.
A sentence that is near impossible to use negatively (yet often positively).
They express agreement.

0:

A sentence that can only be understood in context is inconclusive.
That which is not immediate positive nor negative.
Sentences that are not inherently positive or negative.
Impartial expressions.
Objective descriptions.

-1:
They express disagreement.
Tokens that indicate negativity e.g :(.
Turns something positive into something negative.
Something negative is being referred to.
Negative tone/message.
Wishes something negative without said being eagerly formulated.
Subtle expression of negative attitude towards individuals/person/objects.
A sentence that is near impossible to use positively (yet often negatively).

# Thesis

Read more about the dataset in our thesis here: (NOT PUBLISHED YET)

# License:

Copyright (c) 2019 

Steffan Eybye Christensen

Lucas Høyberg Puvis de Chavannes

Mads Guldborg Kjeldgaard Kongsbak

Peter Due Jensen


We grant permission to any non-commercial use of the software or associated documentations within this repository. This includes the rights to copy, modify, merge, publish og distribute. Anyone using the contents of this repository are subject to the following condition: 

Accredition of the creators

The above copyright notice and these permission notices shall be included in all
copies or substantial portions of the Software.

Please contact us for any commercial use.

