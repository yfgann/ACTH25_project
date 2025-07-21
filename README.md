# Project summary
Dataset: Cleveland Museum of Art Dataset & The Art Institute of Chicago


# Design choices
1. Both musuems provide open access user-friendly APIs
2. Extensive Asian Art Collection, especially for Yufeis "Ceremics" subclass idea @yfgann


# Division of group work
- Dataset collection, Data Pre-processing, cleaning, 5000 sampling
- Metadata: Cleveland Museum of Art: csm.json; Art Institute of Chicago: aic_text_5000.csv

Ziqi:
1. main.ipynb
2. UML class diagram: UML_Graphviz.png
3. Text-based: 
    3.1 Topic modelling. Output visualization: wordcloud AIC.png 
    3.2 Cross museum title cluster; Output visualization: 2D maps of artifacts, titlecluster.png
4. Image-based: data collection from AIC image API, aic_images folder.

   
Yufei:
1. class1.ipynb
2. subclass Ceremics, subclass HumanArtist and OrgArtist, Wikidata enrichment
4. RDF Graph visualization - 10 artworks demo
5. image-based ML with visualisation to examine the ceramic objects across regions
