# hugor
A curl_* wrapper for PHP.

## Examples:
Simple form of a GET request:
```
$response = hugor_make_request(array(
  "url" => "http://dwrap.local/api/get_ip_by_name/www.google.com/json/limit/3",
));

var_dump($response);
```

Result:
```
string(52) "["74.125.232.243","74.125.232.240","74.125.232.244"]"
```

Or in a more complicated situation:

```
$backend_response = make_curl_http_request(array(
  "url" => "path/to/your/URI/",
  "content_type" => "application/json",
  "return_header" => true,
  "username" => "trustworthy",
  "password" => "%!GKTIQW*(RR",
  "method" => "POST",
  "body" => $data,
  "self_signed_certificate" => true
));
```

Note on the project name: It's not the Hugor as in 'Hugor of the Hill' and the inspiration was from 'Hugo Reyes' and his curl()-y hairs.
