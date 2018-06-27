# bunyan-sift
Extension to the https://github.com/trentm/node-bunyan log viewer/formatter to exclude properties from displayed records

Invoke `bunyan-sift` in place of `bunyan`

Adds command flags:
```
  -s, --sift PATH
                Sift each log message removing any
                elements that match PATH. E.g.:
                    -s req.headers
                will hide the request headers
                for all messages displayed.
```
