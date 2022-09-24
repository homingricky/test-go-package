# test-go-package

Steps to publish a go package and import it in another package

Inside the package you want to publsih

1. ```go init github.com/{username}/{repository_name}```

2. ```go tag "v1.0.0"```

3. ```git push --tags```

Import the publsihed package

```go get github.com/{username}/{repository_name}@{version}```

