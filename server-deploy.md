# iWish Deployment Documentation

This document provides a step-by-step guide on how to deploy the iWish application, both for the front-end and back-end components.

## Front-end Deployment

Follow these steps to deploy the front-end component of the iWish application:

1. **Navigate to the front-end directory**: Change the current working directory to the iWish client folder by running the following command:

   ```
   cd test-dev/iwish-client
   ```

2. **Check the current branch**: Determine which branch is currently deployed by running the following command:

   ```
   git branch
   ```

3. **Pull the latest changes**: Update the current branch with the latest changes from the remote repository by running the following command (replace `{currentBranchname}` with the actual branch name):

   ```
   git pull origin {currentBranchname}
   ```

4. **Restart the front-end application**: Restart the iWish client application using PM2 by running the following command:

   ```
   pm2 restart iwish-client
   ```

## Back-end Deployment

Follow these steps to deploy the back-end component of the iWish application:

1. **Navigate to the back-end directory**: Change the current working directory to the iWish server folder by running the following command:

   ```
   cd test-dev/iwish-backend
   ```

2. **Check the current branch**: Determine which branch is currently deployed by running the following command:

   ```
   git branch
   ```

3. **Pull the latest changes**: Update the current branch with the latest changes from the remote repository by running the following command (replace `{currentBranchname}` with the actual branch name):

   ```
   git pull origin {currentBranchname}
   ```

4. **Restart the back-end application**: Restart the iWish server application using PM2 by running the following command:

   ```
   pm2 restart iwish-server
   ```

After completing these steps, both the front-end and back-end components of the iWish application should be successfully deployed and running with the latest changes.
