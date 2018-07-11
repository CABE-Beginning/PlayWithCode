<<<<<<< HEAD
//Saurah
Node jS + Express +Mongo
post salting and hashing:-   
Install cookie parser to save cookie on user's browser:-  "npm install --save cookie-parser"
Install express session:-  "npm install --save express-session"
Install mongostore:-  "npm install connect-mongostore"
install connect mongo:-  "npm install connect-mongo"

=======
Node jS + Express +Mongo
//working on session
session is stored using mongo store, and encrypted before saving as cookie , using secret.

Additional sesson obje (Say username) is added to session , to check whether the db has that object existing for the 
requested session.

///comment saurabh below 12/july
Don't register the schema that is to be embedded(Child schema).
Modify the record fetched(push) and then save to parent schema...to test create a user with first name "skms" and then goto blogcreation page to create 
multiple blogs for the user "skms".