
**KHUÔN MẪU REPOSITORY CHO CÁC DỰ ÁN**
Tài liệu, Tổ chức, Cấu trúc thư mục và các tiêu chuẩn khác áp dụng cho các dự án tại câu lạc bộ SINNO, [SOICT Innovation Club](https://soict.hust.edu.vn/sinno)

**QUI ĐỊNH**
- Tỷ lệ chú thích trong các đoạn mã >= 30% (File có 10 dòng thì có 3 dòng chú thích)
- Tài liệu phân tích thiết kế mức đỉnh có thể bằng công cụ bất kì. Thường dùng MS Excel, Word..
- Tài liệu phân tích thiết kế chi tiết PHẢI được sinh tự động từ mã nguồn, thông qua các công cụ sinh báo cáo tự động (xem bên dưới)
- Việc gửi email nên tuân theo qui tắc cho dễ tìm kiếm, tránh mất mát thông tin và dễ dàng cho người mới tham gia.
![Minh hoạ template](https://i.pinimg.com/originals/bc/b5/8e/bcb58e376794667e766572054f62d665.jpg)
![Minh hoạ thư](https://i.pinimg.com/originals/44/39/ef/4439efc28bd8115f649d83cd246bdd1f.jpg)

**MÁY ẢO**
- Hyper-V: tích hợp sẵn trong Windows 10. Thuận tiện và gọn nhẹ nếu máy tính host dùng Windows OS
- Docker
- VMWare
- VirtualBox
- Windows 10 sandbox

**MÁY CHỦ**
- [Heroku](https://www.heroku.com/): miễn phí nhưng chỉ 8h mỗi ngày, chỉ hỗ trợ linux
- [Googlab Colab](https://colab.research.google.com/notebooks/intro.ipynb): miễn phí, rất tốt để lập trình python, thực hiện các thuật toán AI (giới hạn thời gian chạy liên tục)
- SINNO Server: liên hệ với [BAN HẬU CẦN](http://sinno.soict.ai/org/logistics) để được hỗ trợ

**THIẾT KẾ GIAO DIỆN**
- [Balsamiq](balsamiq.com): thiết kế ý tưởng giao diện (GUI concept), miễn phí, có 2 bản cloud và desktop. 
    - Ví dụ [Thiết kế giao diện website SINNO](https://balsamiq.cloud/s42jjy8/pfo9sne)
    - Ví dụ [Thiết kế giao diện Bootstrap Admin](https://balsamiq.cloud/s42jjy8/pjpvtqo)
    ![Ảnh minh hoạ](https://balsamiq.com/assets/wireframes/controls-sketch-large.jpg)

**SINH BÁO CÁO**
- [Doxygen](https://www.doxygen.nl), kết hợp [Graphviz](https://graphviz.org/): phân tích toàn bộ thư mục code và tự sinh báo cáo, tự sinh các sơ đồ class, sơ đồ cây triệu gọi hàm. Rất tốt để phân tích và đọc hiểu mã nguồn mở, thuận tiện để làm báo cáo thiết kế chi tiết chương trình. Hỗ trợ nhiều loại ngôn ngữ
    - Hướng dẫn (https://youtu.be/Z_gsu84KLLo)
    - Minh hoạ (https://mcuoneclipse.com/2012/06/25/5-best-eclipse-plugins-1-eclox-with-doxygen-graphviz-and-mscgen/)
- JSdoc
- GhostDoc
- JavaDoc    
 ![Ảnh minh hoạ](https://camo.githubusercontent.com/2ffabc8c5e88a2d97aa5838d81007624aee1d7e0/68747470733a2f2f692e696d6775722e636f6d2f387863356568592e6a7067)

**QUẢN LÝ MÃ NGUỒN**
- [Hướng dẫn sử dụng lệnh GitHub](https://backlog.com/git-tutorial/vn/)
- [Mẫu repository chung cho các dự án](https://github.com/SOICTInnovationClub) của SINNO Club
- Lộ trình làm việc của một dự án [GitFlow](https://danielkummer.github.io/git-flow-cheatsheet/index.vi_VN.html)
- Tự động hoá với Git để mỗi khi commit code lên git, tự động kích hoạt các quá trình biên dịch cài đặt và triển khai trên serrver [Git Actions](https://hoangpn.com/p/tan-man-ve-github-actions), [Git Web Hook](https://viblo.asia/p/bat-dau-lam-viec-voi-github-webhook-jvElaOGDKkw)

**QUẢN LÝ CÔNG VIỆC**
- [Microsoft Planner](https://tasks.office.com/): có sẵn trong bộ Office365 của mỗi SV ở Bách khoa Hà Nội
- [Trello](https://trello.com/)
- [Base](https://base.vn/)
![Minh hoạ](https://techcommunity.microsoft.com/t5/image/serverpage/image-id/112758i61F9562D049C6513/image-size/large?v=1.0&px=999)

**TRAO ĐỔI THÔNG TIN**
- Email là phương pháp trao đổi chính thức nhất, có thể thay cho chữ kí, có ý nghĩa pháp lý.
- Ai đó trả lời thư thì KHÔNG ĐƯỢC TẠO THƯ MỚI, mà phải tìm lại thư cũ và reply lại để còn xem được lịch sử trao đổi. Như thế, người mới vào chỉ cần xem thư mới nhất cũng biết toàn bộ lịch sử trao đổi
- Khi trả lời thư, phải gửi cho tất cả mọi người trong team. Đó là nguyên tắc phẳng của Scrum. Mọi người đều phải biết việc nhau.
- Ai là người làm việc chính, hãy dear …… tên của anh ta. Người khác không xuất hiện tên ở dear…. thì tức là cần biết nhưng không phải làm.
- Tiêu đề thư phải có mã dự án phía trước. Điều này giúp thực hiện lọc và tô màu email để quản trị thư cho tốt.
![image](https://user-images.githubusercontent.com/8079397/114507323-2a452c00-9c5d-11eb-9961-7fba7235b7e4.png)
