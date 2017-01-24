# GoWorkspace

A Boilr template for creating a go-lang workspace: https://golang.org/doc/code.html


Creates the directory structure:

```
  |-{{ProjectName}
    |- bin/
    |- pkg/
    |- src/
```

Installation
-------------
```bash

  $ boilr template download jinmatt/boilr-go-workspace GoWorkspace
```
Updates
-------

If you need to fetch the newer version, try this:

```bash

  $ boilr template download jinmatt/boilr-go-workspace GoWorkspace -f
```

Usage
-----

```bash
  # boilr template use GoWorkspace <project-name>
  $ boilr template use GoWorkspace FooBarApp
```

Thanks
------

- The team behind boilr (https://github.com/tmrts/boilr)

Contributing
------------

Contributions are always welcome! Nothing is to small, and the best place to start is to open an issue.

-- jinmatt
