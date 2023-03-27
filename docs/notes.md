{% for key, value in versions.items() %}- {{key}}
	- {{value.notes.title}}
		- {{value.notes.description}}{% endfor %}