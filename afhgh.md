BACKEND DEPLOYMENT

     STEPS:
     Open pycharm terminal or cmd
        STEP 1:- Then run the following command.
                    > ssh user_name@ip and after running the command
                      enter password
        STEP 2:- By using cd set the folder where the project is located.
        STEP 3:- Then run the following command.
                  i) sudo docker build -t {project name and version} .
                  
                  So for eg if my project name is tag-id-admin-api and version is v3.1.0
                  So the command will be 
                  sudo docker build -t tagid-admin-api:v3.1.0 .

FRONTEND DEPLOYMENT

      STEPS:
          STEP 1:- By using cd set the folder where the project is located.
          STEP 2:- Then run the following command.
                  i) sudo docker build -t {project name and version} .
                  
                  So for eg if my project name is tagid-(Organization Name)-ui and version is v3.1.0
                  So for chunmun org the command will be 
                  sudo docker build -t tagid-chunmun-ui:v3.1.4 .
                  So for su org the command will be 
                  sudo docker build -t tagid-su-ui:v3.1.4 . And so on.
                  
                  
AFTER COMPLETEING THE ABOVE PLEASE FOLLOW THE FOLLOWING

      STEP 1:- Go to localhost:9000
      STEP 2:- Images 
      Pls refer the following
![Uploading Screenshot from 2023-05-24 16-15-57.png…]()
      STEP 3:- 



                  
                  
                  
