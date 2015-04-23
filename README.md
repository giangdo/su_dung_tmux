# cach_su_dung_tmux

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

* Chia màn hình terminal theo chiều dọc hay chiều ngang một cách tùy ý. Mỗi phần terminal được chia này
  họat động như những terminal riêng rẽ và được gọi là các "pane".

  Ta có thể dùng phím nóng để di chuyển giữa các pane này rât thuận tiện.

  Kích thước của các pane cũng có thể thay đổi được. Ngoài ra TMUX còn một tính năng tuyệt vời nữa là 
  cho phép một pane mở rộng ra tòan màn hình một cách tạm thời rồi sau đó khôi phục lại nguyên trạng. 

* Cuộn để xem lịch sử hiển thị của một "Pane" trong tmux


* Tạo ra nhiều Window Tab, mỗi Window Tab có thể bao gồm nhiều "Pane" trong đó.
  
  Dùng phím tắt để di chuyển giữa các Window Tab


* Thanh trạng thái (bottom line) trong TMUX cũng có thể được tùy biến để giúp ta hiển thị ngày/giờ,
  tình trạng sử dụng cpu/ram, thời tiết hiện tại ... 
  
  
