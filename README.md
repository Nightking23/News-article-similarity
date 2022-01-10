# News-article-similarity
Overview
With this project, we aim to segregate and group news articles of the similar kind. More than
other features like the style of writing, paragraph phrasing and the emotion conveyed, we will
judge the articles on the basis of the anecdotes they mention in them.
This interests us because many news publishing applications experience a lot of spam as the
users from all across the world want to access the same content in their regional languages.
However, two articles about a political discussion in the parliament are likely to be shown as
similar even though they are not.

Goals
● Task:-Given a pair of news articles, are they covering the same news story?
● The aim is to develop systems that identify multilingual news articles that
provide similar information.
● This is a document-level similarity task in the applied domain of news articles,
rating them pairwise on a 4-point scale from most to least similar.

Challenges
To answer this question, we will need to know particular details about the events in question,
such as what happened, where and when it happened, who was involved, and why and how it
happened. Solutions should also avoid relying too heavily on general language models, because
similarity in writing styles, generic phrases, and other non-essential content can be deceiving,
and dimensions such as time and geolocation of the actual event (not the publication time or
place) as well as narrative are difficult to capture.

3

Dataset Analysis
Our dataset is specifically two news articles of varied genres and same or different incidents.
We compare them on the basis of:-
● How similar is the geographic focus(places,cities,countries,etc) of the two articles?
● How similar are the named entities(e.g., people, companies, organizations, products,
named living beings), excluding previously considered locations appearing in the two
articles?
● Are the two articles relevant to similar time periods or describing similar time periods?
● How similar are the narrative schemas presented in the two articles?
● Overall, are the two articles covering the same substantive news story?(excluding style,
framing, and tone)

References
CodaLab:- https://competitions.codalab.org/competitions/33835
Semantic Similarity Using Transformers
https://towardsdatascience.com/semantic-similarity-using-transformers-8f3cb5bf66d6
