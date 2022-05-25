## Pipeline process:

- You push the code from your computer to GitHub
- CircleCi will detect that and start these steps
  1. install node and npm
  2. set up the AWS clis
  3. install all dependencies and build the app
  4. deploy on aws s3 and eb
- The App is now deployed --Nice :)
