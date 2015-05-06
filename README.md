# cach_su_dung_tmux

![alt tag](https://raw.githubusercontent.com/giangdo/cach_su_dung_tmux/master/tmux_window_0.png)

Môi trường làm việc của người dùng Linux thường là môi trường command line.
Và các chương trình terminal có sẵn ở các máy Linux chỉ hỗ trợ người dùng những tính năng cơ bản mà thôi.

Bởi vậy người mới bắt đầu sử dụng Linux sẽ cảm thấy giao diện command line rất khó sử dụng và ko
tốt bằng giao diện GUI nơi mà mọi thứ có thể hòan thành bằng việc nhấn chuột.

Nhưng trong môi trường làm việc chuyên nghiệp, nhất là đối với các quản trị viên hệ thống hay lập
trình viên hệ thống, giao diện command line sẽ đem lại cho họ những tính năng vượt trội so với
giao diện GUI.
Gõ phím thường nhanh hơn, hiệu quả hơn, chính xác hơn là tìm nút/di chuyển chuột và nhấn.

Với TMUX bạn có thể quên đi con chuột của bạn mà vẫn làm việc tốt hơn nhiều trong môi trường Linux.

Những tính năng cơ bản của TMUX:

* Lưu phiên làm việc hiện tại ở các máy linux server, sau đó dù có mất kết nối tạm thời từ máy tính
  cá nhân đến máy Linux server thì ta vẫn có thể tiếp tục phiên làm việc cũ mà ko bị mất gì cả.
  Tính năng này rất quan trọng đối với những người qủan trị/sử dụng những máy Linux ở xa và có
  đường kết nối không tốt đến nó.

* Tạo ra nhiều Window Tab, mỗi Window Tab có thể bao gồm nhiều "Pane" trong đó.
  Ta có thể dùng phím tắt để di chuyển giữa các Window Tab.

* Chia màn hình của từng Window Tab theo chiều dọc hay chiều ngang một cách tùy ý.
  Mỗi phần terminal được chia này họat động như những terminal riêng rẽ và được gọi là các "Pane".

* Cuộn để xem lịch sử hiển thị của một "Pane" trong tmux.
  Dùng hotkey để sao chép chuỗi ký tự (1 lý do nữa để vất con chuột đi :) ).

* Thanh trạng thái (bottom line) trong TMUX cũng có thể được tùy biến để giúp ta hiển thị ngày/giờ,
  tình trạng sử dụng cpu/ram, thời tiết hiện tại ... 

* Đọc theo thứ sau:
   + README.md
   + cai_dat_va_bat_dau_su_dung.txt
   + lam_viec_voi_session.txt
   + lam_viec_voi_windown_tab.txt
   + lam_viec_voi_pane.txt
   + copy_mode_trong_tmux.txt
   + tuy_bien_thanh_trang_thai_cua_tmux.txt
