# YÊU CẦU ĐẦU RA

## Phần 1: Phân tích
 - Sự nhầm lẫn của An về mặt tư duy trong cách dùng lệnh tìm kiếm trong PowerShell là: Câu lệnh Get-Childitem là câu lệnh dùng để tìm vị trí và danh sánh các file trong FODER mà bạn An lại dùng câu lệnh này để tìm nội dung "404" nên TERMINAL mới không trả về kết quả nào bên trong tệp
 - Phân biệt giữa 2 câu lệnh Get-content và Select-String:

   1: Câu lệnh Get-content: Là câu lệnh dùng để tìm vị trí và cái file trong FODER

   2: Câu lệnh Select-String: Là câu lệnh dùng để chọn nội dung mà mình tìm kiếm trong tệp mà mình đã chọn

## Phần 2: Hoàn thiện

Câu lệnh FowerShell để lọc từ khóa ERROR và hiển thị số kí tự dòng để kỹ sư dễ tra cứu: 

Select-String access.log -Pattern "ERROR"
