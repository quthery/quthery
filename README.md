```go
package main

import "github.com/quthery"

const (
    Name        = "Quthery"
    MainLang    = "Go"
    OtherLangs  = "Python, C++, Lua"
    FocusAreas  = "Backend, Distributed Systems, CLI Tools"
)

func main() {
    quthery.Bio(
        Name,
        "Senior Backend Engineer",
        "Passionate about efficient, clean code",
    )
    
    quthery.Skills(
        Languages: []string{MainLang, OtherLangs},
        Tools:     []string{"Docker", "K8s", "PostgreSQL", "gRPC"},
    )
    
    quthery.CurrentProject("High-performance microservices framework in Go")
}

<div align="center">

Go Reference
GitHub
go

fmt.Println("Let's build something great in Go!")

</div> ```
