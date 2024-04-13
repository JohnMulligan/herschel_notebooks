# Herschel ipynb

The original intention of this repository was to stage formalizations of the calculations regularly made by the Herschels in the process of their astronomical work. However, the project has since grown, as I have been given access to digitizations of the Herschel collections held by the RAS and the UT Austin Ransom Center.

However, the projects are still tightly related. I will therefore articulate the two reamde's (NS) here.

## The original 'Notebooks' project

For a conference in York, I created a Python Jupyter Notebook that demonstrated the reproducibility of Caroline Herschel's work. to my mind, the Herschel Archivie is *the* ideal linked data project for archivists, as it was the origin of modern data science. That's a big claim, but it's true.

Read [that Readme here](notebooks.md).

## The linked data archival project

I have, since, attempted to realize the vision of a linked data version of the Herschel archive.

Initially, I used Omeka-S to produce a linked data archive of the project. However:

1. Its IIIF image server, either because of threading or some other internal issues, would not tile properly.
1. Without using the Custom Ontology plugin (which there is reason to be skeptical of), I could not achieve the linked data effects I wanted.

I then transitioned to Intranda's Goobi viewer & workflow pipelines, and have been quite impressed.

1. I have decided not to down-convert my TIF's but rather simply to give my viewer enough RAM to tile the images live in its IIIF server, and have been very impressed by its performance.
1. I have found its balance between customizability and adherence to standards, in principle, to be ideal. This project has to take a long view, and so a system that prioritizes interoperability is key.

[My ongoing notes on my work with these Intranda systems is here](linked_data).