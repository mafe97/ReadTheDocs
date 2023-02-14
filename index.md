# Documentation Project Software

Documentation of proof, created course inside of DJango, use the library MKDOCS for publish in **ReadTheDocs**

## Requeriments

- Clone repository [Google](www.google.com)
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

## Login

```python
    class Login(FormView):
        Template_name = 'login.html'

        @method_decorator
            if {request.user.login.is_authenticated}
            else:
                return super
```

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
