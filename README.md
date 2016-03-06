# travis-example

Adapted from https://docs.travis-ci.com/user/for-beginners

1. On GitHub, fork this repository.
1. Clone the repository `git clone {repository url}`
1. <a href="https://travis-ci.org/auth">Sign in to Travis CI</a> with your GitHub account, accepting the GitHub access permissions confirmation.
1. Go to your <a href="https://travis-ci.org/profile">profile page</a> and enable Travis CI builds for your fork of the travis-example repository.
1. Take a look at .travis.yml, the file which tells Travis CI what to do. This file tells Travis CI to install the dependencies and run npm test.
1. Edit the empty NewUser.txt file by adding your name to the empty file. Add the file to git, commit and push, to trigger a Travis CI build:
`$ git add .`
`$ git commit -m 'Testing Travis CI'`
`$ git push`
1. Wait for Travis CI to run a build on your fork of the travis-example repository, check the <a href="https://travis-ci.org/repositories">build status</a> and notice that the build fails. (Travis CI sends you an email when this happens)
1. Fix the code by making sure that 2=1+1 in tests/test.spec.js, commit and push to GitHub. This time, the build does not fail.
`$ git add .`
`$ git commit -m 'Testing Travis CI: fixing the build'`
`$ git push`
Congratulations, you have added a GitHub repository to Travis and learnt the basics of configuring builds and testing code.
