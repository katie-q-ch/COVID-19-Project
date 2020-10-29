# COVID-19-Project
COVID-19 DNA Analysis and Twitter Topic Modeling

README

The COVID-19 Project includes the following information:
1. DNA data analysis jupyter notebook
2. Twitter data modeling jupyter notebook
3. Raw DNA sequences collected from NCBI 
4. Machine Learning COVID 19 Power Point Presentation

Part 1: DNA analysis with Bio

    Goals: 
        1. To analyze COVID-19 gene sequences between Jan 2020 to date Sep 2020 
        2. To detect mutations (if yes, then what has changed?)

    Data:
    The COVID-19 RNA sequences include: 
        -2 samples collected in January 2020
        -2 samples collected in April 2020
        -2 samples collected in September 2020
    Gene sequencing: 
        1. Convert DNA to RNA
        2. Convert RNA to protein
        3. Remove short proteins

    Mutation analysis:
        Compare the January sequence with September sequence to detect possible 
        mutations. Eight were detected. 

Part 2: 
  
    Goals: 
        1. To analyze COVID-19 gene sequences between Jan 2020 to date (Sep 2020) 
        2. To detect mutations (if yes, then what has changed?)

    Data: Tweets contained COVID-19 collected on Oct 25, 2020 using Twitter API.
    
        Tweets processing: Tweets were cleaned, okenized, stemmed and 
        lammatized to get ready for analysis. 
        
        Modeling: Models (KNN, Linear, Multinomial, Random Forest and Logistic
        were built to predict which of the 3 categories (politics, health, and               
        emotions) a tweet belongs. The machine learning models may be  used to               
        quickly categorize tweets or short messages as oppose to manualy label
        short texts. 
        
     Testing: 
        Random forest was chosen for testing. It did predict the tweet correctly.
        However, the accuracy of the model is not ideal. There were 400 tweets
        used to train the model due to limitted labeled tweets aivalble. 
        
 Future works: Analyze Covid-19 RNA for possible mutations in the future.
               Collect and label more Twitter data to train the models on. 