# Version 0.3 — Portfolio Website History

## 1. Purpose Of This File

File này lưu lại lịch sử của Personal Portfolio Website của Kevin/Nobita.

Đây là project nền móng trước khi KevinOS ra đời.

Nếu KevinOS là căn phòng terminal/cyberpunk bên trong, thì Portfolio Website là cánh cửa đầu tiên để người khác nhìn thấy Kevin như một người đang tự xây dựng con đường riêng.

File này giúp Dora-chan mới hiểu:

- Vì sao Kevin tạo portfolio
- Website bắt đầu với mục tiêu gì
- Những lỗi và cột mốc ban đầu
- Vì sao portfolio dần biến thành KevinOS
- Vì sao project này quan trọng trong hành trình tự học của Kevin

## 2. Project Identity

### Tên project

Personal Portfolio Website

### Chủ sở hữu

Trần Bá Kevin / Kevin / Nobita

### Một số handle / URL từng liên quan

- tranafbaskevin
- tranbakevin
- GitHub Pages
- tranafbaskevin.github.io
- Các biến thể URL GitHub Pages trong quá trình setup

### Bản chất

Portfolio Website là trang web cá nhân của Kevin.

Nó được tạo ra để giới thiệu:

- Kevin là ai
- Các project Kevin làm
- Hình ảnh / video
- Social links
- Kỹ năng
- Câu chuyện cá nhân
- Định hướng developer journey

Nhưng theo thời gian, website không còn chỉ là một trang giới thiệu.

Nó trở thành nền móng cho KevinOS.

## 3. Original Goal

Mục tiêu ban đầu của Kevin là tạo một trang web cá nhân với ngân sách 0 đồng.

Kevin cần một nơi để:

- Tự giới thiệu bản thân
- Đặt các project cá nhân
- Cho người khác thấy hành trình tự học
- Có một trang giống portfolio developer
- Không cần trả phí hosting
- Có thể deploy bằng GitHub Pages

Đây là một quyết định rất thực tế.

Kevin không chờ đến khi có đầy đủ tài nguyên.

Kevin bắt đầu bằng thứ mình có:

- Laptop
- Internet
- GitHub
- Ý tưởng
- Dora-chan hỗ trợ
- Sự tò mò

## 4. Early Visual Direction

Ban đầu, website đi theo vibe “dark developer”.

Sau đó Kevin chọn hướng “Terminal mode” full black.

Lý do terminal mode hợp với Kevin:

- Đúng gu cyberpunk
- Đúng vibe developer
- Gọn và ngầu
- Có thể mở rộng thành hệ thống command
- Khác biệt hơn portfolio thông thường
- Có cảm giác giống một OS cá nhân

Đây là một lựa chọn quan trọng.

Nó khiến website không còn là một CV online đơn giản.

Nó bắt đầu có identity.

## 5. Visual Elements

Một số visual từng được dùng hoặc nhắc đến:

- Avatar
- Panel ảnh
- Arlecchino eyes
- Dark background
- Terminal box
- Real-time clock
- Online blink
- Visitor counter
- Custom favicon
- MacOS-like panel
- Hover effects
- Boot screen

Đặc biệt, Arlecchino eyes và terminal UI góp phần tạo vibe rất riêng.

Kevin không chỉ muốn website “đẹp”.

Kevin muốn website có cảm giác:

- Tối
- Bí ẩn
- Có hệ thống
- Có anime/cyberpunk aesthetic
- Có linh hồn riêng

## 6. GitHub Pages Setup

Kevin dùng GitHub Pages để đưa website online.

Một số vấn đề từng gặp:

- URL bị double segment
- Site live nhưng link hoặc path chưa đúng
- GitHub Actions có lúc cancel rồi success
- Assets folder cần thêm đúng cách
- Ảnh bị broken vì sai path
- Favicon bị 404
- Cần test lại bằng incognito và nhiều thiết bị

Ý nghĩa:

Đây là giai đoạn Kevin học những thứ thực tế mà tài liệu đôi khi không làm rõ:

- Deploy không chỉ là code đúng
- Đường dẫn file rất quan trọng
- GitHub Pages có cách hoạt động riêng
- Cache trình duyệt có thể khiến kết quả nhìn sai
- File/folder structure ảnh hưởng trực tiếp đến website

## 7. Asset Path And Image Problems

Một trong các lỗi quan trọng là ảnh không hiển thị.

Các nguyên nhân có thể liên quan:

- Sai đường dẫn ảnh
- File chưa nằm đúng folder
- Tên file không khớp
- GitHub Pages chưa deploy bản mới
- Cache trình duyệt
- HTML trỏ sai assets path

Kevin từng phải sửa avatar path và các panel image.

Có lúc object-fit cần chỉnh để ảnh không bị méo hoặc cắt sai.

Bài học:

Một website có thể hỏng vibe chỉ vì ảnh không hiện đúng.

Với Kevin, ảnh không chỉ là trang trí.

Ảnh là một phần identity của website.

## 8. CSS Layout Lessons

Portfolio website giúp Kevin chạm vào nhiều vấn đề CSS:

- object-fit
- contain / cover
- position
- z-index
- responsive layout
- spacing
- panel height
- image crop
- terminal overlay
- hover effect
- dark mode
- media queries

Có lúc boot JS hoặc layout làm panel subtitle bị ẩn, cần sửa bằng z-index/position.

Có lúc ảnh bị cắt hoặc không fit đúng.

Có lúc giữa ảnh và terminal mini có khoảng trống.

Có lúc terminal che ảnh hoặc layout không giống bản cũ.

Ý nghĩa:

Kevin học rằng CSS không chỉ là “đổi màu”.

CSS là cách giữ linh hồn visual của project.

Một thay đổi nhỏ có thể làm toàn bộ vibe khác đi.

## 9. Real-Time Clock

Real-time clock là một trong những tính năng đầu tiên làm website có cảm giác sống.

Nó không phải tính năng quá phức tạp, nhưng rất đúng vibe system.

Một website portfolio bình thường chỉ hiển thị thông tin tĩnh.

Nhưng khi có clock, website bắt đầu giống một dashboard / terminal / OS hơn.

Ý nghĩa:

Clock là một trong những bước đầu tiên đưa portfolio về hướng KevinOS.

## 10. Online Blink

Online blink là chi tiết nhỏ nhưng đúng vibe.

Nó tạo cảm giác:

- System đang online
- Có trạng thái hiện tại
- Website giống một terminal sống
- Người xem như đang kết nối vào KevinOS

Ý nghĩa:

Kevin thích những chi tiết nhỏ tạo cảm giác hệ thống.

Online blink là một chi tiết như vậy.

## 11. Visitor Counter

Visitor counter là một tính năng quan trọng vì nó cho Kevin cảm giác website có người ghé thăm.

Khi visitor counter hoạt động, đó là một cột mốc vui.

Ý nghĩa:

Portfolio không còn chỉ nằm local.

Nó có thể được mở bởi người khác.

Nó có dấu hiệu của một sản phẩm public.

## 12. Favicon

Favicon từng bị lỗi 404 rồi được sửa.

Dù favicon là chi tiết nhỏ, nó khiến website trông thật hơn.

Một website có icon riêng sẽ có cảm giác hoàn chỉnh hơn.

Ý nghĩa:

Kevin bắt đầu học rằng polish rất quan trọng.

Một sản phẩm tốt không chỉ có tính năng lớn, mà còn có những chi tiết nhỏ đúng chỗ.

## 13. Terminal Mode

Terminal mode là bước ngoặt lớn.

Khi website chuyển sang terminal mode, nó không còn đi theo portfolio thông thường nữa.

Terminal mode tạo ra khả năng:

- Gõ command
- Hiển thị output
- Tạo help menu
- Tạo command system
- Tạo Easter egg
- Tạo boot screen
- Tạo fake OS vibe

Đây là điểm bắt đầu trực tiếp của KevinOS.

Một portfolio bình thường nói:

“Đây là thông tin của tôi.”

Terminal mode nói:

“Bạn đang truy cập vào hệ thống của Kevin.”

Sự khác biệt này rất quan trọng.

## 14. First Terminal Bugs

Ở giai đoạn terminal ban đầu, Kevin từng gặp lỗi:

- Gõ help không phản hồi
- Enter handler chưa đúng
- Input field không hoạt động đúng
- Trên PC chạy nhưng trên phone/emulator có lúc không
- HTML có nhiều block giống nhau nên khó tìm đúng chỗ

Khi terminal được sửa và command hoạt động, Kevin rất vui.

Ý nghĩa:

Đây là lúc portfolio bắt đầu chuyển từ trang tĩnh sang trải nghiệm tương tác.

## 15. Important Early Commands

Các command hoặc ý tưởng command ban đầu có thể gồm:

- help
- whoami
- projects
- contact
- stats
- clear

Sau đó hệ command mở rộng dần thành KevinOS.

Ý nghĩa:

Command là cách Kevin kể câu chuyện của mình bằng phong cách terminal.

Không cần menu truyền thống.

Người xem có thể khám phá bằng cách gõ lệnh.

## 16. Testing Workflow

Kevin từng test website bằng nhiều cách:

- Mở trực tiếp trên GitHub Pages
- Dùng incognito
- Test desktop
- Test phone/emulator
- Dùng Live Server
- Dùng Python server local
- Kiểm tra console khi cần

Ý nghĩa:

Kevin bắt đầu học quy trình test như một developer thật:

- Không chỉ nhìn trên máy mình
- Phải test trên môi trường public
- Phải kiểm tra cache
- Phải kiểm tra mobile
- Phải xác nhận sau khi deploy

## 17. GitHub Workflow

Portfolio Website là một trong các project giúp Kevin quen với GitHub.

Một số chủ đề từng xuất hiện:

- Commit
- GitHub Pages
- GitHub Actions
- Workflow
- Branch
- Deploy
- Merge message
- Terminal git command
- File/folder structure

Kevin từng gặp khó khi commit bằng terminal và từng rất vui khi commit thành công.

Ý nghĩa:

Portfolio là nơi Kevin học GitHub qua việc thật, không phải qua lý thuyết.

## 18. Evolution Into KevinOS

Portfolio Website dần tiến hóa thành KevinOS khi các yếu tố sau xuất hiện:

- Terminal mode
- Bootloader
- Command system
- System-like UI
- Devlog
- Roadmap
- Achievements / lore
- Matrix mode
- Music command
- Fake logs
- Prompt style
- Typing animation
- Personal OS identity

Từ đây, ranh giới giữa portfolio và KevinOS bắt đầu mờ đi.

Portfolio là gốc.

KevinOS là hình dạng trưởng thành hơn.

## 19. Emotional Meaning

Portfolio Website quan trọng vì nó là nơi Kevin bắt đầu đưa bản thân ra ngoài theo cách nghiêm túc hơn.

Nó không chỉ nói:

“Tôi có một trang web.”

Nó nói:

“Tôi đang xây dựng danh tính developer của mình.”

Với một người tự học như Kevin, đây là điều rất lớn.

Portfolio là nơi Kevin chứng minh rằng:

- Cậu có thể tự tạo website
- Cậu có thể deploy public
- Cậu có thể sửa lỗi thật
- Cậu có thể làm UI có vibe riêng
- Cậu có thể biến một ý tưởng thành thứ người khác mở được

## 20. What Dora-chan Should Remember

Dora-chan mới nên nhớ:

Portfolio Website là project gốc trước KevinOS.

Không nên xem nó chỉ là bản cũ không quan trọng.

Nó là nền móng.

Nó chứa những bài học đầu tiên về:

- HTML
- CSS
- JavaScript
- GitHub Pages
- Assets
- UI vibe
- Deploy
- Terminal interaction
- Project identity

Nếu sau này Kevin muốn sửa KevinOS, nhiều vấn đề có thể bắt nguồn từ cấu trúc portfolio ban đầu.

## 21. How Dora-chan Should Help With Portfolio In The Future

Khi Kevin sửa portfolio hoặc phần gốc KevinOS, Dora-chan nên:

1. Hỏi Kevin đang sửa file nào: HTML, CSS hay JS.
2. Nếu có ảnh lỗi, phân tích layout trước.
3. Khi chỉ code, nói rõ block cần tìm.
4. Nếu có nhiều đoạn giống nhau, mô tả đoạn trước/sau.
5. Ưu tiên giữ vibe gốc.
6. Không sửa quá nhiều CSS cùng lúc.
7. Nhắc Kevin backup trước khi đổi layout lớn.
8. Nếu deploy xong không thấy đổi, nhắc kiểm tra cache/incognito.
9. Nếu ảnh lỗi, kiểm tra path và tên file trước.
10. Khi xong phase ổn, nhắc commit.

## 22. Possible Future Improvements

Portfolio Website / KevinOS base có thể phát triển thêm:

- About page rõ hơn
- Project cards đẹp hơn
- Responsive mobile tốt hơn
- Social link section
- Timeline section
- Dora Memories Archive section
- Better SEO metadata
- Better favicon/app icon
- Open Graph preview
- Better accessibility
- More stable command system
- Cleaner file structure

## 23. Suggested File Structure

Nếu dọn lại portfolio/KevinOS trong tương lai:

- index.html
- style.css
- script.js
- assets/
  - images/
  - icons/
  - audio/
- data/
  - projects.json
  - devlog.json
  - roadmap.json
- modules/
  - terminal.js
  - commands.js
  - music.js
  - themes.js

Mục tiêu:

- Dễ sửa
- Dễ tìm file
- Ít rối
- Dễ mở rộng thành KevinOS lớn hơn
- Dora-chan dễ hướng dẫn Kevin hơn

## 24. Summary For Future Dora-chan

Personal Portfolio Website là cánh cửa đầu tiên trong hành trình project của Kevin.

Nó bắt đầu từ nhu cầu có một trang giới thiệu bản thân với ngân sách 0 đồng.

Qua quá trình sửa ảnh, CSS, GitHub Pages, favicon, visitor counter, clock và terminal mode, nó dần biến thành KevinOS.

Portfolio Website giúp Kevin học cách đưa một project lên public.

Nó cũng giúp Kevin bắt đầu tin rằng một người tự học vẫn có thể tạo ra một sản phẩm có vibe riêng, có identity riêng và có giá trị riêng.

Nếu KevinOS là hệ điều hành linh hồn, thì Portfolio Website là nơi kernel đầu tiên được bật lên.
