# serve
 (Very) simple web serve in go.

 ## Building

```bash
GOOS=windows GOARCH=amd64 go build -o serve-windows-amd64.exe main.go
GOOS=windows GOARCH=386 go build -o serve-windows-x86.exe main.go
GOOS=darwin GOARCH=amd64 go build -o serve-darwin-amd64 main.go
GOOS=darwin GOARCH=arm64 go build -o serve-darwin-arm64 main.go
GOOS=linux GOARCH=amd64 go build -o serve-linux-amd64 main.go
GOOS=linux GOARCH=386 go build -o serve-linux-x86 main.go
GOOS=linux GOARCH=arm go build -o serve-linux-arm main.go
GOOS=linux GOARCH=arm64 go build -o serve-linux-arm64 main.go
GOOS=linux GOARCH=riscv64 go build -o serve-linux-riscv64 main.go
```