# Day 00 - War

<br>

###  How to install go

a. Download the binary from [here](https://golang.org/dl/)

b. Extract the binary to `/usr/local`:

```bash
sudo tar -C /usr/local -xzf goversion.opereting-system-arch.tar.gz
```

c. Add `/usr/local/go/bin` to your `PATH`

```bash
# Add this to your ~/.bashrc or ~/.zshrc
export PATH=$PATH:/usr/local/go/ # Necessary
export PATH=$PATH:/usr/local/go/bin # Optional
export GOBIN=$HOME/usr/local/go/bin # Optional
```

d. Verify the installation by running `go version`

<br>

------------

# Go Basics

### Some Go Commands

`go run` - Compiles and executes the program

`go build` - Compiles the program

`go fmt` - Formats the program

`go install` - Compiles and installs a package to the workspace's `bin` directory (usually `$GOPATH/bin` or `$GOBIN`)

`go env` - Prints Go environment information
