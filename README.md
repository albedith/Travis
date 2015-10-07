# Travis with Sauce Labs Tutorial
These are the steps that I had to follow in order to get the Sauce Labs + Travis CI Integration tutorial working.

1. Make a repository (e.g Travis)
2. In the repository create a file called ".travis.yml"
3. Go to https://travis-ci.com/ and Sign In
4. Go to your Travis profile (e.g https://travis-ci.org/profile/albedithdiaz)
5. Click on "Sync" and make sure your repository is visible there
6. Flick the repository switch ON
7. Follow the instructions here: https://docs.saucelabs.com/ci-integrations/travis-ci/#adding-credentials-for-a-public-github-repo
8. Copy and add your encypted Sauce Labs credential in the ".travis.yml" file
9. Add your tests to the Travis repository
10. Edit the ".travis.yml" file with your tests details
11. Add/Commit and Push your changes - This will trigger the Travis build to run
12. Spy on your running build (e.g https://travis-ci.org/albedithdiaz/Travis)
