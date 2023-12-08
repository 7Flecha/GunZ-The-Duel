<b> appserv-win32-2.5.7.exe (probably outdated but still works) </b><br>
<b>[Remove ; / Replace this in 'PHP.ini' file]</b><br>
extension=php_ming.dll<br>
extension=php_mssql.dll<br>
;extension=php_msql.dll<br>
extension=php_mysql.dll<br>
extension=php_mysqli.dll<br>
output_buffering = Off to output_buffering = On
session.auto_start = 0 to session.auto_start = 1
mssql.secure_connection = Off to mssql.secure_connection = On
