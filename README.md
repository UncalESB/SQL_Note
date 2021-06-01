# SQL_Note
### comparison date in mysql
if we want to fetch data from mysql within date time as where clause comparison :\
<code>select * from coba where DATE(tanggal) = DATE(NOW());</code>\
column tanggal is datetime type of data, so have to change to date if only date to compare not including time\
<code>select * from coba where tanggal <= NOW();</code>\
to compare datetime \
also \
  <code>select * from coba where tanggal <= CURRENT_TIMESTAMP;</code>\
### convert string to date in mysql\
    <code>SELECT STR_TO_DATE('21,5,2013','%d,%m,%Y');</code>\
    #### result :\
    ![alt text](https://github.com/UncalESB/NVR_Hikvision/blob/main/reqmap.JPG)
