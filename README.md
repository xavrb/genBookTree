# genBookTree
A folder tree generator for a generic book to be compiled on pandoc.

## What?
This script will generate a tree folder of a generic book, to be compiled with pandoc.

For chapters, it will create  01-, 02-, ... XX folders with a 01-capterxx.markdown file

Will create:
```
├── Back\ matter
│   ├── Afterword
│   │   └── afterword.markdown
│   ├── Appendix
│   │   └── appendix.markdown
│   ├── Colophon
│   │   └── colophon.markdown
│   ├── Epilogue
│   │   └── epilogue.markdown
│   ├── Extro
│   │   └── Extro.markdown
│   ├── Glossary
│   │   └── glossary.markdown
│   └── Postscript
│       └── postscript.markdown
├── chapters
│   ├── 01-
│   │   └── 01-chapter01.markdown
│   ├── 010-
│   │   └── 01-chapter010.markdown
│   ├── 011-
│   │   └── 01-chapter011.markdown
│   ├── 012-
│   │   └── 01-chapter012.markdown
│   ├── 013-
│   │   └── 01-chapter013.markdown
│   ├── 014-
│   │   └── 01-chapter014.markdown
│   ├── 015-
│   │   └── 01-chapter015.markdown
│   ├── 016-
│   │   └── 01-chapter016.markdown
│   ├── 017-
│   │   └── 01-chapter017.markdown
│   ├── 018-
│   │   └── 01-chapter018.markdown
│   ├── 019-
│   │   └── 01-chapter019.markdown
│   ├── 02-
│   │   └── 01-chapter02.markdown
│   ├── 020-
│   │   └── 01-chapter020.markdown
│   ├── 03-
│   │   └── 01-chapter03.markdown
│   ├── 04-
│   │   └── 01-chapter04.markdown
│   ├── 05-
│   │   └── 01-chapter05.markdown
│   ├── 06-
│   │   └── 01-chapter06.markdown
│   ├── 07-
│   │   └── 01-chapter07.markdown
│   ├── 08-
│   │   └── 01-chapter08.markdown
│   └── 09-
│       └── 01-chapter09.markdown
├── Front\ matter
│   ├── Acknowledgements
│   │   └── acknowledgements.markdown
│   ├── dedication
│   │   └── dedication.markdown
│   ├── Epigraph
│   │   └── epigraph.markdown
│   ├── Introduction
│   │   └── introduction.markdown
│   └── Prologue
│       └── prologue.markdown
├── metadata.txt

```

# How?
Just run the script as follows:
```bash
sh create.sh
```
