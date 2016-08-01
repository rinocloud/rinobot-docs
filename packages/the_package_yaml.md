# The package.yaml file

This is the file where you define the behavior of a rinobot-package. Its 
really easy, and has just two required fields.

Here is a simple example of a minimal python package.

Assume we have some file `index.py` which performs our package operation. The `package.yaml` will looks like so:

```
main: index.py
engine: python
```

## Fields

- `main`: The name of the initial entry point to the package, so that rinobot knows which file to run.
- `engine`: Wether to run the package using python, matlab, or Rscript. Currently only python is supported. 