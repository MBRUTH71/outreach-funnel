# outreach-funnel
Building a dummy dataset to represent the BDT outreach funnel and display associated metrics and analytics

# step 1 : create the data tables
1. Contacts
   columns: Contact ID, list source
   50,000 records for 2 different list sources, plus 5,200 with no list source
2. Outreach
   columns: Outreach ID, Contact ID, Outreach Date, Letter ID, Text Followup Ind
   Monthly outreach to 10,000 contacts at the start of each month, Jan through Oct.
   5,000 from each list source, no repeated outreach.
3. Call
   columns: Call ID, Contact ID, Call Date, Screening Ind, Application Ind, Language
   Reported on a weekly basis.  300 calls received per week from outreach, 100 calls not outreach, between 50-100 calls per week not answered.
   90% of calls let to a screening, 75% of screenings led to an application.
4. Application
   columns: Application ID, Contact ID, Submission Date  
5. Enrollment
   column: Application ID, Application Status, Enrollment Report Date, rejection reason.
   Among applications, 60% enrollment, 30% rejection, 10% unknown, but this is only 4 weeks after submission.
   


