### Tạo domain trên localhost

[Mapping Hostnames with Ports in /etc/hosts](https://www.baeldung.com/linux/mapping-hostnames-ports)
- `/etc/hosts` is a file used by the operating system to translate hostnames to IP-addresses.
- Nhưng `/etc/hosts` chỉ cho phép mapping domain với IP, chứ không có ***Port***. (The `hosts` file only deals with `hostnames`, not `ports`.)
- 

***Giải pháp***:
- Có 2 cách: Apache và Nginx. Apache cấu hình khó (lâu) hơn Nginx.

#### Cấu hình trên Nginx.
- ***S1: Tạo mapping domain với IP trên /etc/hosts***

```
127.0.0.1       localhost
127.0.0.1       short.local
```
Trong đó:
- `short.local` là domain muốn tạo trên localhost.

- ***S2: Tạo cấu hình trên Nginx***:

Có thể tạo cấu hình trong 2 thư mục `/etc/nginx/conf.d/` và `/etc/nginx/sites-enabled/`, nếu trong `conf.d/` thì phải tạo files có đuôi là `.conf`.

2 thư mục này được nginx call dựa trên config `http` của file `/etc/nginx/nginx.conf`

```
http {
        ...
        include /etc/nginx/conf.d/*.conf;
        include /etc/nginx/sites-enabled/*;
        ...
}
```
- ***S3: Reload nginx's Configuration*** (ưu tiên hơn) hoặc ***Restart Nginx***

> nginx -s reload
> systemctl restart nginx


#### Ref:
- https://www.danclarke.com/nginx-to-avoid-localhost-port
- https://gist.github.com/soheilhy/8b94347ff8336d971ad0
- 
