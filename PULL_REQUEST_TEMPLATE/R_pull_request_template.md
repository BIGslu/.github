*This template is for pull requests made to R packages.*

**Describe the purpose of these changes**
A clear and concise description of what the bug or feature request this pull request addresses. Link to a current GitHub issue if available.

**Tests**
Verify that you have completed the following tests by checking the appropriate box. All tests must pass prior to merging with the main branch.

- [ ] All code contains sufficient commenting
- [ ] `check( )` completes with no errors or warnings
- [ ] If the changes impact a function, the new function was tested on Mac and Windows OS
- [ ] If the output is changed and is used as example data in another BIGslu package, these changes do not disrupt the other package's workflow. This can be done but running `check( )` within the other package with your changes from this packages are loaded with `load_all( )`
