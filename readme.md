# DEPLOYMENT PLAN
## Follow this procedure to update the Portfolio project

1. Head to the master branch
  * $ git checkout master
2. Get the most recent version of the project
  * $ git pull github master
    - github is the remote name for the github repository
3. Merge the feature(s) to be tested with the master branch
  * $ git merge <New Feature>
4. Resolve any conflicts from the merge
5. Test application for any bugs/failures
  * Failures must be fixed before proceding
6. Push new working version to github
  * $ git push github master
7. Push new working version to production server
  * $ git push LiveServer master
    - LiveServer is the remote name for the production server

