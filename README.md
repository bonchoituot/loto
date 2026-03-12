# 🎲 BONCT LOTO PLUGIN - SIÊU PHẨM LÔ TÔ TÀI NGUYÊN
```text
██████╗  ██████╗ ███╗   ██╗ ██████╗████████╗
██╔══██╗██╔═══██╗████╗  ██║██╔════╝╚══██╔══╝
██████╔╝██║   ██║██╔██╗ ██║██║        ██║   
██╔══██╗██║   ██║██║╚██╗██║██║        ██║   
██████╔╝╚██████╔╝██║ ╚████║╚██████╗   ██║   
╚═════╝  ╚═════╝ ╚═╝  ╚═══╝ ╚═════╝   ╚═╝   
         B O N   C H Ơ I   T U Ố T

🔥 Độc quyền phát triển bởi BonCT dành cho BonCity & Cộng đồng Minecraft! 🔥

Plugin Lô Tô thế hệ mới mang trải nghiệm chơi Lô Tô truyền thống vào Minecraft với cơ chế cược tài nguyên vật lý (Kim cương, Netherite...), tích hợp GUI xịn sò, hỗ trợ Resource Pack và hệ thống trừng phạt "Kinh Sộ" cực kỳ tàn khốc để chống gian lận lạm phát!

==========================================

🌟 TÍNH NĂNG NỔI BẬT (FEATURES)
💎 Cược Bằng Tài Nguyên: Không dùng tiền ảo (Vault)! Người chơi dùng trực tiếp các vật phẩm có giá trị (Netherite, Diamond, Táo vàng...) để góp vốn. Máy chủ tự động đếm, thu và chia phần thưởng.

🖼️ GUI Tương Tác Trực Tiếp: Chuột phải vào tờ vé số để mở Bảng dò. Bấm vào các con số để đánh dấu (Đỏ -> Xanh). Trạng thái được lưu vĩnh viễn vào bộ nhớ ngầm của tờ vé (PersistentDataContainer).

🎨 Hỗ Trợ Resource Pack (CustomModelData): Chuyển đổi các tấm kính nhàm chán thành những con số 2D tuyệt đẹp. (Mã Đỏ: 1001-1090, Mã Xanh: 2001-2090).

⚡ Hệ Thống Phạt "Kinh Sộ" (Anti-Troll): Dám báo Kinh (Bingo) khi chưa đủ số?

Đền bù: Bị hệ thống vét sạch túi để đền bù 50% vốn cho những người chơi khác.

Hình phạt: Tống vào tù (thời gian nhân đôi theo cấp số nhân mỗi lần tái phạm: 10p -> 20p -> 40p...) hoặc giáng thiên lôi giết chết ngay lập tức! Hệ thống tự động nuốt tài nguyên để chống farm đồ.

🛡️ Hoàn Tiền Thông Minh: Chủ phòng thoát game giữa chừng? Không sao! Máy chủ tự động hủy phòng và hoàn trả 100% tài nguyên về túi người chơi.

⚙️ Cấu Hình Tùy Biến (Configurable): Cho phép Admin đổi nguyên liệu cược, số lượng cược, tốc độ gọi số, bật/tắt nhà tù và việt hóa 100% tin nhắn.

==========================================

📥 HƯỚNG DẪN CÀI ĐẶT (INSTALLATION)
Tải file BonLoto-1.0.jar.

Copy file .jar vào thư mục plugins/ của server Minecraft (Hỗ trợ Spigot/Paper 1.21+).

(Tùy chọn) Cài đặt plugin EssentialsX nếu bạn muốn sử dụng tính năng Bỏ tù (use-jail: true). Nhớ setup một nhà tù tên là lotojail bằng lệnh /setjail lotojail.

Khởi động lại server hoặc dùng lệnh /reload.

Mở thư mục plugins/BonLoto/config.yml để tùy chỉnh theo ý thích.

Gõ /loto reload trong game để cập nhật cấu hình mới.

==========================================

📜 DANH SÁCH LỆNH & QUYỀN (COMMANDS & PERMISSIONS)

Lệnh (Command) | Chức năng (Description) | Quyền (Permission)

/loto start <vật_phẩm> <số_lượng>	Mở sảnh và cược tài nguyên.     | loto.start
/loto join      Tham gia sảnh đang mở (tự động thu phí).            | loto.join
/loto ru        Bắt đầu ván Lô Tô (Chỉ Host hoặc Admin).            | loto.run
/loto recall    Xem lại danh sách các số đã được gọi.               | loto.recall
/loto kinh      Hô KINH! (Có thể tự động kích hoạt qua GUI).        | loto.kinh
/loto cancel    Hủy ván đấu và hoàn tiền (Chỉ Admin).               | loto.admin
/loto reload	Tải lại file cấu hình config.yml.                   | loto.admin

==========================================

🎮 CÁCH CHƠI (HOW TO PLAY)
Mở sảnh: Một người chơi (Host) gõ lệnh /loto start netherite_ingot 8. Họ sẽ bị trừ 8 Netherite và nhận được 1 Tờ Vé Số Lô Tô.

Tham gia: Những người khác muốn chơi gõ /loto join. Máy chủ trừ 8 Netherite của họ và phát vé.

Bắt đầu: Host gõ lệnh /loto run để chốt sổ. Máy chủ bắt đầu gọi số ngẫu nhiên (mặc định 5s/số).

Dò số: Chuột phải vào Tờ Vé Số trên tay để mở bảng GUI. Nếu máy chủ gọi trúng số của bạn, bấm vào số đó để đổi sang Màu Xanh.

Chiến thắng (KINH): Khi bạn bấm đủ 5 số màu xanh trên cùng 1 hàng ngang, GUI sẽ tự động đóng và hô KINH! Máy chủ sẽ chờ 5 giây xem có ai Kinh trùng không, sau đó chia đều tổng số Netherite cho những người chiến thắng.

==========================================

🎨 HƯỚNG DẪN RESOURCE PACK
Để hiện số đẹp trong GUI, hãy tạo Resource Pack áp dụng cho vật phẩm PAPER (Giấy) theo mã CustomModelData sau:

1001 đến 1090: Tương ứng với Số Đỏ (Chưa dò) từ 1 đến 90.

2001 đến 2090: Tương ứng với Số Xanh (Đã dò) từ 1 đến 90.

==========================================

🌐 LIÊN HỆ & THEO DÕI BONCT (CONNECT WITH ME)
Nếu bạn thấy plugin này hữu ích, đừng quên thả một Sub và tham gia cộng đồng của Bon Chơi Tuốt nhé! Rất nhiều dự án hay ho (như BonCity, Game Việt Hóa...) đang được phát triển mỗi ngày.

📺 YouTube: https://youtube.com/@bonchoituot

📘 Facebook: https://facebook.com/bonchoituot

👾 Discord: https://discord.gg/ZkbsgasDBW
