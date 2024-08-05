# 1. Setting up Go env

## 1.1 Your first Go program

### Go Module

```shell
mkdir "hello_world"
cd hello_world
go mod init hello_world
```
> go: create new `go.mod`: module hello_world

- Go project is called **module**.
- A module is not just a source code, it's also an exact specification of the dependencies of the code within the module
- The `go.mod` file declares:
  - Name of the module
  - Minimum supported version of Go for the module
  - Other modules that your module depends on
  - 