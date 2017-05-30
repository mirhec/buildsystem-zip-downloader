
## Installation
In order to install the latest release of buildsystem-zip-downloader, run the following command:

```
pip install buildsystem-zip-downloader
```

Use this plugin to download and extract zip files to a given location:

```python
depsbuilder = ZipDependencyResolver()
depsbuilder.conf(deps=[{
    'url': 'http://youru.rl/your.zip',
    'dirname': 'yourextractfolder'
}], log_enabled=True)
depsbuilder.build()
```