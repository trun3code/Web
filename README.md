# Web
1. Các lỗi API và mã phản hồi
- 400 Bad_Request: Lỗi máy khách
- 401 UNAUTHORIZED: thiếu thông tin xác
- 403 FORBIDDEN: máy chủ từ chối ủy quyền
- 404 NOT_FOUND: không tìm thấy tài nguyên yêu cầu
- 500 INTERNAL_SERVER_ERROR: máy chủ lỗi, không thực hiện được yêu cầu
- 502 BAD_GATEWAY: phản hồi không hợp lệ từ máy chủ ngược dòng

- 200 OK: thành công
- 201 CREATED: tạo tài nguyên thành công
- 202 ACCEPTED: yêu cầu đã được chấp nhận
- 204 NO_CONTENT: 

2. Đường dẫn
- GET api/v1/user
- GET api/v1/user/{userID}
- GET api/v1/user/{userID}/orders
- POST api/v1/user
- DELETE api/v1/user/{userID}
