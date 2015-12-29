<h1> htpasswd parser class </h1>
you can parse .htpasswd files and control users .
<h3>Methods</h3>
<code>contructor($address) </code> address of .htpasswd <br>
<code>parse()</code> parse .htpasswd file <br>
<code>reload()</code> fetch content and parse again <br>
<code>haveUser()</code> check .htaccess have user or not <br>
<code>userExists($username)</code> check <code>$username</code> exists or not <br>
<code>addUser($username , $password ) </code> push new user in <code>$users[] </code> <br>
<code>updateUser($username , $password )</code> update user ( user password ) <br>
<code>deleteUser($username) </code> unset <code>$username</code> from <code>$users[]</code> <br>
<code>generatePw($pw)</code> generate crypted password <br>
<code>save()</code> save changes. needed after <code>addUser , updateUser , deleteUser </code> <br>
<pre> contact me @ telegram ( <a href="http://telegram.me/pp2007ws">@pp2007ws</a>)</pre>
