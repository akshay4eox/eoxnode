1. NODE > EOS App Data
    CREDENTIAL > Credentials for an EOS account (a generic helper account can be used in some cases)
    RESOURCE
        > Entity 
        > Submission
    OPERATION
        > Entity (*Not recommended for use in production. These operations are workflow-construction aides.)
            > Get All (Retrive a list of all entities in an app)
            > Get Shape (Retrives the JSON structure of a given entity)
        > Submission
            > Create (simulating a form submit)
            > Update (simulating a form edit + submit)
            > Delete (deleting a submission)
            > Read (get detail view of a row)
            > Read All List (get a list of all submissions of a particular entity)
            > Read All Details (get the details of all submissions of a particular entity) (*High load)
2. NODE > EOS Core Data
    CREDENTIAL > Credentials for an EOS account (a generic helper account can be used in some cases)
    RESOURCE
        > User
        > App
        > Account
        > Team
        > Role
        > Log
    OPERATION
        > User
            > Get All List (Retrive a list of all users in a particular account)
            > Get All Details (Retrive an object containing details of all users under a particular account) (*High load)
            > Get (Retrive the details of a particular user, searchable by any field)
            > Create (Add a new user)
            > Update (Update the details of a particular user)
            > Delete (Remove a user)
        > App
            > Get All List (Retrieve a list of all apps in a particular account)
            > Get All Details (Retrieve an object containing details of all apps in an account)
            > Get (Retrieve the details of a particular app)
        > Account
            > Get All List
            > Get All Details
            > Get
            > Create
            > Update
        > Team
            > Get All List
            > Get All Details
            > Get
            > Create
            > Update
            > Delete
        > Role
            > Get All List
            > Get All Details
            > Get
            > Create
            > Update
            > Delete
        > Logs
            > Get All Details
            > Create
