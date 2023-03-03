# MERN-Apis-Hub
    First MERN Paractice App
      A web app that displays apis information to users and users can add apis to their wish list.
        CRUD ops applicable on apis and user's data
        
# FOR VISITORS
    Apis url can be copied, Without Login
    Need to create account and then you will be able to perform actions like -> Add Apis , Delete Apis, update Profile data and delete Account
    
#  SERVER 
    Mongo db Atlas connected
    Single user model is being used.  User Data & Added Apis 
    Fetched apis data from [ https://api.publicapis.org/entries ]
    Fetched images for each unique api category from [ pexels Api ]
  
#  RESTFUL APIS
    Used two different routers
     '/user' for user's actions -> isUserAuth, SignUp, LogIn, updateAccount, deleteAccount
     '/free-apis' for apis's actions -> getAll, addToList, deleteFromList, getAddedApis
  
#  AUTHENTICATION
      Athentication is applied on required routes using middleware function.
   
# CLIENT
    Simple web app front-end emplemented.
    Not too much optimized [ app might lag ]
    Not good UX  | It was very lengthy as CSS was being used.
  
  # COMPONENTS
      Hooks -> useState, useEffect, useContext(userContext, apisContext) are being used.
      Quite understandable code, Except 'UserProfie' component.
      There is also a mishandeled problem -> In 'UserProfile' in updaate Password section, massage is not being conveyed clearly.
      
 # PROBLEMS
    Done alot of processing on client side.
    Used PNGs
    
