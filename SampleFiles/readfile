package main

import (
	"io/ioutil"
    "os"
    "fmt"
)
func main() {
	fn := os.Args[1]
	file, err := ioutil.ReadFile(fn)
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error reading file\n")
		os.Exit(-1)
	}

    fmt.Printf("%s", file)
    
}
