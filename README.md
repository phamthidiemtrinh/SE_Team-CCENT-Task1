# **Mạng căn bản**

## 1. Mạng là gì?

- Mạng hê thống là mạng lưới bao gồm hai hoặc nhiều máy tính được liên kết để chia sẻ tài nguyên (như máy in và đĩa CD), trao đổi file, hoặc cho phép truyền thông điện tử. Các máy tính trên mạng có thể được kết nối thông qua dây cáp, sóng vô tuyến, vệ tinh, hoặc sóng hồng ngoại.

- Hai loại rất phổ biến của mạng là :
 - Local Area Network (LAN)
 - Wide Area Network (WAN)
 
## 2. thành phần vật lý thường gặp của một mạng

- PC: các thiết bị là điểm cuối trong một mạng (có vai trò gửi và nhận dữ liệu) đồng thời cũng là những severs.
- Interconnections: Bao gồm các thành phần là phương tiện để chuyển dữ liệu từ điểm này đến điểm khác trong một mạng, bao gồm:
 - Network interface Card (giao diện mạng) : dịch dữ liệu thành một đinh dạng để truyền.
 - Network media: bao gồm dây cáp hoặc phương tiện truyền thông không dây cho phép các tín hiệu được truyền đi.
 - Connectors: cung cấp điểm đấu nối cho các phương tiện truyền thông.
- Switches : Các hệ thống đầu cuối thường được kết nối với switches.
- Routers: được sử dụng để kết nối các network khác nhau và họ hỗ trợ lựa chọn con đường tốt nhất để truyền dữ liệu giữa hai network.
- WLAN Devices : Wireless LAN of WAN devices conect network devices

## 3. Interpreting a Network Diagram

![](https://s-media-cache-ak0.pinimg.com/736x/1f/99/4f/1f994fc1ef103836bb36309c5e32e1a0.jpg)

- Router : 

![](http://ptgmedia.pearsoncmg.com/images/art_wilkins_nwdgcrint/elementLinks/thfig7_wilkins_network-diagram.jpg)

- Switch:

![](http://ptgmedia.pearsoncmg.com/images/art_wilkins_nwdgcrint/elementLinks/thfig1_wilkins_network-diagram.jpg)

## 4.Resource chia sẻ và lợi ích

- Dữ liệu và ứng dụng: người dùng có thể chia sẻ file, sofwaves chương trình ứng dụng.
- Nguồn: bao gồm các thiết bị đầu vào và thiết bị đầu ra.
- lưu trữ mạng: Direct attached storage (DAS), network attched storage (NAS), storage area network (SANs)
- các thiết bị sao lưu: cung cấp  phương tiện trung tâm để lưu các tập tin từ nhiều máy tính, có khả năng lưu trữ và khắc phục sự cố .

## 5. Ứng ụng mạng:

- E-mail( yahoo, gmail, outlook...)
- trình duyệt web (chrom, ...)
- Chat (yahoo, facebook, zalo...)
- ứng dụng làm việc tập thể.
- Cơ sở dữ liệu (file sevrers)

## 6.Ảnh hưởng của các ứng ụng người ùng lên hệ thống mạng

-  Bacth Application: không có sự tương tác giữa người sử dụng với hệ thống ( có thể thời gian sẽ lâu), băng thông quan trọng nhưng không cấp thiết.
- interactive application : có sự tương tác giữa hệ thống và người sử dụng (truy vấn kiểm kê, cập nhật liệu), thời gian nhập liệu là quan trọng nhưng không quá cấp thiết.
- real-time application : có sự tương tác giữa người với người, độ chờ cấp thiết ( thời gian truyền dữ liệu trong hệ thống càng ít càng tốt

## 7.Đặc tính kỹ thuật của mạng


- Tốc độ đường truyền
- Chi phí của viêc xây đựng hệ thống mạng
- tính bảo mật của mạng.
- Tính sẵn sàng của mạng.
- Khả năng mở rộng mạng
- Độ tin cậy của ường truyền trong hệ thoóng mạng
- Sơ đồ mạng

## 8. Sơ đồ đấu nối vật lý

- đấu nối dạng Bus: các máy đấu nối vào một cáp trục ở giữa, khi một máy truyền tín hiệu thì toàn bộ các máy còn lại đều nhận được dữ liệu.

![](http://echip.vietnamnetjsc.vn/2013/04/06/07/26/Network00202.png)



- đấu nối dạng vòng: các máy đấu nối liên tục với nhau thành dạng vòng tròn. Để tính dự phòng cao hơn sẽ có sơ dồ kép (dual-ring), các vòng có chiều truyền dữ liệu khác nhau, khi 1 vòng xảy ra lỗi thì còn vòng còn lại vẫn hoạt đông bình thường.

![](http://2.bp.blogspot.com/-6KrFRX0ehD0/VoHrhB1eXkI/AAAAAAAAAKA/CeyIJFBhB0s/s1600/vong.png)


- đấu nối dạng sao: máy truyền dữ liệu thông qua maý trung tâm và chỉ thị ra máy nhận dữ liệu, nếu máy trung tâm xảy ra lỗi thì toàn bộ hệ thống ngừng hoạt động. Có dạng sao mở rộng, chia hệ thống ra nhiều cụm nhỏ với các máy trung tâm nhỏ khác nhau, nếu một máy trung tâm của một cụm xảy ra lỗi thì chỉ cụm đó dừng hoạt động và các cụm còn lại vẫn hoạt động bình thường.

![](http://img.quantrimang.com/photos/image/092011/14/BitTorrent-1.jpg)

## 9.Con đường di chuyển dữ liệu trong hệ thống mạng
- có thể con dường di chuyển đữ liệu trong mảng trùng với sơ dồ vật lý hoặc không

## 10. Kiến trúc đấu nối
- full-mesh: 
 - từ một thiết bị đó đường kết nối tới tất cả các thiết bị còn lại trong hệ thống.
 - tính chịu lỗi cao, tính dự phòng cao.
 - chi phí quản lí đắt.
- pastial-mesh : cải tiến từ full-mesh, chỉ lưới môt phần ( nối các điểm quan trọng, giảm thiểu đường kết nối dư thừa) đảm bảo tính dự phòng và tiết kiệm chi phí.

## 11. kết nối đường truyền internet
- kết nối ADSL (Asymmetric Digital Subscriber Line) - đường truyền kết nối dùng chung- đường thuê bao bất đối xứng.
- cable (cáp)  cáp quang
- CSU/DSU  (leased line) - kênh thuê riêng - kết nối trực tiếp các node mạng thông qua kênh truyền dẫn số liệu thuê riêng.

 
# OSI - TCP//IP

## 1. Truyền thông host-to-host
- host là một thực thể có khả năng truyền được các ứng dụng (PC...)
-  xây đựng mô hình cho truyền thông từ host tới host
 - Older model : properetary(tính độc quyền) chỉ những thực thể có cùng nguồn gốc (hãng) mới có thể truyền với nhau; mặt khác chúng chỉ sử dụng được các app , sofwaves của chính hãng cung cấp.
 - Standards- base model: tương tác đươc với tất cả thực thể, tương thích với cả những phần mền của nhiều hãng khác nhau; xây dựng dựa trên phương pháp phân lớp.
 
## 2. Mô hình phân lớp
- Để truyền dữ liệu từ một host đến một host khác cần qua nhiều công việc, vì vậy cần chia thành nhiều nhóm công việc có tính chất tương tự nhau . việc chia nhóm công việc được gọi là phân lớp.
- Lợi ích của phân lớp :
 - Giảm độ phức tạp của việc truyền dữ liệu, chuyên môn hóa sản xuất ( công ty nào có thế mạnh về nhóm công việc thì sản xuất các thiết bị hoăc phần mềm cho nhóm công việc đó)
 - Chuẩn hóa sản phẩm, quy định chuẩn kỹ thuật chung.
 - Đảm bảo tính tương thích về mặt công nghệ.
 - thúc đẩy sự phát triển công nghệ ( do không còn tính độc quyền)
 - đơn giản học trong việc nghiên cứu và học tập
 
##  3. mô hình OSI ( open system interconnection)
![](http://tuhocmang.com/wp-content/uploads/2014/07/OSI.png)

- **Trong mô hình phân lớp:**
  - lớp Physical (lớp vật lý): truyền dòng bit thô qua đường truyền vật lý cụ thể. Nó định nghĩa các đặc tính kĩ thuật về điện, cơ, quang, đặc tính kỹ thuật trong việc thiết lập, giải phóng , duy trì một đường truyền nào đó.
  - lớp Data Link :điều khiển dữ liệu truy nhập vào đường truyền vật lý,giao tiếp vớilớp Network, cung cấp cơ chế dò lỗi
  - lớp Network :phân bố dữ liệu ( định tuyến các gói dữ liệu),xác định đường đi tối ưu nhất để phân phối dữ liệu,định địa chỉ logic cho hệ thống mạng( địa chỉ IP).
  - lớp Transport: quản lý các kết nối đầu cuối( end-to-end), xử lí vấn dề truyền dẫn giữa các host, đảm bảo dữ liệu truyền một cách tin cậy từ điểm này đến điểm khác trong mạng, thu hồi hoặc duy trì các kết nối ảo, cung cấp cơ chế dò lỗi, phục hồi dữ liệu.
  - lớp Session: thiết lập, quản lý và giải phóng các session giữa các ứng dụng ( tổ chức các phiên kết nối giữa các ứng dụng)
  - lớp Presentation: dảm bảo dữ liệu từ nơi guiẻ đến nơi nhận có thể đọc ddược, cung cấp cơ chế mã hóa.
  - lớp Application: giao tiếp trực tiếp với người dùng,cung cấp các ứng dụng mạng,cung cấp cơ chế xác thực người dùng.
  
 - **Cơ chế hoạt động** 
 ![](http://tuhocmang.com/wp-content/uploads/2014/07/data.png)
  - khi một host ( sender) dửi dữ liệu (user data) thì user data sẽ đi từ lớp 7 xuống lớp 1. khi qua mỗi lớp thì user data sẽ được đóng thêm một header ( header là phần thong tin quản lý của gói tin). khi đi đến lớp 2 , gói tin sẽ ddược đóng thêm phần kiểm tra lỗi FCS,đến lớp 1 thì dữ liệu được chuyển thì các bit nhị phân và di chuyển lên đường truyền
 - một host nhận ữ liệu sẽ làm ngược lại  (gỡ bỏ từng header từ lớp 2 đến lớp 7), ở lớp 1 các dãy nhị phân được chuyển dổi thành dữ liệu tương ứng.
- **Đơn vị dữ liệu:**
![](http://tuhocmang.com/wp-content/uploads/2014/07/1.png)
 - ứng với lớp physical : bits
 - ứng với lớp data link : frames
 - ứng với lớp network: packets
 - ứng với lớp transport : segment
 
## 4.mô hình TCP//IP
![](http://tuhocmang.com/wp-content/uploads/2014/07/2.png)

- chỉ gồm 4 lớp
- sử dụng tên khác nhau từ lớp 1 đến lớp 3 so với OSI
- gom từ lớp 5 đến lớp 7 của mô hình OSI thành lớp application
- so sánh mô hình TCP//IP và mô hình OSI:
![](http://tuhocmang.com/wp-content/uploads/2014/07/3.png)

- đa số các hệ thống sử dụng các giao thức của chồng giao thức TCP/IP nhưng lại toàn tham chiếu đến mô hình OSI 
 
 
