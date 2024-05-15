---
title: "Một số mẹo và thủ thuật khi làm việc trên MacOS"
date: 2024-05-15
---
Bài viết gom nhặt tạm một số mẹo và thủ thuật khi làm việc trên MacOS, sẽ được bổ cập dần dần theo thời gian :)

1. Cài đặt PATH
- Với shell mặc định zshrc: mở file .zshrc trong thư mục làm việc gốc ($HOME)
  + Chạy lệnh: nano $HOME/.zshrc
  + Thêm các dòng lệnh export:

        export CPATH=/opt/homebrew/include
        export LIBRARY_PATH=/opt/homebrew/lib
        export PATH=$PATH:$HOME/LMGC/rockable-folked/INSTALL

   + Tạo alias:
<pre><code>
        alias rrun="rockable"
        alias rsee="see"
        alias rclean="rrun -c"
        alias rcleana="rclean && rm *.tga"
        alias rrock="rrun input.txt && rsee"
</code></pre>
- Với shell khác...
2. Cài đặt package với homebrew

3. ...
