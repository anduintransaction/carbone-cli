# Carbone CLI - Command line interface for Carbone.io

## Install

```bash
npm install -g carbon-cli
```

## Usage
```bash
carbone-cli [input-file] [data-file] [output-file]
```
where
- [input-file] is a docx template
- [data-file] is a json file
- [output-file] is the result docx document

e.g, 

```bash
carbone-cli template.docx data.json output.docx
```

will generate `output.docx` from `template.docx` and `data.json`



