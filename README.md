<h2 align="center">About me</h2>

```golang
package main
import (
	"fmt"
)
type Bio map[string]string
func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}
func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "A kind of cyberPunk-gamer-coder-programmer-dogLover hybrid",
		"- 🌱 I’m currently learning":        "JavaScript and C++",
		"- 📫 How to reach me:":              "Discord: IPandral",
	}
}
```
