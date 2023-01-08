# web3-detective
Brownie-compatible tool for restoring the chain of events and test case generation

## installing
Just clone repo into /scripts/ repository of brownie project:
`chdir scripts/`
`git clone https://github.com/drLis/web3-detective`

Or you can do it with git submodule for long-term using:
`chdir scripts`
`git submodule add https://github.com/drLis/web3-detective`

## using
Just run `web3-detective/detective.py` with brownie run command and pass set of contract addresses, which was used:
`run("web3-detective/detective.py", "main", [{python set of your contract addresses in selected network}])`