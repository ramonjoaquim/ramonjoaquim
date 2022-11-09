```go
package main

import "fmt"

type Workplace struct {
	company  string
	position string
}

func main() {
	fmt.Println("Bio:", getBio())
	fmt.Println("Current WorkPlace:", getCurrentWorkplace())
	fmt.Println("Daily Knowledge:", getDailyKnowledge())
	fmt.Println("Future Goal:", getFutureGoal())
}

func getBio() string {
	return `Bachelor in Information System, Full Stack Developer with knowledge about DevOps culture, 
	API development and also functional and automated tests.`
}

func getDailyKnowledge() []string {
	return []string{
		"Java",
		"AngularJS",
		"Kubernetes",
		"Javascript",
		"MongoDB",
		"NestJS",
		"AWS",
		"GitLab",
		"Flutter",
		"React"
	}
}

func getFutureGoal() []string {
	return []string{
		"Go",
		"SpringPatterns",
		"GraphQL",
	}
}

func getCurrentWorkplace() (currentWorkPlace Workplace) {
	currentWorkPlace = Workplace{
		company:  "Betha Sistemas",
		position: "Full-Stack developer",
	}
	return
}
