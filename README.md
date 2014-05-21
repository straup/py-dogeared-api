# py-dogeared-api

Python bindings for the dogeared-www API

## Example

	from doegared.api.client import OAuth2

	api = OAuth2(ACCESS_TOKEN, hostname=HOSTNAME, endpoint=ENDPOINT)

	method = 'api.test.echo'

	args = {
		'hello': 'world'
	}

	rsp = api.execute_method(method, args)
	print rsp

## See also

* https://github.com/straup/dogeared-www

