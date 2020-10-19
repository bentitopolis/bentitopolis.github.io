### All things tofel.tech

## Java

## Kubernetes (k8s)

## Python for Machine Learning

## IDEs
- My favorite IDEs and what I use them for:

| IDE      	| Language 	| Notes                                                 	|
|----------	|----------	|-------------------------------------------------------	|
| PyCharm  	| Python   	| install numpy, scipy & allow added interface features 	|
| IntelliJ 	| Java     	|                                                       	|
| IntelliJ 	| Go       	| Install the plugin for Go, better than GoLand         	|
| IntelliJ 	| yaml     	| syntax highlighting & error checking                  	|
| DataGrip 	| SQL      	| also built-in to PyCharm, IntelliJ                    	|

# Best tips for using IntelliJ with Java
- For Maven based projects, find the `pom.xml` and open it under `New` `Project from Existing Source...`
# Best tips for using IntelliJ
- Use the VCS->git tools for many common git operations, but mix in cli commands where they are better/easier, the built-in git will figure out what's going on. For instance, `git pull --rebase master <branch>` is very handy from the cli. When you are confronted with merge conflicts, jump back to IntelliJ and look in the git pane, you will be offered chance to resolve conflicts graphically. When done, `git rebase --continue` on the cli.
