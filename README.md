1. THE DANGERS OF DATA REDUNDANCY 
if a company stores a customer's phsical adress in 3 different table instead of referencing it the data intergrity is destroyed because the is no source that can support his facts. The customer mus update their address and it must be made in three places so when the customer moves it will be simple to find beacuse if they type it wrong the datase will have two adresses for the same person. this may cause problems because they will be miscommunication between their delivery parcels. they must store the adress only once in the customer table other table must use the unique code to link to it 


2. Primary vs Foreign key 
- A foreign key is a link in another table. This key must be check things that already exist to prevent members from using the same primary key many times 

- A primary key is a unique id that make each row different from others. this avoids two customers to use the same member id 
