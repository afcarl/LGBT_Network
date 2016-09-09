# LGBT Network 

Visualization can be found [here](https://priyakhokher.github.io/LGBT_Network/){:target="_blank"}
Please find the code+date [here](https://github.com/priyakhokher/SemanticWebProjects/tree/master/BF/LGBT_Network){:target="_blank"}

The idea is to see which topics are connected to each other the most and how?. Developing topics in an article/corpus and seeing how
semantically they are related to other topics in my opinion (is a better way of storing data- CONNECTED FORM) and
also can be used to see data as a whole to find new connections.
This project is dedicated to my best friend Neil Verosh D'souza who is interested in the study !

Procedure

1. Scraped 1200 articles of BuzzFeed (LGBT network) (data in pickle files)
2. The idea was to build LDA model on the content of the articles
3. As the LDA model would take time to refine - exploratory analysis was done on the tags of the content/article (obtained from the scraped contenct) to see which articles tags get linked more frequently with which tag

4. The network visualizes only those connections pairs that have occured more than 5 times. The width of the edge shows how often they occur together. (wider means strong occurence together)
5. The color indicates the "between-ness centrality" computed on the network. betweenness centrality is a better choice than degree as the connections between pair of words is accentuated by this metric and importance of a node in terms of degree comes to show itself on its own with the pair connections inherent in the network
6. Here are the values for "between-ness" centrality:
{'add yours': 0.0,
 'aids': 0.0,
 'auspol': 0.0,
 'australia': 0.2594594594594594,
 'bathrooms': 0.0,
 'bisexual': 0.007112375533428165,
 'canada': 0.0,
 'collection': 0.0,
 'coming out': 0.0,
 'dating': 0.0,
 'gay': 0.22361308677098157,
 'hb2': 0.0,
 'hiv': 0.052631578947368425,
 'lesbian': 0.05334281650071124,
 'lesbians': 0.0,
 'lgbt': 0.7642958748221907,
 'lol': 0.0,
 'love': 0.0,
 'marriage equality': 0.10384068278805121,
 'nhs': 0.0,
 'north carolina': 0.028733997155049793,
 'orlando shooting': 0.0,
 'plebiscite': 0.0,
 'pride': 0.0,
 'queer': 0.0,
 'quiz': 0.0,
 'relationships': 0.0,
 'same-sex marriage': 0.0,
 'sex': 0.052631578947368425,
 'social news': 0.03442389758179232,
 'style': 0.0,
 'television': 0.0,
 'title ix': 0.0,
 'trans': 0.028733997155049793,
 'trans rights': 0.0,
 'transgender': 0.16500711237553345,
 'transrights': 0.0,
 'truvada': 0.0,
 'viral': 0.0}

7. Please find the code+date [here](https://github.com/priyakhokher/SemanticWebProjects/tree/master/BF/LGBT_Network)
8. Any suggestions would be appreciated. Editing on the main html file is ongoing.
