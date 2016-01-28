# GoogleSpreadSheetAPI

It is the API generated using JAVA. The authentication method of the user who uses a batch process is better to use the service account.

**We'll add the service account**

(1) "Permission" in the left menu -> you will select the "permisssion information".                                                                                                                                                                                                                                                                                                                                                                                                                                       
(2) Choose the "service account" in the menu.                                                                                                                                                               
(3) Choose the "P12" on the type of key.

Save the Generated `P12` key in src/main/resource

**Create an Excel Sheet**

(1) Set the Title.                                                                                                                                                                      
(2) Set the authority to write to this spreadsheet in the service account.                                                                                                                   
(3) Click the Share button on the seat right end, and then click the submit button to enter the email address of the service account.

 When you register to a service account will be issued client ID and e-mail address, but we more of the e-mail address then the clientID.
 
 **Before Running the project**                                                                                                                                                                                                                                                             
 **(1) Set the ACCOUNT_P12_ID = email ID that is generated alone P12key.**                                                                                                                                                                                                  
 **(2) Set the ssName to Name of the ExcelSheet**                                                                                                                                                                                                                               
 **(3) Set the wsName**


