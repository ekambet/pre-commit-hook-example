# pre-commit-hook-example

```cmd
pip install pre-commit
```


```yaml
 - id: hello
  name: my first hook
  description: (removed) use pre-commit/mirrors-autopep8 instead.
  entry: ./hello.py
  language: python
  always_run: true
  pass_filenames: false
```

# new file -- 
git update-index --chmod=+x hello.py
add shebang line
#!/usr/bin/python
