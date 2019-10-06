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
- [options] is a json file that contains optional parameters [read more](https://github.com/Ideolys/carbone/#user-content-api-reference)

e.g,

```bash
carbone-cli template.docx data.json output.docx
```

will generate `output.docx` from `template.docx` and `data.json`

or with options file:

```bash
carbone-cli template.docx data.json output.pdf options.json
```

will generate `output.docx` from `template.docx` and `data.json` depending on `options.json`.


