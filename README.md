# beam-go
## commands used for this project:
### Install Go:
[Go](https://go.dev/doc/install)
### check GO version:
        go version
### command to create go.mod file to track your code's dependencies:
        go mod init go mod init github.com/Saisumithra/beam-go 
###  To Get the SDK and examples:
        go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
### Installed wordcount example:
        go install github.com/apache/beam/sdks/v2/go/examples/wordcount
### executing a wordcount.go with sample input file.
        go run wordcount.go --input sample.txt --output sumithra
### If, i run the above command i got error so i used:
        go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0
### Again execute wordcount.go then we will get the wordcounts:
          go run wordcount.go --input sample.txt --output sumithra
