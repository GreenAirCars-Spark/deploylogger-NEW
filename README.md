# DeployLogger

A command line tool that wraps 'goapp deploy' it'll neatly log what was
deployed to app engine in a json file.


## To install
Clone this repo and run 'go install'

## To run
Execute 'deploylogger help' in your apps directory to bring up the help menu

Deployments are logged in the following format : {Time, git commit hash, application id}
