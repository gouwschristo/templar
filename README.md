### Templar renders Jinja2 compatible templates from JSON data read from file/stdin.

```
Usage:
	templar <template> <json input>
	stdout | templar <template>
```



Example:

`templar template_file '"firstname": "Foo", "lastname": "Bar"'`

template_file

```
First Name: {{ templar.firstname }}
Last Name: {{ templar.lastname }}
```
