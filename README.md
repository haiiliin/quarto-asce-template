# ASCE (asce)

This is a Quarto template that assists you in creating a manuscript for ASCE journals.

## Creating a New Article

You can use this as a template to create an article for an ASCE journal. To do this, use the following command:

```bash
quarto use template haiiliin/quarto-asce-template
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto add haiiliin/quarto-asce-template
```

## Usage

To use the format, you can use the format names `asce-pdf`. For example:

```bash
quarto render article.qmd --to asce-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  asce-pdf:
    keep-tex: true
```

You can view a preview of the rendered template at <https://haiiliin.github.io/quarto-asce-template/>.

## Format Options
