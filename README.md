# Git workflow
## SVN?
- an open-source, centralized version control system
- a single central repository as the communication hub for developers
- collaboration takeing place by passing changesets between the developers’ working copies and the central repository
## Git?
- a mature, actively maintained open source project originally developed in 2005 by Linus Torvalds, the famous creator of the Linux operating system kernel 
- an example of a DVCS (hence Distributed Version Control System)
- every developer having their own copy of the repository, complete with its own local history and branch structure

## Workflow?
>A workflow consists of an orchestrated and repeatable pattern of business activity enabled by the systematic organization of resources into processes that transform materials, provide services, or process information.

## Git Workflow?
>A Git Workflow is a recipe or recommendation for how to use Git to accomplish work in a consistent and productive manner. 

### Why Git?
- branching capabilities
- distributed development
- pull request
- faster release cycle

## Common Git Workflows for Software Teams

### Centralized Workflow
- transitioning from SVN
- a central repository as the single point-of-entry for all changes to the project
- the default development branch being called master and all changes being committed into this branch
- no requiring any other branches besides master

### Feature branching
- a logical extension of Centralized Workflow
- all feature development taking place in a dedicated branch 
- easy for multiple developers to work on a particular feature without disturbing the main codebase
- master branch always containing production-quality code

![](https://sfault-image.b0.upaiyun.com/135/687/1356871362-56fe09a564c99_articlex)

### Gitflow Workflow
- a strict branching model designed around the project release
- not new concepts or commands beyond what’s required for the Feature Branch Workflow
- assigning specific roles to different branches and defining how and when they should interact

![](https://sfault-image.b0.upaiyun.com/221/358/2213586864-56fe8ad48caf1_articlex)

### Forking Workflow
- every developer having a server-side repository means each contributor having two Git repositories: a private local one and a public server-side one 

![](https://sfault-image.b0.upaiyun.com/348/941/3489415854-56feaa016d70d_articlex)
