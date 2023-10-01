# annotation-data-thesis
The data of the "Textual Re-knittings" workshop and some code for its visualisation and structuring, as part of my Master thesis in Digital Humanities and Digital Knoweldge (DHDK), at the Università di Bologna.

This data was produced by a dozen of participants of the Hackers & Designer's Summer Camp, using anonymous pseudonyms, as part of a 10 days experimentation in digital social reading and collaborative rewriting, which I coordinated and animated. 

Revolving around the theme of "Hope-Punk", our collectively chosen texts have been socially read and re-written (re-knitted), as a "digital social text" experiment, from the 18/07 to the 27/07/2023 in Het Wilde Weg (Netherlands).

For more information on this workshop and its general argument, see [here](https://hackersanddesigners.nl/s/Summer_Camp_2023/p/Textual_Re-knittings). 

Our experiment used the social, web annotation tool [Hypothes.is](https://web.hypothes.is/). [the Hypothes.is API tool](https://jonudell.info/h/facet/) developed by [Jon Udell](https://github.com/judell) was used to retrieve the data in html, json and csv format.

The API gave us the main material to produce [a web-archive of all annotations](https://networkcultures.org/reading-group/textual-reknittings/annotation-archive/all-annotations.html). 

In this repository, you will find:
- the original data in json and csv format
- the Jupyter notebook for making some visualizations and charts in Python using Pandas and MatPlotLib
- a Gephi network visualization file, with its respective nodes and edges xlsx files
- a proposed ontology for the data of the digital social text, in OWL, RDF and TTL formats

This data and code serves the purpose of providing figures to analyze as part of the thesis "Towards a Digital Republic of Letters? Analyses and Propositions for the Digital Social Text", to be sumbitted and presented during the second final exam session of late october-early november 2023, in Aula Affreschi (Via Zamboni 34, Bologna, Italy). If the annotation data of the experiment is published publically on this GitHub repository, it is solely for the academic intent to take a look at the source data and the code used to make vizualizations on it: that is, for transparency reasons. In no way can this data be used commercially or for other non-academic purposes. The ontology files are prototypical propositions, which can be re-used and transformed, ameliorated, given that the credits to this project are provided. 

Some other web archives and Python code is presented or mentionned within the final thesis paper itself. 
