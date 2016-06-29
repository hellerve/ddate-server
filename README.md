# ddate-server

A simple server in zepto that returns the current ddate.

# Requirements

You will need the html package (you can obtain it via `zeps i zepto-lang/html`).

If you don't want to install those manually, you can install the package directly
from Github via `zeps i hellerve/ddate-server`).

# Usage

```
zepto ddate-serve.zp
```

You can now access the web page on `0.0.0.0:5000`.
There is also a JSON "API" under `/json`. It will
tell you the current ddate in the format:

```javascript
{"ddate": "current-ddate"}
```

<hr/>

Have fun!
