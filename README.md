# BatBase
Bat Virome Database

DESCRIPTION AND REASONING

BatBase is a hybrid between a species database and a virus/disease database. In short BatBase contains information about bat-borne zoonotic viruses. These viruses are capable of infecting humans and are considered emerging viruses.

BatBase consists of 9 table schemas. The first table consists information about 7 emerging zoonotic bat-borne viruses. These viruses are rabies, SARS-COV, SARS-COV-2, MERS-COV, Ebola, Nipah and Marburg. Theses are some of the most prominent and influential virus in the past several years. They have resulted in many epidemic and pandemic situations. This table also consists of the symptoms of these viruses and which bat species they are caused by. Their data was collected from Wikipedia

The second table comprises of data about all major bat species including the domain and family names, their natural habitats, and the diseases they are said to cause. This data was collected from Wikipedia and DBatVir 

Then the database contains 7 more table schemas containing the genes related to each disease which includes their gene ids, their descriptions, their nucleotide accession ids, and their MIM ids. This data was collected form NCBI gene database.

There is only one other existing bat virome database is known as DBatVir ( mgc.ac.cnhttps://www.mgc.ac.cnDBatVir: the Database of Bat-associated Viruses )
This database comprises of a repository of all bat associated viruses but it does not specify the viruses which can particularly affect humans. This database is also very slow and quiet un intuitive as it does not contain user friendly query/search function.

Our database solves these issues by having a relatively simple but effective schema that efficiently links data from several tables to provide the user with the information they need.
We also concentrate on a particular area of research i.e zoonotic viruses instead of whole virome. Hence BatBase can be considered as a secondary database.

Finally BatBase can be easily expanded and updated for future relevance as it still has a lot of space additional data. More schema tables can be created if any new zoonotic virus show up. Hence this is the reason we came up with the idea of BatBase
