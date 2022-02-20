

# Notes
The toolbox seems gonna have a lot of dependencies(which is not good consider the Jenkins plugins).
We should avoid having too many dependencies.


```
.
├── README.md
├── network(network tools)
│   └── root
│       └── root.go
├── shell(generic shell syntex)
│   └── root
│       └── root.go
├── database(useful SQLs)
│   └── root
│       └── root.go
├── storage
│   └── root
│       └── root.go
├── cheatsheet(like gist, a group of commands)
│   └── root
│       └── root.go
└── main.go
```



Refs:
* https://github.com/spf13/viper
* https://github.com/spf13/cobra/blob/master/user_guide.md
* https://copilot.github.com/