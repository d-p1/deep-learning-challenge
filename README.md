# Background 
  The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

# Overview 
  Using deep learning techniques such as predictive models, our goal is to predict whether an Organization will succeed or not succeed. We use a CSV dataset provided by the Alphabet Soup's bussiness team, containing more that 34,000 organization they are funding, in which the predicive models will output a result(successful or not successfulP.

# Results 


*Preprocessing the Data*:
 - The model's target : variable 'IS_SUCCESSFUL'
 - The model's feature(s) : APPLICATION_TYPE , 'CLASSIFICATION', 'ORGANIZATION_TYPE', 'USE_CASE'
 - 'EIN' and 'NAME' columns were both drop in the beginning due to its possible low impact on determining whether or not the organization would succeed. 

*Optimizing the Model*: 
- In order to optimize the model , we dropped a different column this time :'SPECIAL_CONSIDERATIONS',
- noticing this variable had a lesser impact on the result.
- Focus on binning: 'APPLICATION_TYPE','CLASSIFICATION','ORGANIZATION' . This makes it easier for the predictive model to identify indicators of organizational success.

  
