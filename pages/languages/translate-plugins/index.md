# Translate a plugin
<!-- position: 1 -->

Each plugin has a folder `languages`; inside this folder you can create the different dictionary files for each language.

```
/bl-plugins/{PLUGIN_NAME}/languages/
	de_DE.json
	en.json
	es.json
	fr_FR.json
	...
```

<div class="note">
<div class="title">File Encoding</div>
All dictionary files are <b>JSON</b> files and are encoded in <b>UTF-8</b>.
</div>

This is an example of an English dictionary (`en.json`). Each line in `en.json` file is a key-value pair, with the key on the left and the value on the right.

```
{
	"plugin-data":
	{
		"name": "Page list",
		"description": "Shows the list of pages in order."
	},

	"home": "Home",
	"show-home-link": "Show home link"
}
```

As you can see, you have a field called `plugin-data`, this has the name and description of the plugin; and the next fields are phrases for the plugin as `home` and `show-home-link`.

This is an example of a Spanish dictionary; the file is located in `/bl-plugins/{PLUGIN_NAME}/languages/es.json`.

```
{
	"plugin-data":
	{
		"name": "Listado de paginas",
		"description": "Muestra el listado de paginas en orden."
	},

	"home": "Inicio",
	"show-home-link": "Mostrar link de la pagina de incio"
}
```
