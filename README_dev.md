Vorbereitung

```bash
deactivate
python -m venv ~/venv-sphinx
source ~/venv-sphinx/bin/activate
pip install sphinx-rtd-theme sphinx-bootstrap-theme sphinx-book-theme sphinx-panels sphinxcontrib-luadomain myst-parser sphinx-autobuild sphinx-intl rstdoc rst2pdf esbonio docutils doc8 releases rstcheck sphinxcontrib-plantuml sphinxcontrib-drawio sphinxcontrib-confluencebuilder sphinx-markdown-builder
```


Patch for Sphinx error 'Interpreted text role "index" not implemented.doc8(D000)'
https://github.com/PyCQA/doc8/pull/2/commits/b68617bf0b39c8ecc6fff5e5076af4c0b1bfeaee



Update

```bash
source ~/venv-sphinx/bin/activate
python -m pip install --upgrade pip
python -m pip --trusted-host files.pythonhosted.org --trusted-host pypi.org install  --upgrade pip
python -m pip --trusted-host files.pythonhosted.org --trusted-host pypi.org install --upgrade sphinx-rtd-theme sphinx-bootstrap-theme sphinx-book-theme sphinx-panels sphinxcontrib-luadomain myst-parser sphinx-autobuild sphinx-intl rstdoc rst2pdf esbonio docutils doc8 releases rstcheck sphinxcontrib-plantuml sphinxcontrib-drawio sphinxcontrib-confluencebuilder sphinx-markdown-builder

```


# Publishing

* https://pypi.org/project/betty/ - Betty is a static site generator for Gramps and GEDCOM family trees.

	`pip install git+https://github.com/bartfeenstra/betty.git`

* https://www.grampsweb.org/ - Gramps Web is a web app for collaborative genealogy. It is based on and interoperable with Gramps, the leading open source genealogy desktop application. Gramps Web is free & open source software and puts your privacy and your control of your research data first.
* https://www.grampshub.com/

