A Portugese bank is rolling out term deposit for its customers. They have in the past connected to their customer base through phone calls. Results for these previous campaigns were recorded and have been provided to the current campaign manager to use the same in making this campaign more effective.

Challenges that the manager faces are following:

•  Customers have recently started to complain that bank’s marketing staff bothers them with irrelevant product calls and this should        immediately stop

•  There is no prior framework for her decide and choose which customer to call and which one to leave alone

She has decided to use past data to automate this decision, instead of manually choosing through each and every customer. Previous campaign data which has been made available to her; contains customer characteristics , campaign characteristics, previous campaign information as well as whether customer ended up subscribing to the product as a result of that campaign or not. Using this she plans to develop a statistical model which given this information predicts whether customer in question will subscribe to the product or not. A successful model which is able to do this, will make her campaign efficiently targeted and less bothering to uninterested customers.

We have given you two datasets , bank-full_train.csv and bank-full_test.csv . You need to use data bank-full_train to build predictive model for response variable “y”. bank-full_test data contains all other factors except “y”, you need to predict that using the model that you developed and submit your predicted values in a csv files.

Evaluation Criterion :KS score on test data. larger KS, better Model

data dictionary:

1 - age (numeric)

2 - job : type of job (categorical: “admin.”,“unknown”,“unemployed”,“management”,“housemaid”,“entrepre neur”,“student”, “blue-collar”, “self-employed”,“retired”,“technician”, “services”)

3 - marital : marital status (categorical: “married”,“divorced”,“single”; note: “divorced” means divorced or widowed)

4 - education (categorical: “unknown”,“secondary”,“primary”,“tertiary”) 

5 - default: has credit in default? (binary: “yes”,“no”)

6 - balance: average yearly balance, in euros (numeric)

7 - housing: has housing loan? (binary: “yes”,“no”)

8 - loan: has personal loan? (binary: “yes”,“no”)

Related with the last contact of the current campaign:

9 - contact: contact communication type (categorical: “unknown”,“telephone”,“cellular”)

10 - day: last contact day of the month (numeric))

Direct Marketing Campaign: Details and Phase I Tasks
11 - month: last contact month of year (categorical: “jan”, “feb”, “mar”, . . . , “nov”, “dec”)

12 - duration: last contact duration, in seconds (numeric)

other attributes: 13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)

15 - previous: number of contacts performed before this campaign and for this client (numeric)

16 - poutcome: outcome of the previous marketing campaign (categorical: “unknown”,“other”,“failure”,“success”)



17 Output variable (desired target):-     y - has the client subscribed a term deposit? (binary: “yes”,“no”)
