# 🎲 BONCT LOTO PLUGIN - PREMIER RESOURCE-BASED BINGO

██████╗  ██████╗ ███╗   ██╗ ██████╗████████╗
██╔══██╗██╔═══██╗████╗  ██║██╔════╝╚══██╔══╝
██████╔╝██║   ██║██╔██╗ ██║██║        ██║   
██╔══██╗██║   ██║██║╚██╗██║██║        ██║   
██████╔╝╚██████╔╝██║ ╚████║╚██████╗   ██║   
╚═════╝  ╚═════╝ ╚═╝  ╚═══╝ ╚═════╝   ╚═╝   
         B O N   C H Ơ I   T U Ố T

🔥 Exclusively developed by BonCT for BonCity & the Minecraft Community! 🔥

A next-generation Loto (Bingo) plugin that brings the traditional experience into Minecraft with a physical resource betting mechanism (Diamonds, Netherite, etc.), a sleek integrated GUI, Resource Pack support, and a brutal "Kinh Sộ" (False Bingo) punishment system to prevent exploits!

---

## 🌟 KEY FEATURES

* 💎 Physical Resource Betting: Forget virtual currency (Vault)! Players use high-value items (Netherite, Diamonds, Enchanted Golden Apples, etc.) as their entry fee. The system automatically counts, collects, and distributes rewards.
* 🖼️ Interactive GUI: Right-click your ticket to open the marking board. Click numbers to toggle states (Red -> Green). Marked data is permanently stored in the ticket's NBT (PersistentDataContainer).
* 🎨 Resource Pack Support (CustomModelData): Easily replace boring glass panes with stunning 2D number textures. (Red IDs: 1001-1090, Green IDs: 2001-2090).
* ⚡ "Kinh Sộ" Punishment (Anti-Troll): Dared to call Bingo without enough marked numbers?
    * Compensation: The system clears your inventory to pay a 50% "scam fee" to other players.
    * Penalty: Get thrown into jail (time doubles exponentially: 10m -> 20m -> 40m...) or get struck by lightning and die instantly!
* 🛡️ Smart Refund System: If the host disconnects before starting? No problem. The server automatically cancels the lobby and refunds 100% of the resources to every participant.
* ⚙️ Fully Configurable: Admins can change allowed materials, bet amounts, call intervals, toggle jail features, and translate 100% of the messages.

---

## 📥 INSTALLATION

1.  Download BonLoto-1.0.jar.
2.  Drop the .jar file into your server's plugins/ folder (Supports Spigot/Paper 1.21+).
3.  (Optional) Install EssentialsX for the Jail feature (use-jail: true). Set up a jail named lotojail using /setjail lotojail.
4.  Restart your server or use /reload.
5.  Edit plugins/BonLoto/config.yml to your liking.
6.  Use /loto reload in-game to apply changes.

---

## 📜 COMMANDS & PERMISSIONS

| Command | Description | Permission |
| :--- | :--- | :--- |
| /loto start <material> <amount> | Open a lobby with a specific bet. | loto.start |
| /loto join | Join the active lobby (Auto-pays fee). | loto.join |
| /loto run | Start the game (Host or Admin only). | loto.run |
| /loto recall | View all numbers called so far. | loto.recall |
| /loto kinh | Call BINGO! (Auto-triggers via GUI). | loto.kinh |
| /loto cancel | Cancel the match and refund (Admin only). | loto.admin |
| /loto reload | Reload the config.yml file. | loto.admin |

---

## 🎮 HOW TO PLAY

1.  Open Lobby: A host types /loto start netherite_ingot 8. They pay 8 Netherite and receive a Loto Ticket.
2.  Join: Other players type /loto join. The server collects their 8 Netherite and gives them tickets.
3.  Start: The host types /loto run. The server begins calling random numbers (default: 5s interval).
4.  Marking: Right-click the ticket in your hand to open the GUI. If the server calls your number, click it to turn it Green.
5.  Victory (KINH): Once you mark 5 green numbers on the same horizontal row, the GUI auto-closes and calls BINGO! After a 5-second window for ties, the total prize pool is split among the winners.

---

## 🎨 RESOURCE PACK GUIDE

To display custom numbers in the GUI, apply a Resource Pack to the PAPER item using these CustomModelData IDs:
* 1001 to 1090: Red Numbers (Unmarked) 1 to 90.
* 2001 to 2090: Green Numbers (Marked) 1 to 90.

---

## 🌐 CONNECT WITH BONCT

If you find this plugin useful, drop a Sub and join the Bon Chơi Tuốt community! Many exciting projects (BonCity, Game Localizations...) are in active development.

* 📺 YouTube: https://youtube.com/@bonchoituot
* 📘 Facebook: https://Facebook.com/bonchoituot
* 👾 Discord: https://discord.gg/ZkbsgasDBW

***

Made with ❤️ by BonCT | © 2026 Bonchoituot

==========================================

# 🎲 BONCT LOTO PLUGIN - LÔ TÔ TÀI NGUYÊN
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
