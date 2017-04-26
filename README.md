## Go Source From AST  
Go Program that takes in a Go file, parses it into an AST, and then rebuilds the source from the AST.  
### How to run  
`go build main.go`   
`./main filename`  
### Notes  
Could execute with  
`go run main.go filename`  
However, the filename should NOT have the extension '.go'  
go run will attempt to execute the file, when it should be interpreted as a filename  
### Version  
Developed on  
go version go1.7.5 darwin/amd64 
