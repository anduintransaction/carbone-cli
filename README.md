# Carbone CLI - Command line interface for Carbone.io

## Install

```bash
npm install -g carbon-cli
```

## Usage
```bash
carbone-cli [input-file] [data-file] [output-file] [options-file]
```
where
- [input-file] is a template
- [data-file] is a json file
- [output-file] is the result document
- [options-file] is a json file containing the carbone options

the options file can be used, for example, to convert the file into pdf after processing

e.g, 

```bash
carbone-cli template.docx data.json output.docx options.json
```

will generate `output.docx` from `template.docx` and `data.json`