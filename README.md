Dataset Source – OpenDataSus - Registros de Vacinação Covid19 - Dados SC – Santa Catarina – Brasil (1)

Dataset downloaded on 02 July 2021 at 07:00 am.

Inicial master File named – sc0207_07am.csv

Original total file size – 1.71 GB = 34 columns and 3.133.344 (or registrations)

The above master file was divided in 17 separated files. Each grouping all the registered data from the counties belonging to a DECENTRALIZED EPIDEMIOLOGICAL SURVEILLANCE UNITS (UDVE) in the state of Santa Catarina- Brasil.

To have the most updated dataset up to 30 Jun 2021, I downloaded the file from OpenDataSus on 02 Jul 21 at 07 am, and re-named my downloaded master file to match this (sc0207_07am_csv).

Per the original source records at the time of the download, the latest updated of the original database was done on 01 July 21 at 3 pm. I hope, we will have most of the updated registrations up to 30 June 2021 to compare with the data from end May 2021 used for modules 1 and 2.

FYI: between the last update done to the original source database on 29 Jun 21 and 01 Jul 21, 92.876 registrations were added to the OpenDataSus' database for the state of Santa Catarina.

# Introduction for Module 3 work:

This personal project was created as a task for Module 3 (out of 5) of the Alura Bootcamp Data Sciences Applicada.

It is a continuation and extension of the exploratory work I already done for the first two modules of this bootcamp, when I reviewed the OpenDataSus registers of covid19 vaccination in the Brazilian State of Santa Catarina(SC) up to 30 May 2021.


# Brief Comments and conclusions: FINALLY I DE-EXCELLED!!!!

* With the help of the Alura Bootcamp Applied Data Sciences II, Alura courses Programming with Python, Python for DataSciences, services as stackoverflow, medium and others, I accomplished my objective to deliver all the 3 phases of this module 3 project entirely within one Google Colab notebook using Python related packages.

* We notice that, in Santa Catarina, on 30 Jun 21, the overall trend of 12% registrations of covid_19 vaccinations with 'Combinations of Concern' is still valid (368,833 (CoC_1 + CoC_3) out of a total of 3,133,344 registrations).

* UDVE 13 alone clusters 62% of the state total of 'Combinations of Concern' (229,208 out of 368,833).

* "'No_issue'" - as already mentioned, from the pharmacovigilance point of view, is not totally correct, as I noticed some other 'combinations of worrying' (to distinguish of the definition of 'CoC'). So I may tackle 'combinations of worrying' in the projects of the next two modules of this bootcamp.

Finally, as already explained elsewhere, I am tailoring all the above with the end_user in mind: the SC UDVE manager and local teams at the each 'vaccination center'. Therefore, at the end of this bootcamp we may use the material above to easily identify and isolate all the registrations with 'combinations of concern' for appreciation at several levels - UDVE, county, vaccination center, etc. More about how that can be done in a sensitive way with efficiente Risk Based Monitoring techniques I use in clinical trials may be presented in the next two modules.
