# http\Client\Request http\Client\Request::setOptions([array $options = NULL])

Set client options.
See http\Client::setOptions() and http\Client\Curl.

Request specific options override general options which were set in the client.

> **Note:** Only options specified prior enqueueing a request are applied to the request.

## Params:

* Optional array $options = NULL  
  The options to set.

## Returns:

* http\Client\Request, self.

## Throws:

* http\Client\InvalidArgumentException
