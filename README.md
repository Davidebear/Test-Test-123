# This is a test repository
- I have no idea how to use Markdown. I should probably learn how to do it.
- I do know that at the very least "#" is used to indicate varying sizes of bold headers. Let's do some test runs.
- I need to highlight these ==very important words==.
- *Electronics for Inventors*

- [X] Learn how to create a local repo using Git on the CLI.
- [ ] Master git commands.
- [ ] Learn --verbose and -v uses in CLI 
- [ ] Learn how to deal with merge conflicts in git


## --- Some Nice Tips to Remember ---
Git has three config files: <br>
--local stored in .git/config for repositories
--user stored in ~/Users/gitconfig for users
--system stored in the OS for the entire system

# Setting up a remote repo
The steps involve ensuring that 1) you are on a branch named origin, 2) remote added the branch to the remote repo, 3) push your existing branch to the remote repo
'git branch -M origin'
'git remote add origin git@github.com:Davidebear/Test-Test-123.git'
'git push -u origin origin'

note the syntax of the url and -u (git push will work in the future now)
