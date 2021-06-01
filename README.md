# SQL_Note
### comparison date in mysql
if we want to fetch data from mysql within date time as where clause comparison :\
<code>select * from coba where DATE(tanggal) = DATE(NOW());</code>\
column tanggal is datetime type of data, so have to change to date because of NOW() is Date type not datetime as tanggal column
