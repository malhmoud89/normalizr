#How to contribute
Found a problem? Know how to fix it? Great! Your contributions are extremely important. Think of this guide as grease in the wheels to keep the contribution process slippery smooth for you.

##At a glance
The basic rules of contributing to this project are:

1. Make the commits logical, simple and concrete
2. Cover your changes with unit tests.
3. Run all existing unit tests.

##Getting started
Thought of something that would be a neat addition to the project? Found a bug you want to fix? Either way, the first step is always the same, branch the repo. Most of the time you'll want to branch from master, so do that. Give your branch a sensible name, and start committing to it. Ensure your commits are sensible, have reasonable messages, and don't encapsulate too many changes at once.

##Trivial changes
Trivial changes are welcomed at this repository, which are defined as any change that makes no modification to functional code. Changes to comments, XML documentation comments or non-code files can all be considered trivial changes, regardless of their scope or size.

With trivial changes, the rules on testing are relaxed. Since no code has changed, tests do not need to be run. If your changes somehow break the tests when I run them though, your pull request will be denied, so you might as well make sure.

##Before you submit your pull request

Once you have made enough changes to enact your vision, it's almost time to submit a pull request from your branch to master.

First, make sure you've suitably covered your changes with unit tests. Aim to follow the naming and style of the unit tests that already exist in the repository.

    public void MethodName_TestSomeFunctionality_ExtraInfo

You don't have to provide 100% coverage, but any untested code must be trivial.

Next, run all the tests. Not just yours, all of them. When all of the tests pass, do your best to clean the code as much as you can.

With that all done, submit your pull request and wait impatiently for somebody to review and, hopefully, approve it.

Thank you for making the effort to make this free utility even better.