Câu 1:
Đoạn code này giúp bạn tách riêng từng kênh màu (Đỏ, Xanh lá, Xanh dương) của một ảnh màu, hiển thị và lưu lại từng ảnh kênh màu riêng biệt.
Câu 2 : 
Đoạn code này đọc một ảnh màu, tạo ra các phiên bản với thứ tự kênh màu khác nhau (RGB, GRB, BRG), và lưu các ảnh này ra file
Câu 3:
Chuyển ảnh từ hệ màu BGR sang hệ màu HSV (Hue - Sắc độ, Saturation - Độ bão hòa, Value - Độ sáng).
Tách ảnh HSV thành 3 kênh riêng biệt: H (sắc độ), S (độ bão hòa), V (độ sáng).
hue_img: Ảnh chỉ giữ thông tin sắc độ (H), còn S và V đều đặt giá trị tối đa (255) để sắc độ thể hiện rõ nhất.
sat_img: Ảnh chỉ giữ thông tin độ bão hòa (S), H đặt về 0 (màu đỏ), V đặt tối đa (255) để thể hiện rõ mức bão hòa.
val_img: Ảnh chỉ giữ thông tin độ sáng (V), H và S đều đặt về 0 để chỉ còn lại độ sáng.
huyển từng ảnh HSV vừa tạo về hệ màu BGR để có thể lưu và hiển thị bằng các phần mềm thông thường.
Lưu từng ảnh kết quả ra file với tên tương ứng.
Đoạn code này đọc một ảnh màu, chuyển sang hệ màu HSV, tách riêng từng kênh (H, S, V), tạo các ảnh chỉ thể hiện từng kênh, chuyển về BGR và lưu lại.
Kết quả giúp bạn quan sát riêng biệt sắc độ, độ bão hòa và độ sáng của ảnh.
Câu 4:
Đoạn code này đọc một ảnh màu, chuyển sang hệ màu HSV, giảm giá trị sắc độ (H) và độ sáng (V) xuống còn 1/3 so với ban đầu, giữ nguyên độ bão hòa (S), sau đó chuyển lại về ảnh màu và lưu kết quả.
Kết quả là ảnh sẽ có màu sắc và độ sáng bị giảm mạnh so với ảnh gốc.
Câu 5
Đoạn code này đọc ba ảnh xám, áp dụng mean filter (bộ lọc trung bình 5x5) để làm mờ từng ảnh, sau đó lưu lại các ảnh đã làm mờ với tên mới.
Mean filter giúp giảm nhiễu và làm mịn ảnh.
