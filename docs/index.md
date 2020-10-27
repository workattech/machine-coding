Please go through this document to participate in the machine coding round by workat.tech

## Why Mock Machine Coding Round?
- In companies like Flipkart, Uber, Swiggy, Ola, Cred, etc the first onsite round is the <a href="https://workat.tech/machine-coding/article/what-is-a-machine-coding-round-omfn1w54ojlg" target="_blank">machine coding round</a>.
- You're given a design problem (like design a parking lot) with a set of requirements.
- Then you need to create a clean, modular and extensible coding solution for the same.
- The code is supposed to be written in a matter of 2-3 hours.
- After the round, you sit with an interviewer who goes through your code and tries to understand your design decisions and also tries to see if your code works for all the requirements.
- The interviewer may ask you to extend your solution based on some new requirement.
- It is a pretty crucial round since most of the people get eliminated in this round and it is completely different from what everyone generally practices for.

## How to prepare?
Please go through our article on '<a href="https://workat.tech/machine-coding/article/how-to-prepare-for-machine-coding-round-naf2ih7a9e5l" target="_blank">How to prepare for machine coding round?</a>'.

## What to do during the round?
Please go through our article on '<a href="https://workat.tech/machine-coding/article/how-to-ace-machine-coding-round-hi8lnpp8tlmo" target="_blank">How to ace the machine coding round?</a>'.

## Event Format
- Go through the problem statement at [this link]().
- You can go through the problem statement and think about the solution for 30 mins.
- You'll have 2 hours to code the solution and put it on Github. More details on how to do it is available in the [setup section](#setup) below.
- If you're unable to complete it in 2 hours, it is totally fine. Please submit it whenever you're done though it would be good if you can do it in 2 hours.
- Run the tests to verify the functional correctness of your solution.
- Submit your solution based on the [submission section](#submission) below.
- We'll try to evaluate everyone's submission if the code passes the functional tests.
- We recommend you to go through the submissions of other people as well to learn different approaches and also to provide feedback.

## Setup
- Ensure that you've a github account. If you do not have one, check <a href="git#create-github-account" target="_blank">this page</a>.
- Ensure that you've git set up locally on your Laptop/PC. If it is not set up, check <a href="git#install-git-locally" target="_blank">this page</a>.
- Go to <a href="https://github.com/workattech/mock-machine-coding-1" target="_blank">mock-machine-coding-1 repository</a>.
- Fork the repository. If you're new to git, follow the steps mentioned <a href="git#fork" target="_blank">in the fork section here</a>
- Clone the repository in your local machine.If you're new to git, follow the steps mentioned <a href="git#clone" target="_blank">in the clone section here</a>
- If you are on Windows then install the [ubuntu terminal](https://ubuntu.com/tutorials/ubuntu-on-windows). It is mandatory to run the tests.
- Make sure that you have java/g++/python2/python3 installed based on your language preference

## Coding
- After the setup step, a new folder will be created in your laptop/PC.
- Open that folder in an IDE of your choice.
- Write your code in the respective language folder present in the solution directory
- Do not modify the directory structure or the tests would fail
- The driver code should be in the main method specified in the driver file
- The input needs to be taken from standard input in the main method
- The output needs to be printed to standard output
- Create classes for the core logic following best coding practices

## Testing
- Your code will be run on some predefined input and the output will be compared with the expected output
- The input and expected output is mentioned in the tests directory
- Run the following command from the repository home directory:
  - ```bin/test lang``` where lang could be java/cpp/py2/py3

## Expectations
- Make sure that you have a working and demonstrable code
- Make sure that the code is functionally correct
- Code should be modular and readable
- Separation of concern should be addressed
- Please do not write everything in a single file
- Code should easily accommodate new requirements and minimal changes
- There should be a main method from where the code could be easily testable
- [Optional] Write unit tests, if possible
- No need to create a GUI

## Problem Statement
To be added

## Submission
- After you're done with coding and testing, you need to commit and push your changes to github.
- Submit the code for review only if all tests get passed
- You should push your changes to the master branch of your forked repository. If you're new to git, follow the steps mentioned <a href="git#push-local-changes-to-remote" target="_blank">in the push local changes to remote section here</a>
- Create a pull request to our master branch. If you're new to git, follow the steps mentioned <a href="git#pr" target="_blank">in the PR section here</a>
- Mention the language in the PR title

## Evaluation
- We'll be reviewing everyone's submission if all the tests are passing.
- We'll try to provide feedback on how to improve through code review comments on GitHub.
- We also have some volunteers who will help with the review.
- Anyone can volunteer to review.

## Contact us
If you need any help regarding this:
- Ping us on <a href="http://bit.ly/machine-coding-chat" target="_blank">WhatsApp</a>
