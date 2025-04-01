# **Tic-Tac-Toe Game (C++)**

## **Giới thiệu**
Đây là một trò chơi **Tic-Tac-Toe** đơn giản được viết bằng ngôn ngữ **C++**, nơi người chơi đấu với máy tính. Trò chơi sử dụng console để hiển thị bàn cờ và nhập nước đi. Máy tính chọn nước đi một cách ngẫu nhiên.

## **Cách chơi**
1. Chạy chương trình trên trình biên dịch C++ có hỗ trợ **`iostream`** và **`ctime`**.
2. Người chơi sẽ nhập một số từ **1-9** để đặt dấu **"X"** vào vị trí tương ứng trên bảng.
3. Máy tính sẽ tự động chọn một vị trí ngẫu nhiên cho dấu **"O"**.
4. Trò chơi tiếp tục cho đến khi có người thắng hoặc kết quả hòa.

## **Điều kiện thắng**
- Người chơi hoặc máy tính chiến thắng nếu có **3 ký hiệu liên tiếp** theo hàng ngang, hàng dọc hoặc đường chéo.
- Nếu tất cả các ô đều được lấp đầy mà không có người thắng, trò chơi kết thúc với **kết quả hòa**.

## **Cấu trúc code chính**
- **`drawBoard()`**: Vẽ bảng Tic-Tac-Toe.
- **`playerMove()`**: Nhận nước đi từ người chơi.
- **`computerMove()`**: Máy tính chọn nước đi ngẫu nhiên.
- **`checkWinner()`**: Kiểm tra xem có người thắng không.
- **`checkTie()`**: Kiểm tra xem trận đấu có hòa không.

## **Yêu cầu hệ thống**
- Trình biên dịch C++ hỗ trợ **C++11** hoặc cao hơn (GCC, MSVC, Clang).
- Hệ điều hành: Windows, Linux, macOS.

## **Hướng dẫn chạy chương trình**
1. **Biên dịch code** bằng terminal hoặc command prompt:
   ```sh
   g++ tic_tac_toe.cpp -o tic_tac_toe
   ```
2. **Chạy chương trình**:
   ```sh
   ./tic_tac_toe
   ```

---
