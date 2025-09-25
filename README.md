# MatchUsernames - RapidFuzz - Phyton
Example of a real use case of Phyton and RapizFuzz library to match name, surname, email and usernames from different sources. 
We used test data in the example test files provided. Test data led to 100% match.
In our real life user case we had to match a list of users from an ERP with a list of email addresses of the same company. 
Additional complexity encountered was: 
- user information were not stored in the same format in the 2 lists, caps, low, commas, dashes, etc
- some users had multiple names and surnames like 2 first names and 2 surnames, but on the other list only 1 name and 1 surname
- we had users registered with nicknames
- especially in Asia lot of users with the same shorth surnames and nicknames instead of real first names (so the 2 lists were not matching)
- erp users regitered with former surnames (exp maiden surname instead of actual surname - again the 2 lists were not matching
With all these challenges still we got to a 80% records with a matching score > 90%
