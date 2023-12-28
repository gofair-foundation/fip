# Minting nanopublications

What is a nanopublication? 
A nanopublication is a unitary assertion about the world with associated metadata, rendered in machine-readable form, and all of this having a globally unique, persistent and resolvable identifer (see [here](https://nanopub.org/wordpress/) and [here](https://peerj.com/articles/cs-387/)). 

<p align="left"><img src="./_static/img/fipwug_ch3_img16flat.png" width="20%"></p>

Nanopublications are authored using cryptographic keys that make them hard to forge and corrupt. So once published, they are persistent and immutable.  
Multiple nanopublications can be “contained” or bundled using a special kind of nanopublication called “index nanopublications”. 

Why nanopublication? 
These computational properties of nanopublications can be powerfully leveraged to make machine-readable FIPs.
This happens in two ways: 
Individual components of the FIP (such as the FIC and FERs) are all represented as nanopublications.
The output of the FIP Wizard 3.0 (see below, Publishing your FIP) is an index nanopublication that provides a list of declared FERs for every FIC.
How to mint FER nanopublications in the FIP Wizard: 
Go to VII. Register a new resource as a nanopublication
Click on one of the for “template” links
This takes you to a new project dialog box. In this case, the new project is the nanoWizard. 
Select the tab: From Template 
Enter a name for your new nanopub. 
There is no specific format required here for the name. 
Click Save. This will bring you to the nanoWizard questionnaire. 
There are only two chapters in the nanoWizard:
I. Author - provide your ORCID.
II. Definition - various details required to build your nanopublication. For Communities you may choose a “supercommunity” to which your community belongs which will help in the analysis of  the results. For FERs you have to identify the appropriate FER type. More than one FER type can apply. A FER might be available or to be developed.
For the name of the resource you are creating you should avoid ‘,’ use a pipe (|) with a space before and after that symbol (for enabling a better findability) if you want to add both an acronym and a longer name like Envhes | Environmental Thesaurus
After completing the nanoWizard, go to Documents (16) and make a “new document”.
For Template choose Nanopublication Template and for Format choose RDF Trig. 
Push Create

<p align="left"><img src="./_static/img/fipwug_ch3_img16.png" width="50%"></p>

If no error appears you can submit the nanopub clicking on the three dots (17):

<p align="left"><img src="./_static/img/fipwug_ch3_img17.png" width="20%"></p>

Choose Nanopub Server (not the local one, which is only for testing) and submit
Click on view submission
You will view the submission as a FER nanopub (18), the persistent identifier (nanopub URI) is highlighted in yellow

<p align="left"><img src="./_static/img/fipwug_ch3_img18.png" width="70%"></p>

This FER will now appear, automatically, in the drop downs of the question where the FER type is expected (e.g. identifier for F1).
The newly created FER will not yet have a GFF qualification, as this review process will take a few days. If it is not accepted you will get a notification about the reason. 
You can, however, already use the FER before it gets a qualification.

