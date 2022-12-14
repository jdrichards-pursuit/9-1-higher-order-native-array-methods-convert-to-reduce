# Higher Order Native Array Methods Convert To Reduce Lab

`.reduce` may not always be the best use case to solve a problem. But knowing how to use such a strong method, **THE STRONGEST OF ARRAY METHODS!** , is worth your while. You have both song and vote data to work with in this exercise. Use your knowledge of `.reduce` to solve all the problems you formerly solved with `.map`, `.filter`, `.find`, `.some`, and `.every`.
Plus solve a few new problems that you have not solved before.
**Good Luck!**

## Getting started

1. Fork and clone this repository.

1. Navigate to the cloned repository's directory on your command line. Then, run the following command:

   ```
   npm install
   ```

   This will install the libraries needed to run the tests.

1. Open up the repository in VSCode. Follow the instructions below to complete the Lab.

## Instructions

Complete each function inside of the `src/` folder. The comments and tests will help you determine what each function requires.

### Tests

\*\*You must manually test the `src/01-reduce-no-tests.js` file\*\*

#### To test `src/01-reduce-no-tests.js` locally in terminal:

1.  Uncomment appropriate `console.log` line
1.  In terminal type `node src/01`
1.  Push `tab`
1.  Push `ENTER`
1.  When you are done, re-comment the `console.log` line you uncommented

#### To test all other files using Jest

To run the tests, you can run the following command from the command line. You will need to be in the root directory of your repository.

```
npm test
```

This will run the test output once.

#### Test watcher

If you'd like, you can have the tests run constantly. This means that each time you save your file, your tests will re-run. To do so, you can run the following:

```
npm run watch
```

Follow the on-screen prompts to exit out of the constant runner.

### Run test files individually

There are a lot of tests that are contained in this lab. You can run a single test file individually by putting the name of the file after `npm test`. You can even only put part of the file name.

```
npm test 01
```

### Run tests individually

_After choosing a specific file to run,_ you can also specific which test you want to run, specifically. Add `.only` after either `test` or `describe` for the specific test you'd like to run.

```js
test.only("should return an array of everyone's name who is in the line, in order", () => {
```

This will either run the specific `test` or, in the case of adding `.only` to a `describe`, all of the tests for a specific function.

> **NOTE:** Don't forget to remove this after you get the test to pass!

### Run file

If you want to manually test out your file, you can do so by running the following command.

```
node index.js
```

The output will be printed to your terminal.
