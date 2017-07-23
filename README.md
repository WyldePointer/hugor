# hugor
A curl_* wrapper for PHP.

Examples:
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
