 install go
[X] create a folder with name "beam-go"
[X] go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
[X] go install github.com/apache/beam/sdks/v2/go/examples/wordcount
[X] go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0
[X] go build wordcount.go
[X] .\wordcount --input sample.txt --output out1.txt
[X]  Get-Content out1
