# My LaTeX template

1. Add the following bash function to your bashrc
```sh
function tex_tpl() {
	git clone https://github.com/homerours/latex_style.git;
	cp latex_style/example.tex ./$1.tex;
	cp latex_style/gitignore ./.gitignore;
}
```
2. Run `tex_tpl <document-name>`
