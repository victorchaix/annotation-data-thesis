# annotation-data-thesis
Data of the "Textual Re-knittings" workshop + some code for it visualisation and structuring, as part of my thesis in Digital Humanities and Digital Knoweldge (DHDK), at the Università di Bologna.

This data was produced by some participants of the Hackers & Designer's Summer Camp, using anonymous pseudonyms, as part of a 10 days experimentation in digital social reading and collaborative rewriting, which I coordinated and animated. 

Revolving around the theme of "Hope-Punk", our collectively chosen texts have been socially read and re-written (re-knitted) as a "digital social text" experiment, from the 18/07 to the 27/07/2023 in Het Wilde Weg (Netherlands), on the theme of "Hope-Punk". 

For more information on this workshop and its general argument, see [here]([url](https://hackersanddesigners.nl/s/Summer_Camp_2023/p/Textual_Re-knittings)https://hackersanddesigners.nl/s/Summer_Camp_2023/p/Textual_Re-knittings). 

Our experiment used the social, web annotation tool [Hypothes.is](https://web.hypothes.is/). To retrieve the data produced within it, [the Hypothes.is API tool](https://jonudell.info/h/facet/) developed by [Jon Udell](https://github.com/judell) was used, to retrieve the data in html, json and csv format, according to tag.

This allowed us to produce [a web-archive of all annotations](https://networkcultures.org/reading-group/textual-reknittings/annotation-archive/all-annotations.html). 

In this repository, you will find:
- the original data in json and csv format
- the Python notebook for making some visualizations and charts using Pandas and MatPlotLib libraries
- a Gephi network visualization file, with its respective nodes and edges xlsx files
- a proposed ontology for the data of the digital social text, in OWL, RDF and TTL formats

This data and code has the purpose of providing figures to analyze as part of the thesis "Towards a Digital Republic of Letters? Analyses and Propositions for the Digital Social Text", to be sumbitted and presented in the second final exam session of late october-early november 2023, in Aula Affreschi (Via Zamboni 34, Bologna, Italy). Some other web archives and Python code prototype is presented or mentionned within the thesis paper itself. 
