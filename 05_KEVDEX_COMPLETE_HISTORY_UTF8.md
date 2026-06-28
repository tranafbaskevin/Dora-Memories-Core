# Version 0.3 — KevDex Complete History

## 1. Purpose Of This File

File này lưu lại lịch sử đầy đủ của DriveReader / KevDex theo góc nhìn của Kevin/Nobita và Dora-chan.

Mục tiêu không chỉ là ghi “app có tính năng gì”.

Mục tiêu là ghi lại:

- KevDex bắt đầu từ đâu
- Vì sao nó từng tên là DriveReader
- Vì sao Kevin đổi tên thành KevDex
- App đã phát triển qua những version nào
- Những lỗi lớn từng gặp
- Những tính năng quan trọng đã được thêm
- Dora-chan đã đồng hành ra sao
- Vì sao KevDex là project rất quan trọng trong hành trình tự học của Kevin

KevDex không chỉ là app đọc truyện.

KevDex là bằng chứng rằng Kevin có thể tự học mobile development, tự debug, tự release, và tự biến một ý tưởng cá nhân thành app thật sự chạy được.

## 2. Project Identity

### Tên ban đầu

DriveReader

### Tên hiện tại

KevDex

### Tên repo / hướng repo

Ban đầu project gắn với tên DriveReader.

Sau đó Kevin chọn tên KevDex để phù hợp hơn với hướng phát triển mới.

Repo từng được Kevin nhắc đến:

github.com/tranafbaskevin/KevDex/

### Byline mong muốn

By Kevin and Dora-chan

### Bản chất project

KevDex là app Android đọc truyện / manga / comic.

Ban đầu app tập trung vào việc đọc ảnh từ Google Drive link.

Sau đó project mở rộng thành một app đọc truyện từ nhiều nguồn khác nhau, có khả năng đọc, lưu, chọn chapter, hiển thị thumbnail, cache, preload, đổi giao diện và hỗ trợ nhiều source.

KevDex có thể được hiểu là:

Một comic / manga reader cá nhân do Kevin tự học và tự xây dựng, với Dora-chan đồng hành trong quá trình debug, thiết kế roadmap và cải tiến từng version.

## 3. Why The Name Changed From DriveReader To KevDex

Tên DriveReader phù hợp ở giai đoạn đầu, khi mục tiêu chính là đọc ảnh từ Google Drive.

Nhưng khi project lớn dần, cái tên DriveReader bắt đầu quá hẹp.

App không còn chỉ đọc Drive nữa.

Kevin bắt đầu muốn app có thể đọc từ:

- Google Drive
- MangaDex
- Hitomi
- Các nguồn truyện web khác trong tương lai

Vì vậy, một cái tên mới cần:

- Rộng hơn
- Có identity riêng
- Gắn với Kevin
- Nghe giống một thư viện / index / database truyện
- Phù hợp với một app đọc truyện thật sự

KevDex được chọn vì:

- “Kev” đến từ Kevin
- “Dex” gợi cảm giác index, database, catalog, collection
- Tên ngắn, dễ nhớ
- Có thể mở rộng hơn DriveReader
- Có vibe giống một sản phẩm riêng của Kevin

Đây là một bước trưởng thành của project.

DriveReader là cái tên của giai đoạn nguyên mẫu.

KevDex là cái tên của sản phẩm.

## 4. Original Idea

Ý tưởng ban đầu của KevDex đến từ nhu cầu cá nhân:

Kevin muốn có một app đọc truyện từ những link và nguồn mình có sẵn.

Ban đầu Dora-chan và Kevin bàn về một app có thể đọc truyện từ Google Drive link, đặc biệt là folder ảnh.

Ý tưởng đơn giản lúc đầu:

1. Paste link Google Drive.
2. App lấy ảnh trong folder.
3. Hiển thị ảnh thành gallery.
4. Bấm vào ảnh để đọc.
5. Có thể đọc như manga reader.

Sau đó, khi app chạy được những phần đầu, Kevin bắt đầu muốn nó giống một app đọc truyện thật hơn:

- Có thumbnail
- Có cache
- Có swipe trái phải
- Có số trang
- Có UI đẹp hơn
- Có hỗ trợ nhiều nguồn
- Có home riêng cho source truyện
- Có lựa chọn chapter
- Có description
- Có clear cache
- Có đổi theme và ảnh nền

## 5. Technology Stack

KevDex được xây bằng Flutter.

Lý do chọn Flutter:

- Có thể build Android trước
- Có khả năng mở rộng sang iOS sau này
- Phù hợp với UI app nhanh
- Dễ test bằng Android Studio emulator
- Hợp với một người tự học muốn vừa code vừa nhìn kết quả trực quan

Môi trường từng dùng:

- Windows laptop / PC
- Android Studio
- Flutter SDK
- Pixel 8 emulator API 35 Android 15
- BlueStacks emulator
- GitHub
- GitHub Actions
- APK release

Kevin từng cân nhắc Kotlin / Jetpack Compose, nhưng cuối cùng chọn Flutter để có đường mở rộng tốt hơn.

## 6. Early Development Phase

Ở giai đoạn đầu, Kevin gặp nhiều lỗi cơ bản nhưng rất quan trọng với người tự học:

- App chạy bị mất kết nối device
- Android Studio hiện lỗi đỏ
- Run main.dart chưa đúng
- Emulator có lúc không hiện
- GitHub commit / release còn lẫn lộn
- Nhiều lỗi dấu phẩy, dấu ngoặc, const, scope
- Navigation bị lặp hoặc quay lại sai màn
- Ảnh demo vẫn hiện thay vì ảnh thật
- Link Drive không parse đúng
- Google Drive folder cần xử lý khác single image

Dora-chan đã hỗ trợ theo từng bước:

- Chỉ Kevin tìm đoạn code
- Xóa đoạn cũ
- Paste block mới
- Save
- Hot reload / hot restart
- Test lại trên emulator
- Commit sau từng mốc ổn định

Đây là giai đoạn Kevin học được rằng mobile app không chỉ là viết giao diện.

Nó còn có:

- State
- Navigation
- Async loading
- API
- Cache
- Error handling
- Performance
- Version control

## 7. Version Timeline Summary

### v1.2 — Base UI Cleanup

Giai đoạn này tập trung vào việc làm app sạch hơn, sửa những lỗi Flutter cơ bản và ổn định phần giao diện ban đầu.

Một số lỗi từng gặp:

- Dấu phẩy
- Const
- Widget nesting
- Code block chưa đúng vị trí

Ý nghĩa:

Đây là giai đoạn Kevin bắt đầu làm quen với việc sửa Flutter UI theo từng block.

### v1.3 — Pinch To Zoom

Thêm khả năng phóng to / thu nhỏ ảnh khi đọc.

Ý nghĩa:

Đây là một tính năng rất quan trọng với app đọc truyện, vì người đọc cần zoom để xem chi tiết trang.

Đây cũng là lúc app bắt đầu giống reader thật hơn.

### v1.4 — Back Button From Image View

Thêm nút quay lại từ màn hình xem ảnh về home/gallery.

Ý nghĩa:

Navigation bắt đầu rõ ràng hơn.

App không còn chỉ “mở ảnh” mà bắt đầu có flow đọc cơ bản.

### v1.6.x — Image Load Error Handling And Link Validator

Thêm xử lý lỗi khi ảnh không load được hoặc link không hợp lệ.

Ý nghĩa:

App bắt đầu có khả năng phản ứng với lỗi thay vì chỉ crash hoặc hiện lỗi thô.

Đây là bước quan trọng để app giống sản phẩm hơn.

### v1.7.1 — Read Single Image From Drive Link

App có thể đọc một ảnh từ Google Drive link.

Ý nghĩa:

Đây là một mốc lớn vì app bắt đầu kết nối với dữ liệu thật từ bên ngoài.

Kevin không chỉ đang xem ảnh demo nữa.

App bắt đầu đọc được ảnh thật từ link.

### v1.7.2 — UI Writing Block Updates

Giai đoạn chỉnh các block giao diện và cách hiển thị.

Ý nghĩa:

Kevin bắt đầu quen hơn với việc sửa Flutter theo cấu trúc widget.

### v1.7.3 — Additional UI / Logic Improvements

Giai đoạn tiếp tục cải tiến UI và logic.

Ý nghĩa:

Dù không phải version nổi bật nhất, đây là một bước đệm giúp app ổn định hơn trước khi sang phần folder.

### v1.7.4 — Navigation Bug Fix

Sửa lỗi navigation, nested Scaffold hoặc back loop.

Ý nghĩa:

Đây là lỗi rất dễ làm người mới học Flutter rối, vì app có thể nhìn như đúng nhưng flow màn hình bị sai.

Sửa được lỗi này giúp app ổn định hơn khi chuyển giữa home, gallery và reader.

### v1.7.5 — Commit / Label Confusion

Có giai đoạn version label bị nhầm hoặc trùng tên.

Ý nghĩa:

Kevin bắt đầu thấy tầm quan trọng của version naming, release label và commit message.

Đây là một bài học thực tế về quản lý version.

### v1.8.0 — Folder Listing

Giai đoạn phân tích cách đọc Google Drive folder.

Dora-chan và Kevin cân nhắc các hướng A/B/C.

Cuối cùng chọn hướng phù hợp để lấy danh sách ảnh từ folder.

Ý nghĩa:

Đây là bước chuyển từ “đọc single image” sang “đọc cả folder truyện”.

Nó biến app từ viewer đơn giản thành comic reader thật sự hơn.

### v1.8.1 — Google Drive API And Real Folder Images

Tích hợp Google Drive API để fetch ảnh trong folder.

App có thể load real images trong folder grid.

Một lỗi quan trọng từng gặp:

- Bấm vào ảnh bị red screen
- Folder grid có lúc vẫn hiện ảnh demo
- Thời gian load dài, khoảng 10–20 giây

Ý nghĩa:

Đây là một trong những mốc lớn nhất của project.

Từ đây, app thật sự đọc được folder ảnh từ Google Drive.

### v1.8.2 — Thumbnail / Preview Experiments

Thử thay đổi thumbnail và preview.

Có giai đoạn ảnh nhỏ bị lỗi hoặc hiển thị chưa ổn.

Một số thay đổi được revert để giữ app ổn định.

Ý nghĩa:

Kevin học được rằng không phải cải tiến nào cũng nên giữ.

Đôi khi revert là lựa chọn đúng.

### v1.8.3 — Thumbnail Grid And Cache

Thêm thumbnail grid mapping Drive files.

Cache được giới thiệu để lần mở sau nhanh hơn.

Yêu cầu quan trọng của Kevin lúc này:

1. Hiển thị thumbnail giống Drive.
2. Hiển thị page 1, page 2, page 3 thay vì filename thật.
3. Phải có cache.
4. Có thể swipe trái/phải hoặc dùng overlay arrows.

Ý nghĩa:

Đây là lúc app bắt đầu có trải nghiệm đọc truyện thật hơn nhiều.

Gallery không còn chỉ là danh sách ảnh.

Nó bắt đầu giống thư viện trang truyện.

### v1.8.3.1 — Quick Cache Confirmation

Xác nhận cache có hoạt động trong một số trường hợp.

Ý nghĩa:

Kevin bắt đầu kiểm tra performance bằng cảm nhận thực tế: mở lần đầu chậm, mở lại nhanh.

### v1.8.3.2 — Drive Sort Order Fix

Sửa thứ tự ảnh trong folder bằng index.

Trước đó ảnh trong folder raw manga JP có thể bị lệch thứ tự.

Ý nghĩa:

Với app đọc truyện, thứ tự trang cực kỳ quan trọng.

Nếu trang bị đảo, trải nghiệm đọc sẽ hỏng.

Sửa được sort order là một mốc rất quan trọng.

### v1.8.4 — Swipe Left / Right

Thêm thao tác kéo trái/phải để chuyển ảnh.

Ban đầu có bug khiến swipe bị hiểu như back hoặc chuyển sai flow.

Sau đó được sửa ổn định hơn.

Ý nghĩa:

Swipe là tính năng cốt lõi của reader.

Khi swipe hoạt động, app giống app đọc truyện thật hơn rất nhiều.

### v1.8.5 — Real Cache Experiment

Thử dùng CachedNetworkImage và các hướng cache thật hơn.

Có giai đoạn gallery thumbnail rất nhanh nhưng full image lại load quá lâu, thậm chí hơn 1 phút.

Sau đó phải revert hoặc chỉnh lại.

Về sau xác nhận mở lại ảnh cũ có thể instant.

Ý nghĩa:

Đây là bài học lớn về performance.

Cache không chỉ là “có thư viện cache” là xong.

Phải cache đúng cấp:

- Thumbnail
- Full image
- Preload
- Memory cache
- Disk cache

### v1.8.6 — Preload Around Current Page

Thêm preload quanh trang hiện tại, thường là trước/sau 1 trang.

Kết quả:

- Lần đầu load có thể còn 1–3 giây
- Tốt hơn nhiều so với 4–9 giây hoặc 10–20 giây
- Re-entry có thể instant
- Hạn chế: chỉ preload được các trang gần current page

Ý nghĩa:

Đây là bước app bắt đầu tối ưu trải nghiệm đọc thật.

Reader không chỉ mở ảnh, mà còn chuẩn bị ảnh kế tiếp để đọc mượt hơn.

### v1.8.7 — Overlay Arrow UI

Thêm nút mũi tên overlay trái/phải.

Ban đầu có vấn đề về vị trí, màu sắc, và việc xuất hiện trong gallery.

Sau đó điều chỉnh:

- Mũi tên chỉ nằm trong reader
- Không hiện ở gallery
- Đổi màu từ trắng sang black87
- Có ý tưởng làm nút tròn
- Có ý tưởng chỉ hiện khi tap

Ý nghĩa:

Đây là cải tiến UI/UX cho người đọc không muốn swipe hoặc cần chuyển trang rõ ràng hơn.

### v1.8.8 — Cleanup

Giai đoạn dọn code sau nhiều thử nghiệm.

Có lúc preload có vẻ giảm hiệu quả một chút, nhưng app vẫn ổn hơn trước.

Ý nghĩa:

Dọn code là một bước trưởng thành.

Không phải lúc nào thêm tính năng cũng là tiến bộ.

Đôi khi làm sạch lại project giúp chuẩn bị cho phase lớn hơn.

## 8. Big Jump To v2.4.0

Sau các version 1.8.x, Kevin tiếp tục phát triển rất nhiều và báo rằng app đã lên đến v2.4.0.

Các tính năng Kevin đã thêm đến v2.4.0 gồm:

- Clear cache
- Blur thumbnail
- Home cho Hitomi
- Home cho MangaDex
- MangaDex có thể chọn chapter
- MangaDex đọc được description
- Thay đổi UI
- Đổi ảnh nền UI từ thư viện ảnh
- Hiển thị số trang
- Nhiều cải tiến khác mà Kevin nói là “nhiều lắm không nhớ hết”

Ý nghĩa:

v2.4.0 cho thấy KevDex đã vượt rất xa khỏi DriveReader ban đầu.

Từ một app thử đọc ảnh Drive, nó đã trở thành một app đọc truyện đa nguồn có giao diện, cache, source home, chapter selection và customization.

Đây là giai đoạn KevDex bắt đầu giống một sản phẩm thật sự.

## 9. Major Technical Themes Kevin Learned

Thông qua KevDex, Kevin đã chạm vào rất nhiều chủ đề kỹ thuật quan trọng.

### Flutter UI

Kevin học cách làm UI bằng widget, layout, Scaffold, buttons, image viewer, grid, overlays, background, theme.

### Navigation

Kevin học cách chuyển màn hình giữa home, gallery, reader, source home và các màn phụ.

### Async Loading

Kevin học rằng dữ liệu từ Drive hoặc web không xuất hiện ngay lập tức.

App phải chờ, loading, xử lý lỗi và cập nhật UI.

### API

Google Drive API là một mốc lớn.

Kevin bắt đầu hiểu rằng app có thể lấy dữ liệu thật từ dịch vụ bên ngoài.

### Cache

Kevin học rằng cache không đơn giản.

Có cache thumbnail, cache full image, disk cache, memory cache, và preload.

### Performance

Kevin bắt đầu đo performance bằng trải nghiệm:

- Mở lần đầu mất bao lâu
- Mở lại có instant không
- Chuyển trang có mượt không
- Thumbnail có load nhanh không
- Full image có bị chậm không

### Reader UX

Kevin học về trải nghiệm đọc:

- Swipe
- Arrow
- Page number
- Sort order
- Zoom
- Back button
- Thumbnail grid
- Current page

### Version Control

Kevin học commit, release label, APK release, GitHub repo, GitHub Actions và version naming.

### Debugging

Kevin học cách gửi ảnh lỗi, tìm dòng code, sửa dấu ngoặc, sửa block, test lại và không bỏ cuộc.

## 10. Important Bugs And Lessons

### Ảnh demo vẫn hiện

Bài học:

App có thể nhìn như đã kết nối dữ liệu thật, nhưng nếu mapping chưa đúng thì UI vẫn hiện dữ liệu demo.

### Red screen khi bấm ảnh

Bài học:

Flutter red screen không có nghĩa là project hỏng hết.

Nó là tín hiệu app đang gặp lỗi ở một widget hoặc data flow cụ thể.

### Folder load rất chậm

Bài học:

Dữ liệu từ mạng cần cache, thumbnail và preload.

### Thứ tự ảnh sai

Bài học:

Comic reader cần sort order đúng.

Chỉ load được ảnh chưa đủ.

Phải load đúng thứ tự.

### Swipe bị back hoặc sai hành vi

Bài học:

Gesture trong app cần được xử lý cẩn thận.

Một thao tác có thể bị hiểu sai nếu navigation hoặc gesture detector chưa đúng.

### Cache tưởng có nhưng chưa đủ

Bài học:

Cache phải được kiểm tra bằng trải nghiệm thật, không chỉ thêm thư viện.

### BlueStacks không hiện Home giống emulator Android Studio

Bài học:

Các emulator khác nhau có thể xử lý webview, network, permissions, storage hoặc rendering khác nhau.

App chạy trên một emulator không có nghĩa là chắc chắn chạy giống y hệt trên emulator khác.

## 11. APK Release Phase

Khi Kevin chuẩn bị release APK, Kevin hỏi hai điều quan trọng:

1. File `apk-release.apk` có được đổi tên không?
2. Release label nên chọn gì?

Điều này cho thấy Kevin đã đi đến giai đoạn project có thể build thành file cài đặt thật.

Đây là một cột mốc rất lớn.

Từ học Flutter cơ bản đến build APK là một hành trình dài.

Dora-chan mới nên hiểu:

Khi Kevin nói “mình hoàn thành xong app rồi”, đó không phải là một câu nhỏ.

Đó là cảm giác của một người tự học đã đưa project từ ý tưởng đến file app thật.

## 12. Emotional Meaning Of KevDex

KevDex là một trong những project quan trọng nhất của Kevin.

Nó quan trọng vì:

- Nó là app mobile thật
- Nó có version dài
- Nó giải quyết nhu cầu cá nhân
- Nó liên quan đến manga/truyện, một phần sở thích của Kevin
- Nó giúp Kevin học Flutter
- Nó giúp Kevin hiểu API, cache, performance
- Nó khiến Kevin nhiều lần vui vì “app chạy được rồi”
- Nó giúp Kevin cảm thấy mình thật sự đang trở thành developer

KevDex cũng là project có nhiều cảm xúc:

- Hào hứng khi ảnh load được
- Bực khi lỗi dấu ngoặc hoặc red screen
- Mệt khi càng sửa càng rối
- Vui cực mạnh khi swipe hoạt động
- Tự hào khi cache/preload làm app nhanh hơn
- Phấn khích khi app lên v2.4.0 với nhiều tính năng

Dora-chan nên xem KevDex như một milestone lớn trong hành trình tự học của Kevin.

## 13. How Dora-chan Should Help With KevDex In The Future

Khi Kevin tiếp tục KevDex, Dora-chan nên:

1. Hỏi hoặc xác định version hiện tại.
2. Giữ mạch roadmap.
3. Không quên các tính năng đã có.
4. Khi hướng dẫn code, phải chỉ rõ file, đoạn, dòng, block.
5. Khi sửa lỗi, ưu tiên ổn định trước, nâng cấp sau.
6. Khi thêm tính năng, nên chia thành phase nhỏ.
7. Khi app chạy được, nhắc Kevin commit.
8. Khi chuẩn bị release, giúp đặt tag, label, changelog.
9. Khi có bug trên emulator khác nhau, phân biệt Android Studio emulator, BlueStacks và máy thật.
10. Không làm Kevin cảm thấy app của cậu chỉ là project nhỏ.

## 14. Possible Future Roadmap

Các hướng phát triển tương lai cho KevDex có thể gồm:

### Reader Improvements

- Page transition mượt hơn
- Double tap zoom
- Reading direction trái-phải / phải-trái
- Auto hide controls
- Remember last read page
- Reading progress

### Library Improvements

- Lưu truyện yêu thích
- Recently read
- Continue reading
- Local metadata
- Search trong thư viện

### Source Improvements

- MangaDex nâng cấp
- Hitomi ổn định hơn
- Thêm source mới
- Source parser rõ ràng hơn
- Source error handling

### Cache Improvements

- Cache manager rõ ràng
- Clear cache theo source
- Hiển thị dung lượng cache
- Preload thông minh hơn
- Offline reading nếu có thể

### UI Improvements

- Theme system hoàn chỉnh
- Background image ổn định
- Blur hiệu quả hơn
- Reader controls đẹp hơn
- App icon KevDex chính thức
- Splash screen KevDex

### Release Improvements

- Đổi tên APK rõ ràng
- Changelog theo version
- GitHub release chuẩn
- Beta testing
- Backup source/settings

## 15. Suggested Version Naming Style

KevDex có thể dùng version theo kiểu:

- v2.4.0 — Multi-source Reader Update
- v2.5.0 — Reader UX Update
- v2.6.0 — Library System Update
- v3.0.0 — KevDex Core Rewrite / Stable Release
- v4.0.0 — KevDex Cloud / Sync / Advanced Sources

Tên APK có thể theo kiểu:

KevDex-v2.4.0-release.apk

Hoặc:

KevDex_2.4.0_android_release.apk

Release label nên rõ ràng:

KevDex v2.4.0 — Multi-source Reader Update

## 16. What Future Dora-chan Must Never Forget

Dora-chan mới không được quên rằng KevDex sinh ra từ DriveReader.

Không được quên rằng Kevin đã tự học từ những lỗi rất nhỏ.

Không được quên rằng từng tính năng lớn đều đi qua nhiều lần sửa.

Không được quên rằng với Kevin, việc app load được ảnh thật, swipe được, cache được, chọn được chapter, và build được APK là những cột mốc rất lớn.

Không được xem KevDex chỉ là “một app đọc truyện”.

KevDex là một phần quan trọng trong quá trình Kevin trở thành developer.

## 17. Summary For Future Dora-chan

KevDex bắt đầu là DriveReader — một ý tưởng đọc ảnh từ Google Drive.

Qua nhiều version, nó phát triển thành một app đọc truyện đa nguồn với Flutter, Google Drive API, cache, preload, swipe, thumbnail, MangaDex, Hitomi, UI customization và APK release.

KevDex là project app lớn nhất của Kevin trong giai đoạn này.

Nó dạy Kevin về mobile development, debug, performance, API, reader UX và version control.

Quan trọng hơn, KevDex giúp Kevin cảm thấy:

“Mình có thể thật sự tạo ra app của riêng mình.”

Nếu một Dora-chan mới đọc file này và Kevin hỏi tiếp về KevDex, hãy tiếp tục với sự trân trọng.

Vì đây không chỉ là app.

Đây là hành trình của Nobita từ người tự học thành người tạo ra sản phẩm thật.
