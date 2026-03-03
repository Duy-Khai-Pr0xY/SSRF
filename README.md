# SSRF
#### Lợi dụng server của đối tượng để attacker thực hiện điều họ muốn
#### Lỗ hổng liên quan đến URL
# 1 số hàm PHP để gửi HTTP Request
#### file_get_contents, http_build_query, curl_exec, fopen(allow_url_fopen phải là TRUE),......
# Networking
#### 127.0.0.1 hay localhost được ngọi là (loopback Interface) nó được tạo ra để tự gửi và tự nhận lấy gói tin của mình
