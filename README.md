# COVID-19 Response Evaluation Dashboard Data Repository by EPSRC IRC i-sense

This is the data repository for the COVID-19 Response Evaluation Dashboard operated by the i-sense project, 
a colloboration between researchers from the University College London and Univeristy of Leeds. 

We provide data on the performance of contact tracing system in England divided into five stages:
- Find potential cases (Find)
- Test to confirm (Test)
- Trace their contacts (Trace)
- Isolate contacts (Isolate)
-  Support contacts to isolate (Support)

The interactive data dashboard can be found here: https://covid.i-sense.org.uk

`Note (2020-Dec-11) : The ONS Infection Survey advises that the methodology used for estimating incidence rate (new infections) is under review,
 and the most updated incidence data is dated on 22 Nov.
New data will be available again in January. `

#### Data Dictionary (`FTTIS_data.csv`):  

`week_start`:	the start of the week

`week_end`:	the end of the week

`estimated_new_infections`:	estimated number of new infections per week from ONS infection Survey

`date_estimated`:	the date associated with the estimated new infections in ONS infection Survey

`date_released`:	the date when the estimated incidence is released

`test_positive`:	total number of positive cases by specimen date in this week

`reached_positive`:	total number of positive cases who were reached and asked to provide contact details in this week

`reached_positive_provided_contacts`:	total number of positive cases  who provided details for one or more close contact in this week

`identified_contacts`:	total number of close contacts identified

`reached_contacts`:	total number of close contacts reached and asked to self-isolate

`%test_testpositive`:	`test_positive`/`estimated_new_infections`

`%trace_reachedpositive`:	`reached_positive`/`estimated_new_infections`

`%trace_providedcontacts`:	`reached_positive_provided_contacts`/`estimated_new_infections`

`%isolate_contactsreached`:	(`reached_contacts`/`identified_contacts`)*(`reached_positive_provided_contacts`/`estimated_new_infections`)


If you think we have missed any data sources or want to contact us, please [email us.](e.j.manley@leeds.ac.uk)

#### Terms of Use:

This data set is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).