# MinesweeperSDL
- Lê Khả Thái Sơn - 21020088
# 1. Cách cài đặt game
- Cài đặt Visual Studio tại https://visualstudio.microsoft.com/downloads
- Tải game về bằng đường link https://github.com/21020088LeKhaThaiSon/MinesweeperSDL, chọn Code -> Download Zip. Giải nén và mở Visual Studio tới file SDLgame.sln.
  Hoặc có thể clone repo về máy tính qua đoạt git clone gh repo clone 21020088LeKhaThaiSon/MinesweeperSDL.
- Cách cài đặt SDL cho Visual Code: https://phattrienphanmem123az.com/lap-trinh-game-c-p2/game-cpp-phan-2-cai-dat-project.html, có sẵn SDL, SDL_image, SDL_tff và SDL_mixer trong file tải về.
- Chạy file MinesweeperSDL.exe để trải nghiệm game.
# 2. Mô tả chung về trò chơi
- Có 100 ô vuông 10x10, trong đó có 12 quả bom giấu kín trong 100 ô đó.
- Các ô mìn được tạo ngẫu nhiên, sau đó những ô còn lại sẽ đếm những trái bom xung quanh mình và tạo ra 1 con số thích hợp, nếu ko có trái nào thì sẽ để trống.
- Nhiệm vụ người chơi là mở được tất cả những ô không chứa bom.
- Click chuột trái để mở 1 ô, chuột phải để đặt cờ nếu người chơi nghi vấn ô đấy có bom, bấm chuột phải lần nữa để xóa bom. Nếu tất cả các ô không chứa bom được lật, người chơi thắng và ngược lại.
- Bấm R để chơi lại lần nữa, ESC để thoát.
# 3. Các chức năng đã cài đặt:
- 100 ô vuông để bấm và là chủ đề chính của trò chơi.
- Các đoạn text thể hiện số mìn, thể hiện thắng/thua, chơi lại.
- Thao tác chuột: trái để mở ô, phải để đặt/rút cờ.
- Âm thanh: tiếng click chuột, tiếng bom nổ khi thua, đoạn âm thanh khi thắng cuộc
- Thao tác phím: R để chơi lại, ESC để thoát game
- Video minh họa : https://www.youtube.com/watch?v=dpvfVrqJsd4
# 4. Các kĩ thuật lập trình được sử dụng
- Xài thư viện SDL: Màn hình game, các ô vuông để bấm, sự thay đổi các ô vuông khi click chuột, âm thanh click chuột để mở ô, âm thanh bom nổ khi thua cuộc và âm thanh phát ra khi thắng cuộc.
- Các class để cài âm thanh, hình ảnh, chuột bấm (được học từ Lazyfoo).
- Mảng để xử lý từng ô vuông trong 10x10 ô.
- Vòng lặp (for, while), logic (if-else) để xử lý logic game.
# 5. Kết luận, hướng phát triển game
Hướng phát triển:
- Vẫn còn chưa hiểu hết về SDL (nhiều đoạn code còn tham khảo Lazyfoo) nên sẽ tự tìm tòi, học hỏi để mở rộng game hơn: chia độ khó, tạo màn hình chơi game, điều chỉnh âm thanh (bật/tắt), thêm âm thanh dễ nghe trong lúc chơi game.
- Giúp người chơi tự tạo sân chơi game của mình (tự tạo bảng, số mìn).
Kết luận:
- Tự mình đã hiểu logic và tạo ra 1 phần con game tuổi thơ.
- Vẫn còn nhiều thứ để học hỏi và tìm tòi cách phát triển game, clean code và refactor cẩn thận hơn.
- Cố gắng tìm cách phát triển game tốt hơn để dễ thu hút người chơi.
