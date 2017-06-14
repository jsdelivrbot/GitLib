## **GitLib** 

<img width="100" alt="img" src="https://rawgit.com/stylekit/img/master/GitLib.svg">

- works by utilizing shell and git (CRUD)

```swift
GitParser.status("~/test/","-s")//Outputs the status (compact version)
GitModifier.commit("~/test/", "Bug fix", "Fixed the bug in the code")
GitAsserter.isGitRepo("~/test/.git/")//Output: true or false
```
