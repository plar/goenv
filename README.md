## GoEnv - Simple virtual enviroment manager for Go lang

#### Create Go virtual enviroment

```
plar@devel:~/workspace$ goenv project1
Create [project1] environment
Activate [project1] environment
(project1) plar@devel:~/workspace$ _

```
Create a *project1* directory with *bin*, *src* and *pkg* subdirectories and 
activate it (set GOPATH and update PATH shell variables)

#### Deactivate Go virtual enviroment
```
(project1) plar@devel:~/workspace$ exit
exit
plar@devel:~/workspace$ _

```

#### Activate Go virtual enviroment in the current directory or try to search virtual enviroment in the parent directories 
```
plar@devel:~/workspace$ cd project1/
plar@devel:~/workspace/project1$ goenv
Activate [project1] environment
(project1) plar@devel:~/workspace/project1$ _

```

It also works from subdirectories

```
plar@devel:~/workspace$ cd project1/pkg
plar@devel:~/workspace/project1/pkg$ goenv
Activate [project1] environment
(project1) plar@devel:~/workspace/project1/pkg$ _

```
