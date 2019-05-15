hexdump -c mydb.pb
 cat mydb.pb |protoc --decode_raw
