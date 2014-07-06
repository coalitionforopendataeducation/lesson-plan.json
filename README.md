lesson-plan.json is a flexible standard to capture the content, learning objectives, skills, and Mozilla Badges that is intended to complement tutorials, courses, and other learning opportunities in a GitHub repository. This repo contains documents that specify the keys and values that make up the lesson-plan.json data standard, and provides information about the scope, mission, and background of the standard.

lesson-plan.json exists to create an opportunity to index free data science-oriented learning modules that exist on GitHub.
A specification of the lesson-plan.json, a flexible metadata standard for learning modules that indexes the content within courses and tutorials.

lesson-plan.json looks like this:
```json
{
	"module": "Example Title of Learning Module",
	"creation date": "yyyy-mm-dd",
	"last modified": "yyyy-mm-dd",
	"repository": "https://github.com/coalitionforopendataeducation/ggplot2-introduction",
	"Languages": [
		"R",
	],
	"language modules": [
		"ggplot2",
	],
	"supporting languages": [
		"xml",
	],
	"badges": [
		"ggplot2 beginner",
		"web data scrapper beginner",
	],
}
```