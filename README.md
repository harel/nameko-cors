# nameko-cors
Cors Support for Nameko HTTP


Written following this github issue (and borrowing heavily from that post): https://github.com/nameko/nameko/issues/309

## Example
```
@cors_http('GET', '/some/path/')
def some_request(self, request):
    """
    Do a get request with CORS 
    """
    return self.response(data={'some': 'value'})
```
