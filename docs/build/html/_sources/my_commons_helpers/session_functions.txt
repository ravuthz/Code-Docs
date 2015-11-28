Session Functions
=================

set_session($name, $value)
--------------------------
    * $name : Name of the session to set.
    * $value : Value of the session to set.

get_session($name)
------------------
    * $name : Name of the session to fetch.
    * return the session object.

delete_session($name = null)
----------------------------
    * $name : Name of the session to delete, if name is empty or null this will destroy all
   the session object.

list_session()
--------------
    * return the session array.

flash($name, $value = null)
---------------------------
    * $name : Name of the session to set or get when $value null or not.
    * $value : of the session to set

redirect_flash($to, $message = '')
----------------------------------
    * $to : Path to redirect
    * $message : Session object send before redirect by flash().
