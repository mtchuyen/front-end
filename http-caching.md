
## Cache
### What Can be Cached?
See [2]

### Caching Headers
See [2]

***Thứ tự của header : (xem trong [1])***

`[[Last-Modified]]` --> `[[Etag (Entity Tags)]]` --> `[[Expires]]` --> `[[Cache-Control]]`

- chiều từ trái sang phải là chiều tịnh tiến (hiện đại hơn, khắc phục được các nhược điểm hơn)
- hầu hết các web hiện đại đều sử dụng thay thế `[Cache-Control]` cho `[Expires]` (tất nhiên dùng cả 2 đều không ảnh hưởng gì).


### Cache-Control
Các thành phần: (xem trong [1])

Các tùy chọn của Cache-Control header bao gồm:
- `max-age`=[seconds]: gán thời gian tối đa trước khi file hết hạn. Giá trị này cũng tương tự như Expires và được tính bằng giây.
- `s-maxage`=[seconds] : cũng tương tự như max-age nhưng chỉ áp dụng cho những cache được chia sẻ (ví dụ như proxy).
- `public`: Đánh dấu rằng gói response này có thể cached. Thông thường người ta set thuộc tính public cho những thông tin không bảo mật và báo cho trình duyệt biết rằng có thể cache. Thông thường, nếu yêu cầu xác thực HTTP thì response sẽ tự động private.
- `private`: Chỉ cho phép cache thông tin của một user nào đó vào trình duyệt của họ. Và những shared cache (như proxy) thì không được phép.

## Developing a Caching Strategy
See [2]

## Fingerprints
See: [2], [3]
- [2]: Fingerprint cache items
- [3]: Fingerprint content

## Ref:
[1: Tìm hiểu về http caching](https://viblo.asia/p/tim-hieu-ve-http-caching-djeZ1BRJlWz)
[2: Web Caching Basics: Terminology, HTTP Headers, and Caching Strategies](https://www.digitalocean.com/community/tutorials/web-caching-basics-terminology-http-headers-and-caching-strategies3]
[3: Guide for Caching and HTTP Cache Headers for Static Content](https://imagekit.io/blog/ultimate-guide-to-http-caching-for-static-assets/)
[4: Hypertext Transfer Protocol (HTTP/1.1): Caching (IETF docs)](https://httpwg.org/specs/rfc7234.html#header.expires)
[5: Caching Header Best Practices](https://simonhearne.com/2022/caching-header-best-practices/)
[6: HTTP Cache Headers - A Complete Guide](https://www.keycdn.com/blog/http-cache-headers)
[7: An in-depth introduction to HTTP caching: Cache-Control & Vary](https://www.freecodecamp.org/news/an-in-depth-introduction-to-http-caching-cache-control-vary/)
