### 编码

> Excelsior Stan Lee



UCS

UTF（UCS Transfer Format）

[UTF-8 a transformation format of ISO 10646](https://www.ietf.org/rfc/rfc3629.txt)

```c
 0000 0000-0000 007F | 0xxxxxxx
 0000 0080-0000 07FF | 110xxxxx 10xxxxxx
 0000 0800-0000 FFFF | 1110xxxx 10xxxxxx 10xxxxxx
 0001 0000-0010 FFFF | 11110xxx 10xxxxxx 10xxxxxx 10xxxxxx
```

| -   | -    | -               | -                          |                            |        |
| --- | ---- | --------------- | -------------------------- | -------------------------- | ------ |
| 严   | 4E25 | 100111000100101 | 1110xxxx 10xxxxxx 10xxxxxx | 11100100 10111000 10100101 | E4B8A5 |





FEFF

ZERO WIDTH NO-BREAK SPACE





xxd

od

hexdump





#### escape

The hexadecimal form for characters, whose code unit value is 0xFF or less, is a two-digit escape sequence: %xx. For characters with a greater code unit, the four-digit format %**u**xxxx is used.





#### chcp

Changes the active console code page.

936 | Chinese 





#### locale

> locale -a
> 
> 

参考

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/escape

https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/chcp

https://wiki.archlinux.org/index.php/Locale_(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87)



https://www.ietf.org/rfc/rfc1738.txt

Thus, only alphanumerics, the special characters "$-_.+!*'(),", and
reserved characters used for their reserved purposes may be used unencoded within a URL.


