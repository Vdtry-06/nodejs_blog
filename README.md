1. HTTP: giao thức truyền tải siêu văn bản
SSR: server side rendering: HTML, CSS trả về trực tiếp
    tốt cho SEO (Search Engine Optimization), lượt truy cập đầu tiên nhanh, mỗi lần gửi yêu cầu phải refresh lại trang, thời gian phát triển nhanh hơn, tác vụ nhỏ
    trả về đủ dữ liệu không cần giao tiếp với api nữa
CSR: client side rendering: trả về thẻ div trống, đọc file js, js thực thi, thực thi xong mới append được content
    lượt truy cập đầu tiên chậm hơn, tác vụ dài hạn nên chọn vì có tính kế thừa, trả về khung, khi cần dữ liệu thì tải thêm

2. cài node.js
node -v npm -v: xem phiên bản
npm init
npm i express
npm i nodemon --save-dev
nodemon: lắng nghe sự thay đổi của file
inspector: debug
