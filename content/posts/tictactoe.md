+++
author = "dungpham"
draft = false
title = "Tic Tac Toe"
date = '2024-03-25'
description = "Guide to Tic Tac Toe"
tags = [
    "minimax theory",
]
+++

## TicTacToe and the Minimax algorithms

Thời gian gần đây với những khoảng thời gian rảnh rỗi mình sẽ thường tìm tòi và học thêm một số thứ mới trong lĩnh vực kỹ sư phần mềm. Tình cờ thay mình có học được một số kiến thức về lập trình động (dynamic programing), và áp dụng nó vào một trò chơi đơn giản là tic-tac-toe.

<!--more-->
Mình khá là khó khăn để có thể hiểu hết được các khái niệm về 'dynamic programming' và tự làm một trò chơi cho riêng mình, ngoài kia đã có một số bài viết khá hay về khái niệm minimax trong dynamic programming, và nó khá là khó hiểu với một đứa mới tiếp cận như mình. Vì vậy, mình mong bài viết này sẽ giúp các bạn hiểu rõ hơn.

Trước khi bắt đầu thì chúng ta cần làm rõ hai khái niệm đó là 'dynamic programming' và 'recursion':
Đầu tiền, 'dynamic programming' là kỹ thuạt giải quyết vấn đề bằng cách lưu trữ một số trạng thái kết quả giúp thuật toán hoạt động hiệu quả hơn.

Thứ hai, đệ quy 'recursion' hiểu đơn giản là một function gọi lại chính nó cho đến khi thỏa mãn một điều kiện nhất định.

Ở đây thì mình sẽ làm hai con bot. 1 là bot dễ 2 là bot không thể đánh bại.

[Web play!](https://dungpham.vercel.app/labs/ttt/tictactoe/)

<body>
<p>abc</p>
</body>