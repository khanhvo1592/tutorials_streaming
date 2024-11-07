# Nguyên lý hoạt động của Streaming
Streaming là quá trình truyền tải dữ liệu liên tục từ một nguồn đến một hoặc nhiều thiết bị đích qua mạng internet. Nguyên lý hoạt động của streaming bao gồm các bước chính sau:

1. **Mã hóa (Encoding)**: Dữ liệu gốc (ví dụ: video, âm thanh) được mã hóa thành các định dạng nén để giảm kích thước và dễ dàng truyền tải qua mạng. Các định dạng phổ biến bao gồm H.264 cho video và AAC cho âm thanh.

2. **Phân đoạn (Segmenting)**: Dữ liệu mã hóa được chia thành các đoạn nhỏ hơn, thường là vài giây mỗi đoạn. Điều này giúp giảm độ trễ và cho phép người xem bắt đầu phát ngay lập tức mà không cần chờ tải toàn bộ nội dung.

3. **Truyền tải (Transporting)**: Các đoạn dữ liệu được truyền qua mạng internet đến thiết bị đích. Giao thức truyền tải phổ biến bao gồm HTTP Live Streaming (HLS), Dynamic Adaptive Streaming over HTTP (DASH), và Real-Time Messaging Protocol (RTMP).

4. **Bộ đệm (Buffering)**: Thiết bị đích nhận các đoạn dữ liệu và lưu trữ tạm thời trong bộ đệm. Bộ đệm giúp đảm bảo phát lại mượt mà ngay cả khi có sự gián đoạn tạm thời trong kết nối mạng.

5. **Giải mã (Decoding)**: Dữ liệu nén được giải mã trở lại định dạng gốc để phát lại. Thiết bị đích sử dụng các bộ giải mã (codec) tương ứng để thực hiện quá trình này.

6. **Phát lại (Playback)**: Dữ liệu đã giải mã được phát lại trên thiết bị đích, cho phép người xem thưởng thức nội dung trực tiếp hoặc theo yêu cầu.
![Nguyên lý hoạt động của Streaming](https://example.com/streaming_workflow.png)

Nhờ vào các bước trên, streaming cho phép truyền tải nội dung đa phương tiện một cách hiệu quả và tiện lợi, đáp ứng nhu cầu giải trí và thông tin của người dùng trên toàn thế giới.


# Hướng dẫn Streaming với ffmpeg
    
# Streaming với OBS

# Streaming với vMix

