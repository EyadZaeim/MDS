# MDS

https://developers.google.com/docs/api/samples/mail-merge  ( lINK FOR THE SAMPLE CODE )
https://developers.google.com/docs/api/quickstart/python   ( LINK FOR PYTHON & GOOGLE API INTEGRATION )
https://github.com/googleworkspace/python-samples/tree/master/docs/mail-merge ( GITHUB LINK FOR SAMPLE CODE )
https://docs.google.com/document/d/1rWK74DQA42K8VkbW3qPgyPFr8IhFZ4cUdq2z_XcmkiM/edit?usp=sharing  ( LINK TO GOOGLE Doc TEMPLATE ).
https://docs.google.com/spreadsheets/d/1zTZRO27k_f5YsX9zkUXjsmuHsGvYdjDntUk0cJHLDog/edit#gid=1089207158 ( LINK FOR SAMPLE GOOGLE SHEET )



-
IMRPOVING THE CODE PLAN 
1. SOLVE ERRORS: current error is shown below ( ERROR SOLVED )

    

2. FORMULATE CODE FOR OUR PURPOSE
  Since this code is made to generate a different doc for each row pulled from excel sheet, i would like to have all rows in the same sheet ( see my doc sheet ) i belive that this part of the code is resposible for that manner. 
  
get row data, then loop through & process each form letter

    * data = get_data(SOURCE) # get data from data source
    for i ,row in enumerate(data):
        merge.update(dict(zip(COLUMNS,row)))
        print(Claimant_Name '%d: docs.google.com/document/d/%s/edit' % (
                i+1, merge_template(DOCS_FILE_ID, SOURCE, DRIVE))) * 
  




4. GET CODE TO DOWNLOAD TEMPLATE AS PDF AFTER MERGING 
