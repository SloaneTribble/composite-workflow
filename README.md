This is an action designed to be used in other workflows.  

Takes one **optional** input, a string representing a name.

If applicable, the optional input will be appended to a string which is output by this action.  Otherwise, this action will output a default string.  

Also outputs a random number to $GITHUB_OUTPUT, which the runner may use.  

This action also demonstrates using github.action_path to add its path to the runner's system path so that the runner can make use of a script, goodbye.sh