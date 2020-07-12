# Porter Web Interface

This repository contains a web interface for [porter](https://github.com/ctrezevant/porter), a smart garage door controller.

Configuration options (specified in the HTML document):

```
var CONFIG = {
		api_uri: "",
		api_key: "",
		door_name: ""
}
```

**Note that any API key you embed in this document is exposed to anyone on your local network who accesses the web page.**

The Porter API service can optionally serve a web page at its root URL. You can use this to serve the contents of this web UI
to visitors by adding the following line to your Porter configuration file (in the `"http":{...}` section):

```
	"index_file": "/path/to/your/index.html"
```
