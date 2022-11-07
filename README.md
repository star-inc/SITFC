# SITFC

Star Inc. - Transport Format with Compressed 

## Expression

```php
gzencode("$id\x1e$hmac_sha3_256\x1e$unix_timestamp\x1e$encrypt_algo\x1e$data");
```
