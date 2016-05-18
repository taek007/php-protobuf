# php-protobuf
modified the php-protobuf,now was support php7

https://github.com/allegro/php-protobuf
the php-protobuf  only support php5,so i modified some code,it can support php7

In php7,the hashTable had many changes
example zend_hash_quick_find had removed , the options was zend_hash_find
zend_hash_get_current_key_ex decrease to 4 params
