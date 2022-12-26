# Pipeline process

the pipeline works with the following sequence

1. build
   with the folloing steps:
   - install nodejs ver 16.13
   - checkout code
   - install frontend Dependencies
   - install backend Dependencies
   - linting frontend
   - Build frontend
   - Build backend
2. hold

   - must be approval manually

3. deploy
   - setup Elasticbeans Talk
   - install AWS cli
   - configure AWS With credintial
   - checkout code
   - start deployment procees for backend and frontend
