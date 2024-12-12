In case this error happens:
```
urllib3 v2.0 only supports OpenSSL 1.1.1+, currently the 'ssl' module is compiled with LibreSSL 2.8.3
```

```bash
pip uninstall urllib3
pip install 'urllib3<2.0'
```