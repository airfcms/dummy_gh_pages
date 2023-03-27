{% for key, value in versions.items() %}- {{key}}
{% for note in value.notes %}	- {{note.title}}
		- {{note.description}}{% endfor %}{% endfor %}