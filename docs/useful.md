<!-- (dl (section-meta Useful Tool)) -->

The templates provided through this project are designed to utilizes [gittey](https://www.npmjs.com/package/gittey) to make things easier. Gittey is not required but useful.

Gittey is a command runner with understanding of git.

To install:

`npm i -g gittey`

<!-- (dl (# Useful commands)) -->

<!-- (dl (## To run the tests)) -->

`gittey test`

This will run tests and commit the code if the tests pass

<!-- (dl (## To commit code)) -->

`gittey commit`

This will commit code with prompts, including message.

<!-- (dl (## To undo current work)) -->

`gittey undo`

This will reset the directory to the last commit