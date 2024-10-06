# COMP3104 - DevOps, Assignment 01: Group 60

[![Build Status](https://app.travis-ci.com/taylormarz/COMP3104_Group60_Assignment.svg?token=bGad9p6xEapvxKocD54N&branch=main)](https://app.travis-ci.com/taylormarz/COMP3104_Group60_Assignment)

#### Group Members:
**Leader:** Taylor Martin (`100849882`) [Taylor's GitHub](https://github.com/taylormarz) <br>
**Member 2:** Ethan Sylvester (`101479568`) [Ethan's GitHub](https://github.com/AnEdgyVeggie) <br>
**Member 3:** Justin Oskam (`100851894`) [Justin's GitHub](https://github.com/J-Oskam) <br>
**Member 4:** Amanda Gurney (`101443253`) [Amanda's GitHub](https://github.com/TheGeneralJay) <br>

#### Project Description:
// filled out by justin

#### Instructions:
Step 1: Clone the repository to your local machine.<br>command: git clone https://github.com/taylormarz/COMP3104_Group60_Assignment.git

Step 2: Create/switch to your own branch.<br>command: git checkout -b your-new-branch-name

Step 3: Push your new branch to the remote repository.<br>command: git push -u origin 'your-new-branch-name'

// add other steps if you guys think we need them - otherwise delete this line

#### CI/CD Details:
This project is utilizing the Travis CI tool for continuous integration.
All branches of this repository have also been set up successfully through Travis.
An example of the files/packages needed to do this can be found in the ci-files directory.

#### Branching Strategy:

The purpose of a branching strategy is threefold:
    - Protect the main branch (the deployed product) from errors, vulnerabilities or code that has not been quality checked and peer reviewer
    - Enable developers to work on / introduce seperate features or aspects into a project without having to frequently update and / or pull everything everyone is working on at the same time which would introduce breaking bugs throughout the entire process
    - Enable peer review, QA checks, and safety checks through pull requests.

Our branching stategy was to use a 'per-developer' branch as opposed to a 'per feature'. This means that every developer involve had their own branch to commit their own code. When working with Travis, each developer had their own package.json which created a merge conflict. This was easily remedied through github's application and allowed for seamless integration of each developers code into the main branch.

At this point, we left out branches open, although they can be closed if needed. We determined that there was no sense in closing branches that could potentially be used again, and would therefore be recreated, wasting development time. 