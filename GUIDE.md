# Console Translator cho Android

Hướng dẫn cho người mới, bản APK thử nghiệm. Điện thoại đọc chữ trong game, dịch và hiện phụ đề trên điện thoại hoặc gửi lên TV. App không tự kết nối máy chơi game thay cho ứng dụng Remote Play.

## 1. Chuẩn bị trước khi bắt đầu

- Điện thoại Android 11 trở lên và kết nối Internet. Bản beta vẫn cần mạng để kiểm tra mã, kể cả khi chọn dịch trên máy.
- File APK và mã mời do người phát hành gửi riêng. Nhận bản mới hoặc liên hệ hỗ trợ tại [Telegram Console Translator](https://t.me/pstranslator).
- Game bật phụ đề ở phần cài đặt trong game. Lần đầu nên thử tiếng Anh sang tiếng Việt.
- Nếu chơi PX5: kết nối và xem được hình game trên điện thoại bằng app PS Remote Play trước. Nếu chơi trên TV, điện thoại vẫn phải có hình game để đọc chữ.

## 2. Cài APK và nhập mã mời

1. Trên điện thoại, mở file APK nhận từ người phát hành và bấm **Cài đặt**. APK là file cài ứng dụng Android.
2. Nếu điện thoại yêu cầu quyền cài ứng dụng từ nguồn này, chỉ cấp cho ứng dụng bạn đang dùng để mở file. Tên màn hình có thể khác giữa các hãng. Nếu xuất hiện cảnh báo an toàn, dừng lại và hỏi người phát hành, không tự tắt bảo vệ của điện thoại.
3. Mở **Console Translator Beta**, bật mạng, nhập **Mã mời** rồi bấm **Kích hoạt trên máy này**.
4. Chọn ngôn ngữ app, ngôn ngữ trong game và ngôn ngữ muốn đọc. Ví dụ: app Tiếng Việt, game Tiếng Anh, dịch sang Tiếng Việt.

Mã mời dùng cho một lần cài app trên một máy và có thời hạn do người phát hành đặt. Thông thường chỉ nhập một lần. Hết hạn, đổi máy, gỡ app hoặc xóa dữ liệu thì liên hệ người cấp mã. Bạn không cần khóa quản trị hay tài khoản Cloudflare.

**Cập nhật:** mở APK mới và chọn cài cập nhật để giữ dữ liệu. Nếu báo xung đột ứng dụng, hỏi người phát hành; đừng vội gỡ bản cũ vì có thể mất thiết lập và cần mã mới.

## 3. Bắt đầu dịch trên điện thoại

1. Mở game hoặc PS Remote Play, vào đoạn có phụ đề và kiểm tra chữ gốc hiện rõ.
2. Quay về Console Translator. Bấm **Cho phép hiện nổi**, bật quyền cho app rồi quay lại. Quyền này giúp bản dịch hiện trên game.
3. Vào **Cài đặt → Bộ dịch**, chọn **Dịch trên máy** để thử đơn giản nhất. Nếu app yêu cầu tải ngôn ngữ, vào trang **Tải ngôn ngữ**, tải các gói còn thiếu rồi quay lại.
4. Bấm **Bắt đầu dịch**. Khi Android hỏi chia sẻ màn hình, ưu tiên **Chia sẻ một ứng dụng** và chọn đúng game hoặc PS Remote Play. Nếu máy chỉ cho chia sẻ toàn màn hình, để phụ đề dịch ở chỗ khác, không che chữ gốc.
5. Trên thanh công cụ nổi, bấm nút **khung quét**, kéo khung trùm chỗ phụ đề gốc, rồi bấm **Xong**. Khung quá rộng sẽ đọc cả menu, điểm số và chữ không cần dịch.
6. Bấm nút **▶** trên thanh nổi để bắt đầu đọc và dịch. Bấm lần nữa để tạm dừng.

Giữ game hoặc Remote Play hiển thị trên điện thoại trong lúc dịch. Console Translator không tự đọc hình từ cổng HDMI của TV.

Bấm **aA** để chỉnh chữ. Bấm bánh răng để đổi bộ dịch, giọng đọc hoặc hồ sơ game. Chạm icon app để thu gọn thanh công cụ; giữ và kéo để di chuyển. Kết thúc buổi chơi bằng **Dừng dịch**, hoặc nút **Dừng** trong thông báo Android.

## 4. Chỉnh cho dễ đọc và dễ nghe

- **Phụ đề:** trong Cài đặt, chỉnh cỡ chữ và bật/tắt **Hiện câu gốc**. Mới dùng nên giữ thiết lập mặc định trước.
- **Đọc to bản dịch:** bật khi muốn nghe, dùng **Nghe thử** để kiểm tra giọng của điện thoại. Nếu thiếu giọng, vào **Tải ngôn ngữ** để mở nơi tải giọng. Giọng đọc phát trên điện thoại.
- **Hồ sơ game:** tạo một hồ sơ cho từng game để nhớ vùng quét và phong cách dịch.
- **Chữ hiện dần:** chỉ bật cho game hiện thoại từng chữ; game hiện cả câu thì để tắt.
- **Dịch AI:** là lựa chọn thêm, cần khóa API riêng. Mã mời beta không phải khóa AI. Chưa có khóa thì dùng **Dịch trên máy**; không cần tự tìm khóa để bắt đầu thử app.

Dịch trên máy có thể dùng các gói đã tải mà không gọi dịch đám mây, nhưng bản beta vẫn kiểm tra quyền qua mạng. Bản thử này chưa phải gói PRO/Premium đã mua qua Google Play.

## 5. Hiện phụ đề trên Android TV / Google TV

1. Nhận bản **PS Translator TV** phù hợp từ người phát hành và cài trên TV Android/Google TV. File cài cho điện thoại không phải file cài cho TV.
2. Mở app trên TV, cấp quyền **Hiển thị trên ứng dụng khác** nếu được hỏi. Điện thoại và TV cùng mạng nhà; TV nối dây mạng cũng được nếu cùng mạng với Wi-Fi điện thoại.
3. Trên điện thoại mở **Cài đặt → Phụ đề trên TV**, chọn TV được tìm thấy hoặc nhập địa chỉ hiện trên TV.
4. Nhập **Mã 8 số trên TV** rồi bấm **Kết nối**. Mã này đổi mỗi phút, nên dùng mã đang hiện. Nếu sai, đọc lại mã mới.
5. Bấm **Gửi lên TV** để thử một câu. Khi thấy phụ đề, chuyển TV sang HDMI của máy chơi game, rồi làm các bước dịch trên điện thoại ở mục 3.

Cỡ chữ, vị trí và nền phụ đề TV chỉnh trong **Phụ đề trên TV**. Tính năng này cần ứng dụng nhận trên TV; TV Samsung Tizen không cài được APK Android. Với LG webOS, làm mục 6 bên dưới.

## 6. Cài lần đầu trên TV LG webOS

Phần LG hiện dành cho bản beta đã kích hoạt. Không cần máy tính: điện thoại sẽ gửi ứng dụng nhận phụ đề sang TV. Khả năng phụ đề nổi trên HDMI tùy mẫu TV và phần mềm TV; hãy test trước khi dùng lâu dài.

**Chuẩn bị TV:** tìm và cài **Developer Mode** trong LG Apps/LG Content Store. Mở app đó, đăng nhập tài khoản LG Developer, bật **Dev Mode Status** và chờ TV khởi động lại. Mở lại Developer Mode, bật **Key Server**.

**Từ điện thoại:** vào **Cài đặt → Phụ đề trên TV → Cài cho TV LG webOS**. Nhập IP TV và **Passphrase 6 ký tự** đang hiện trong Developer Mode, đúng chữ hoa/thường. Điện thoại và TV phải cùng mạng nhà. IP là địa chỉ của TV trong mạng nhà, xem ở phần thông tin kết nối trong Cài đặt mạng của TV, ví dụ 192.168.1.50. Nhập địa chỉ của TV nhà bạn, không chép địa chỉ ví dụ.

Bấm **Cài lên TV**. Nếu hiện xác nhận tin cậy, kiểm tra đúng TV/IP; nếu không chắc TV nào, bấm Hủy và hỏi hỗ trợ. Chờ app báo cài thành công. Cài xong app tự mở trên TV.

Đóng màn hình hướng dẫn LG trên điện thoại, nhập **mã phụ đề 8 số** hiện trên TV vào mục **Phụ đề trên TV**, rồi bấm **Kết nối**. Bấm **Gửi lên TV** để kiểm tra.

**Nhớ gia hạn Developer Mode:** trước khi thời gian còn lại hết, mở Developer Mode trên TV và bấm **EXTEND** khi TV có mạng. LG có thể gỡ các app cài bằng Developer Mode khi chế độ này bị tắt. Xem [hướng dẫn chính thức LG](https://webostv.developer.lge.com/develop/getting-started/developer-mode-app).

## 7. Mỗi lần chơi trên TV LG

1. Bật PX5 và TV. Kết nối Remote Play trên điện thoại, kiểm tra đã thấy hình game.
2. Chuẩn bị IP và Passphrase: nếu chưa có, mở Developer Mode trên TV, bật Key Server và xem Passphrase. Ghi nhớ thông tin để nhập trên điện thoại, không gửi cho người khác.
3. Chuyển TV sang đúng HDMI của PX5 và chờ hình game hiện. Sau đó trên điện thoại vào **Cài cho TV LG webOS**, nhập IP/Passphrase rồi bấm **Mở app đã cài**. Không cần bấm Cài lên TV mỗi lần.
4. Kết nối phụ đề nếu chưa ghép, dùng mã 8 số đang hiện trên TV. Nút mở nằm trong màn hình LG, không phải nút tự xuất hiện sau ghép nối; mỗi thao tác cần nhập lại Passphrase vì app không lưu nó. Nếu mở không được, kiểm tra lại Developer Mode/Key Server rồi thử lại.
5. Bật phụ đề game, chọn đúng vùng quét trên điện thoại và bấm ▶. Chơi bằng tay cầm, giữ điện thoại tiếp tục hiển thị game và chia sẻ màn hình.

Trong lúc chơi, tránh bấm **Home** hoặc mở app khác bằng remote TV vì lớp phụ đề có thể bị đóng. Không phải mọi nút remote đều bị cấm. Nếu phụ đề mất, trở về HDMI rồi mở app LG lại từ điện thoại; không cần cài lại ngay.

## 8. Ba loại mã, đừng nhập nhầm

- **Mã mời beta:** người phát hành gửi riêng, nhập vào màn hình **Kích hoạt bản thử** trên điện thoại.
- **Passphrase 6 ký tự của LG:** xem trong Developer Mode, nhập vào màn hình **Cài cho TV LG** để cài/mở app.
- **Mã phụ đề 8 số:** hiện trong app nhận phụ đề trên TV, nhập vào **Phụ đề trên TV** để kết nối.

Không đăng công khai các mã hoặc Passphrase. Không gửi mật khẩu tài khoản LG cho người hỗ trợ.

## 9. Gặp lỗi thì làm gì?

**App hỏi lại quyền hoặc báo hết hạn:** bật mạng, bấm **Kiểm tra lại**. Nếu vẫn bị từ chối, nhắn người cấp mã. Đừng gỡ app để thử sửa lỗi trước.

**Không có bản dịch:** kiểm tra game đã bật phụ đề, bạn đã bấm ▶, khung quét đúng chỗ chữ gốc và gói ngôn ngữ đã tải. Nếu chia sẻ toàn màn hình, dời bản dịch để không che chữ gốc. Nội dung bị ứng dụng khác chặn chụp màn hình có thể không đọc được.

**Đọc cả menu hoặc dịch chữ sai:** thu nhỏ khung quét, tránh điểm số và tên nút. Nếu chữ game quá nhỏ hoặc mờ, tăng kích thước phụ đề trong game.

**Dịch chậm hoặc máy nóng:** thử Dịch trên máy, giữ số lần quét mặc định, tắt đọc to nếu không cần. Giảm chất lượng Remote Play nếu hình bị giật; đừng tăng số lần quét liên tục để chữa lỗi mạng.

**Không nghe giọng:** bật Đọc to bản dịch, tăng âm lượng điện thoại và dùng Nghe thử. Kiểm tra giọng của ngôn ngữ dịch sang đã được tải.

**TV không kết nối:** kiểm tra app nhận đang mở, hai máy cùng mạng, đúng IP và đúng mã 8 số đang hiện. Wi-Fi khách có thể không cho các thiết bị nhìn thấy nhau.

**LG không cài/mở được:** kiểm tra Dev Mode Status còn bật, Key Server đang bật, Passphrase đúng hoa/thường và TV có mạng. Nếu Developer Mode đã hết hạn và app bị gỡ, bật lại theo hướng dẫn rồi cài lại.

**LG đang chơi thì mất phụ đề:** tránh Home, giữ TV ở HDMI, dùng Mở app đã cài từ điện thoại. Nếu chỉ kết nối được mà không hiện chữ trên HDMI, gửi model TV và phiên bản webOS cho người phát hành; không bảo đảm mọi TV đều hỗ trợ.

## 10. Báo lỗi để được hỗ trợ

Liên hệ [Telegram Console Translator](https://t.me/pstranslator). Gửi model điện thoại, phiên bản Android, tên game, đang dịch trên điện thoại hay TV và các bước dẫn đến lỗi. Với LG, thêm model TV và phiên bản webOS.

Có thể gửi ảnh thông báo lỗi sau khi che mã mời, Passphrase và thông tin cá nhân. Đừng gửi khóa API, mật khẩu hoặc file riêng của app.

[Chính sách quyền riêng tư](https://kyozxx.github.io/Console-Translator/privacy.html) · [Hướng dẫn bản iOS](https://kyozxx.github.io/PS-Translator/guide.html)
