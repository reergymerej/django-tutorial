# Tue Jul  6 21:06:25 EDT 2021

Django uses MVC and templating.

pip3 - pip is the package installer for Python
venv - used for virtual environments (isolate different python/pip installations)

    python manage.py runserver
      File "manage.py", line 17
        ) from exc
             ^
    SyntaxError: invalid syntax

This is because it is not running in the environment (venv).  How do we start that?

## To load venv, you source it from the shared env.

    source ~/envs/mysite/bin/activate.fish

If Coc isn't seeing the imports, source the terminal and then open Vim.
