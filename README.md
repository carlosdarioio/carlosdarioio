```go
package main

import (
    Kian "https://github.com/carlosdarioio/"
)

func main() {
    var Me *Kian.About = &Kian.About{
        Name  : "Carlos Dario Flores",           
        Age        : 31,
        Job        : "Full time developer work at Copemsa",
		Job2        : "Part-time Programmer Analyst job at GRT",
        Interested : []string{
            "Start PhD",
            "Web, mobile or backend projects",            
            "Teach and learn",
        },
        Hobbies    : []string{
            "Study",
			"WeRunHN",
			"To meditate",
			"Pokemon",
			"RPG"
        },
    }
}
```
