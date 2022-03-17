
# Download Go
https://go.dev/

# Execute hello program in powershell
* go mod init example/hello
* go: creating new go.mod: module example/hello
* create hello.go and paste the code from  https://go.dev/doc/tutorial/getting-started
* click go run .

# Commands used to execute the wordcount in powershell
* go version
* go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
* go install github.com/apache/beam/sdks/v2/go/examples/wordcount
* go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37
* wordcount --input sample.txt --output machhacounts
