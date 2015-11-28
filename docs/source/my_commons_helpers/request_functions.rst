Request Functions
=================

request($input = null, $method = 'post')
----------------------------------------
    * $input : Name of the request from client, can be Array or String to fetch.
    * $method : The method name of the request, default is POST.
    * return fetched object

    ::

     Example: $array = request('firstname', 'lastname');

request_is_post()
-----------------
    * return true if the request method is POST otherwise false.

request_is_get()
----------------
    * return true if the request method is GET otherwise false.
