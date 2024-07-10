# nosql-challenge-2-
Module_12_Challenge
I created a New Repository called nosql-challenge-2. I cloned the repository to the computer, I added the Jupyter notebook Starter files to this foler. I pushed the changes to Github. For Part 1, I imported the data provided in the establishments.json file from the terminal. I named the database uk_food and the collection establishments. I also copied the text I used in the import data from my Terminal to a markdown cell in my notebook. Within my notebook, I imported the PyMongo and the Prettyprint libraries. I created an instance of a Mongo client. I made sure that I created the database and loaded the data properly. I listed the database in MongoDba and made sure that uk_food is listed. I listed the collection in the database to ensure that establishments is there. I found and displayed one document in the establishments collection using find_one and displayed with pprint. I assigned the establishments collection to a variable to prepare the collection for use. In Part 2, I used the NoSQL_starter_setup.ipynb. I wrote an analysis on the new halal restaurant in Greenwich. I added {
    "BusinessName":"Penang Flavours",
    "BusinessType":"Restaurant/Cafe/Canteen",
    "BusinessTypeID":"",
    "AddressLine1":"Penang Flavours",
    "AddressLine2":"146A Plumstead Rd",
    "AddressLine3":"London",
    "AddressLine4":"",
    "PostCode":"SE18 7DY",
    "Phone":"",
    "LocalAuthorityCode":"511",
    "LocalAuthorityName":"Greenwich",
    "LocalAuthorityWebSite":"http://www.royalgreenwich.gov.uk",
    "LocalAuthorityEmailAddress":"health@royalgreenwich.gov.uk",
    "scores":{
        "Hygiene":"",
        "Structural":"",
        "ConfidenceInManagement":""
    },
    "SchemeType":"FHRS",
    "geocode":{
        "longitude":"0.08384000",
        "latitude":"51.49014200"
    },
    "RightToReply":"",
    "Distance":4623.9723280747176,
    "NewRatingPending":True
} to my database. 
I found the BusinessTypeID for "Restaurant/Cafe/Canteen" and returned only BusinessTypeID and BusinessTypeFields. I updated the new restaurant with the new BusinessType ID I found. I also checked how many documents contained the Dover Local Authority. I removed any establishments with the Dover Local Authority from the database and checked the number of documents and made sure that they were deleted. I used update _many to convert longitude and latitude to decimal numbers, I also used update_many to convert Ratingvalue to integer numbers. For Part 3, I used the NoSAL_analysis_starter.ipynb. I used count_documents to display the number of documents contained in the result. I displayed the first document in the result using pprint. I converted the result to a Pandas Dataframe, printed the number of rows in the dataframe and displayed the first 10 rows. I answered some questions - which establishments have a hygiene score of 20, which establishments in London have a Ratingvalue greater than or equal to 4. I also answered what are the top 5 establishments with a Rating value of 5, sorted by the lowest hygiene score, nearest to the new restaurant added, "Penang Flavours", I answered this question - How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas. 
