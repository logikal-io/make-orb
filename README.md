Make Orb
========
GitHub Action for creating a [pyorbs](https://pyorbs.readthedocs.io/) orb.

Usage
-----
```yaml
steps:
  - uses: logikal-io/make-orb@v1
```

Inputs
------
`name`: Optional, the name of the orb. Defaults to `magic`.

`requirements`: Optional, the path to the requirements file. Defaults to `requirements.txt`.

`working-directory`: Optional, the working directory to use. Defaults to the current directory.

License
-------
This GitHub Action is licensed under the MIT open source license.
