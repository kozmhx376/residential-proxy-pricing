# mua proxy dân cư: bảng giá theo IP và theo GB, chọn gói nào cho nuôi tài khoản, MMO và thu thập dữ liệu

Gõ "mua proxy dân cư" vào Google thường là lúc bạn đã thử vài cách rẻ hơn và thấy không ổn: proxy công cộng thì chết liên tục, proxy datacenter thì bị chặn ngay từ request đầu tiên, còn tài khoản thì vẫn bị checkpoint đều đặn.

Nhưng khi mở trang của nhà cung cấp ra, câu hỏi thật sự lại nằm ở chỗ khác: giá bao nhiêu, tính theo cái gì, và gói nhỏ nhất có đủ dùng cho công việc của mình hay không. Đây là chỗ dễ mất tiền nhất, vì các trang bán proxy thường chỉ quảng cáo con số khởi điểm — "từ $0,015/IP" hoặc "từ $1/GB" — mà hai con số đó không thể so sánh trực tiếp với nhau.

Bài này đi theo thứ tự bạn thực sự cần: hiểu cách tính tiền, biết mô hình nào hợp với công việc gì, rồi mới xem bảng giá cụ thể. 9Proxy được dùng làm ví dụ xuyên suốt vì bảng giá của nó công khai theo từng bậc, không phải dạng "liên hệ để báo giá" — và vì đây cũng là dịch vụ có nhiều điểm dễ kiểm chứng.

## Hai kiểu tính tiền quyết định chi phí thật

Hầu hết nhà cung cấp proxy dân cư dùng một trong hai mô hình, hoặc cả hai:

**Theo IP.** Bạn trả tiền cho số lượng địa chỉ IP, và băng thông đi qua mỗi IP là không giới hạn. Đây là kiểu tính phù hợp khi bạn cần giữ nguyên một IP trong suốt phiên làm việc — đăng nhập, duyệt web, chạy phần mềm automation — và không muốn bị cắt giữa chừng vì hết dung lượng.

**Theo GB.** Bạn trả tiền cho lưu lượng đã dùng, IP được xoay liên tục. Hợp với kiểu công việc mà mỗi request chỉ lấy một lượng dữ liệu nhỏ, nhưng số request thì rất lớn: kiểm tra thứ hạng từ khóa, quét giá, xác minh quảng cáo theo khu vực.

Điểm quan trọng: cùng một công việc có thể rẻ hơn đáng kể khi chọn đúng mô hình. Nếu bạn chạy 30 trình duyệt anti-detect với phiên đăng nhập dài, mô hình theo GB sẽ khiến bạn trả tiền cho toàn bộ ảnh, video và script tải về trong phiên — khoản đó tăng rất nhanh. Ngược lại, nếu bạn chỉ cần gửi hàng nghìn request nhỏ rồi bỏ IP đi, trả theo IP nghĩa là bạn trả tiền cho những địa chỉ gần như không dùng hết.

Một số nhà cung cấp còn bán gói kết hợp (bundle) để bạn có cả hai dạng trong cùng một số dư.

## Proxy dân cư khác proxy datacenter ở điểm nào

IP dân cư thuộc về kết nối internet tại nhà của người dùng thật, do nhà mạng như Comcast, AT&T, Viettel cấp. Với hệ thống phát hiện của website, request từ IP này trông giống một người bình thường đang ngồi ở thành phố bạn chọn. IP datacenter thì thuộc dải của các công ty thuê máy chủ — nhanh hơn, rẻ hơn nhiều, nhưng nằm sẵn trong danh sách nghi ngờ của gần như mọi hệ thống chống bot.

Sự khác biệt này giải thích luôn phần lớn chênh lệch giá. Một gói datacenter có thể rẻ bằng một phần mười gói dân cư cùng dung lượng. Bạn không trả tiền cho tốc độ, mà trả cho việc IP đó không bị gắn cờ.

## 9Proxy: hồ sơ nhanh và bảng giá hiện hành

9Proxy là nhà cung cấp proxy dân cư thành lập năm 2023, hiện quảng cáo pool hơn 20 triệu IP tại hơn 90 quốc gia, hỗ trợ HTTP/HTTPS và SOCKS5, có nhắm mục tiêu theo quốc gia, bang, thành phố và cả ISP. Một số điểm đáng chú ý về mặt vận hành, dựa trên các bài đánh giá độc lập: IP theo gói IP-based có thời gian sống từ vài giờ đến tối đa 24 giờ, và những IP đã dùng trong 24 giờ gần nhất được nằm trong danh sách "Today List" để tái sử dụng miễn phí nếu vẫn còn sống.

Về giá, có một chi tiết dễ gây nhầm lẫn: 9Proxy đã điều chỉnh giá lần đầu kể từ khi thành lập, áp dụng từ ngày 1/6/2026 cho các gói theo IP và gói bundle, còn gói theo GB giữ nguyên. Vì vậy bạn sẽ gặp những bài review cũ vẫn ghi 100 IP giá $20 — mức hiện hành là $24. Bảng dưới đây tổng hợp toàn bộ các bậc đang được niêm yết, theo mức giá sau điều chỉnh.

**Gói theo IP (băng thông không giới hạn trên mỗi IP, IP chưa kích hoạt không hết hạn):**

| Gói | Đơn giá | Tổng | Mua |
| --- | --- | --- | --- |
| 100 IP | $0,24/IP | $24 | [Mua gói 100 IP](https://bit.ly/9-Proxy) |
| 500 IP | $0,144/IP | $72 | [Mua gói 500 IP](https://bit.ly/9-Proxy) |
| 1.000 IP + tặng 500 IP | $0,084/IP | $126 | [Mua gói 1.000 IP](https://bit.ly/9-Proxy) |
| 2.500 IP | $0,084/IP | $210 | [Mua gói 2.500 IP](https://bit.ly/9-Proxy) |
| 5.000 IP | $0,072/IP | $360 | [Mua gói 5.000 IP](https://bit.ly/9-Proxy) |
| 15.000 IP | $0,048/IP | $720 | [Mua gói 15.000 IP](https://bit.ly/9-Proxy) |
| 25.000 IP | $0,035/IP | $863 | [Mua gói 25.000 IP](https://bit.ly/9-Proxy) |
| 50.000 IP | $0,029/IP | $1.438 | [Mua gói 50.000 IP](https://bit.ly/9-Proxy) |
| 100.000 IP (Business) | $0,023/IP | $2.300 | [Mua gói Business 100K IP](https://bit.ly/9-Proxy) |
| 200.000 IP (Business) | $0,021/IP | $4.140 | [Mua gói Business 200K IP](https://bit.ly/9-Proxy) |
| 500.000 IP (Business) | $0,018/IP | $8.625 | [Mua gói Business 500K IP](https://bit.ly/9-Proxy) |

**Gói theo GB (IP xoay vòng, không giới hạn số request):**

| Gói | Đơn giá | Tổng | Hiệu lực | Mua |
| --- | --- | --- | --- | --- |
| 5 GB | $3,00/GB | $15 | 180 ngày | [Mua gói 5 GB](https://bit.ly/9-Proxy) |
| 50 GB + tặng 5 GB | $2,10/GB | $105 | 180 ngày | [Mua gói 50 GB](https://bit.ly/9-Proxy) |
| 100 GB | $1,50/GB | $150 | 180 ngày | [Mua gói 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | $1,00/GB | $200 | 180 ngày | [Mua gói 200 GB](https://bit.ly/9-Proxy) |
| 1.000 GB | $0,80/GB | $800 | 180 ngày | [Mua gói 1.000 GB](https://bit.ly/9-Proxy) |
| 2.000 GB | $0,75/GB | $1.500 | 180 ngày | [Mua gói 2.000 GB](https://bit.ly/9-Proxy) |
| 3.000 GB (Enterprise) | $0,72/GB | $2.160 | Không hết hạn | [Mua gói Enterprise 3.000 GB](https://bit.ly/9-Proxy) |
| 6.000 GB (Enterprise) | $0,70/GB | $4.200 | Không hết hạn | [Mua gói Enterprise 6.000 GB](https://bit.ly/9-Proxy) |
| 10.000 GB (Enterprise) | $0,68/GB | $6.800 | Không hết hạn | [Mua gói Enterprise 10.000 GB](https://bit.ly/9-Proxy) |

**Gói bundle (có cả IP và lưu lượng):**

| Gói | Nội dung | Giá | Mua |
| --- | --- | --- | --- |
| Starter | 100 IP + 5 GB | $30 | [Mua bundle Starter](https://bit.ly/9-Proxy) |
| Popular | 1.500 IP + 50 GB | $180 | [Mua bundle Popular](https://bit.ly/9-Proxy) |
| Pro | 5.000 IP + 500 GB | $720 | [Mua bundle Pro](https://bit.ly/9-Proxy) |

Thanh toán bằng thẻ tín dụng, thẻ ngân hàng, ví điện tử (Alipay, Apple Pay, Google Pay) và tiền mã hóa gồm USDT, BTC, ETH, LTC, DOGE. Giá niêm yết bằng USD và có thể thay đổi, nên bước cuối cùng trước khi trả tiền vẫn nên là đọc lại con số trên trang thanh toán.

## Gói nào dành cho ai

**Nuôi tài khoản, chạy anti-detect, MMO nhiều acc.** Đây là nhóm nên đi theo hướng tính theo IP. Bạn cần IP ổn định trong suốt phiên, số lượng cụ thể, và băng thông không phải thứ bạn muốn đếm. Khởi điểm hợp lý là gói 100 IP giá $24 — đủ để thử với 20–30 profile trước khi quyết định mua nhiều hơn. Nhóm này cũng nên tận dụng Today List: nếu một IP vẫn còn sống trong 24 giờ, bạn dùng lại mà không mất thêm IP nào trong số dư.

**Thu thập dữ liệu, kiểm tra thứ hạng, xác minh quảng cáo.** Đây là địa hạng của gói theo GB. IP xoay liên tục, không cần quan tâm địa chỉ nào đang chạy, và mỗi request thường chỉ tốn vài chục KB. Gói 5 GB giá $15 là mức thử nghiệm rẻ, nhưng đơn giá $3/GB ở bậc này cao nhất trong bảng — nếu công việc chạy đều, bậc 100 GB ($1,50/GB) hoặc 200 GB ($1,00/GB) hạ chi phí trên mỗi GB xuống một nửa. Một điểm đáng lưu ý: lưu lượng có hiệu lực 180 ngày, nên dự án chạy theo đợt không bị ép phải tiêu hết trong một tháng.

**Nhóm cần khối lượng lớn hoặc bán lại.** Các gói Business IP và Enterprise GB mới là chỗ giá thực sự giảm — từ $0,029/IP xuống $0,018/IP, và lưu lượng Enterprise không hết hạn. Nếu bạn bán lại cho khách, phần FAQ của 9Proxy có nhắc đến gói dành cho reseller với giá bán buôn, và tính năng share code / sub-account để chia số dư cho nhiều người dùng.

**Nhóm không chắc mình cần gì.** Bundle là cách né việc phải chọn. Starter $30 cho 100 IP kèm 5 GB đủ để chạy thử cả hai kiểu trong vài tuần rồi tự thấy bên nào tốn hơn. Nhưng nếu bạn đã biết rõ luồng công việc của mình, mua riêng hai gói thường rẻ hơn mua bundle cùng cấu hình — Popular $180 cho 1.500 IP + 50 GB, trong khi mua lẻ 1.500 IP và 50 GB ở bậc tương ứng cộng lại đã xấp xỉ con số đó.

## Mua và bắt đầu trong khoảng 10 phút

1. Đăng ký tài khoản bằng email (nên dùng email riêng cho công việc proxy, và bật xác thực hai lớp nếu có).
2. Chọn gói: theo IP, theo GB, hay bundle. Bạn không cần chọn trước cả năm — số dư dạng này không phải subscription theo tháng, mua rồi dùng dần.
3. Lấy thông tin kết nối. Với gói theo IP, bạn dùng ứng dụng desktop (Windows/Mac) để tạo port, chọn quốc gia và lấy danh sách IP kèm user/pass. Với gói theo GB và các trường hợp muốn thao tác nhanh trên trình duyệt, Proxy2Web cho bạn endpoint ngay trong web mà không phải cài gì.
4. Gắn vào công cụ. SOCKS5 dùng được trực tiếp với các trình duyệt anti-detect như AdsPower hay Dolphin Anty; HTTP(S) thì dán vào Scrapy, requests, Playwright hoặc các tool SEO. Trường hợp cần tự động hóa hoàn toàn thì dùng API.
5. Test trước khi chạy thật. Kiểm tra bằng curl hoặc đặt proxy thủ công trong trình duyệt trước, rồi mới đưa vào phần mềm — nếu proxy không lên ở đó, vấn đề không nằm ở anti-detect browser.
6. Kiểm tra chất lượng IP trên chính mục tiêu của bạn. Một IP có thể mở được Google nhưng lại bị chặn ở sàn thương mại điện tử bạn cần. Một chính sách đáng chú ý: nếu proxy lỗi trong 60 giây đầu sau khi kích hoạt, 9Proxy hoàn lại số dư tự động — điều này giúp việc thử từng IP không trở thành tiền mất vô ích.

## Vài điều nên biết trước khi nạp tiền

Năm 2026 là một năm khó chịu với ngành proxy, và 9Proxy không nằm ngoài câu chuyện đó. Tối 28/6/2026, website và ứng dụng desktop của dịch vụ này ngừng hoạt động; đến 29/6 họ đăng thông báo "service disruption" trên Facebook và tài khoản bán hàng trên BlackHatWorld, không nêu nguyên nhân cũng không có thời gian khôi phục. Nhiều nguồn lúc đó suy đoán bị cơ quan chức năng đánh sập, nhưng các bài phân tích về bản ghi tên miền cho thấy dấu hiệu bình thường — khoá registrar thông thường, nameserver Cloudflare không đổi, tên miền trả phí tới năm 2027 — tức là một sự cố chứ không phải một cuộc thu giữ. Dịch vụ quay lại khoảng giữa tháng 7/2026.

Vài tháng sau, một nhà bán lại viết rằng gói GB đã hoạt động trở lại còn gói theo IP vẫn trong trạng thái bảo trì, nhưng đây là thông tin từ một phía và không được xác nhận chính thức; trang theo dõi trạng thái saashub ghi nhận 9proxy.com hoạt động 100% trong 30 ngày gần nhất tính đến giữa tháng 9/2026. Nói thẳng ra: bạn không thể xác minh được tình trạng bên trong của bất kỳ nhà cung cấp proxy nào chỉ bằng việc trang web có mở được hay không.

Nên cách xử lý rất đơn giản và áp dụng được cho mọi nhà cung cấp, không riêng gì 9Proxy: mua gói nhỏ nhất trước, chạy đúng luồng công việc thật của bạn trong vài ngày, rồi mới nâng lên. Đừng nạp tiền cho cả năm vào một nhà cung cấp duy nhất, và nếu công việc phụ thuộc hoàn toàn vào proxy, hãy giữ một tài khoản dự phòng đã nạp sẵn ở nhà cung cấp khác. Chuyện một dịch vụ im lặng vài tuần không phải hiếm trong ngành này.

## Câu hỏi thường gặp khi mua proxy dân cư

**IP mua theo gói sống được bao lâu?** Với gói tính theo IP của 9Proxy, mỗi IP hoạt động từ vài giờ đến tối đa 24 giờ, và IP chưa kích hoạt thì không bị trừ dần theo thời gian. Với gói theo GB, không có khái niệm IP sống bao lâu vì lưu lượng đi qua IP xoay vòng.

**Có giới hạn băng thông không?** Gói theo IP là không giới hạn băng thông trên mỗi IP đã kích hoạt. Gói theo GB thì tính theo tổng lưu lượng của gói bạn mua.

**Bao lâu thì hết số dư GB?** 180 ngày với các gói tiêu chuẩn, và không hết hạn với các gói Enterprise GB. Đây là khác biệt đáng kể so với các dịch vụ bắt buộc dùng hết trong tháng.

**Có dùng được với AdsPower, Dolphin Anty, Scrapy, Playwright không?** Có. Đây đều là các công cụ hỗ trợ SOCKS5 hoặc HTTP proxy, và 9Proxy hỗ trợ cả hai giao thức.

**Có bản dùng thử không?** Theo FAQ của nhà cung cấp, 9Proxy có chương trình dùng thử giới hạn cho người dùng mới, tuỳ tình trạng còn hàng, và bạn cần nói rõ muốn thử dạng theo IP hay theo GB. Nếu cần chắc chắn, gói 5 GB giá $15 là phương án rẻ nhất để tự kiểm tra.

**Mua proxy dân cư có hợp pháp không?** Bản thân việc dùng proxy là hợp pháp ở phần lớn quốc gia. Phần cần cân nhắc là mục đích: thu thập dữ liệu công khai, kiểm tra quảng cáo, nghiên cứu thị trường thì khác hoàn toàn với việc vượt qua kiểm soát truy cập, giả mạo danh tính hoặc vi phạm điều khoản của nền tảng. Đây không phải tư vấn pháp lý, và luật áp dụng thì tuỳ nơi bạn ở.
