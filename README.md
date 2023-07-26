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
		- 🔭 I am currently enrolled in The Institution of Bloom Technology working on my Data Science degree. I am developing a strong foundation of skills in analyzing data and in Python.
		- 🌱 This year my family and I have started a farmers market stand, bought and r chickens and built a greenhouse. When I am not working I love to spend my time helping them.
		- 👯 I’m looking to collaborate on books. My favorite genre is fantasy.
		- ⚡ I’m looking for connections in the data science industry to grow both my social connections and improve myself academically.
		- 😄 Fun fact: Chickens are living decendents of dinasours.
		- 📫 How to reach me: sheyer0597@gmail.com

		Thanks for stopping by, and happy coding! 😄
	}
}
