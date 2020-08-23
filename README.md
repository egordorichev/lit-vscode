# Lit syntax highlighting support for Visual Studio Code

Syntax support for [Lit](https://github.com/egordorichev/lit).

#### Instalation

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

```
ext install egordorichev.lit-lang
```

For best results, add the following section to your `settings.json`:

```json
"editor.tokenColorCustomizations": {
	"textMateRules": [
		{
			"scope": "constant.character.interpolation.lit",
			"settings": { "foreground": "#fff" }
		},
		{
			"scope": "comment.expected.lit",
			"settings": { "foreground": "#1e6f50" }
		}
	]
},
```

You can also view the package on [VS Market Place](https://marketplace.visualstudio.com/items?itemName=egordorichev.lit-lang).
