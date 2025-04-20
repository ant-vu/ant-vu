```go
package main

import "fmt"

type Profile map[string]any

func main() {
    anthonyVu := Profile{
        "workExperience": "SWE @ Citi",
        "education":      "McMaster CS '24",
        "awards":         "Schulich Leader '20",
    }

    fmt.Println(anthonyVu)
}
```
