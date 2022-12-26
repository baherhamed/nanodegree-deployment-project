# Infrastructure description

- This project required :
  1. RDS Database with username and password.
  2. Elasticbeanstalk used to add backend environment and add variables.
  3. S3 used to add frontend files.
  4. CircleCi after upload project to Github you should follw the project via githup account with the following steps
     - login CircleCi.com with githup account
     - select project that we need to follow
     - set environment from Tab Project Setting> Envaironment Variable we pass required AWS Credintials .
     - after any push to git hup repository circleci will detect changes autotmaticly.
