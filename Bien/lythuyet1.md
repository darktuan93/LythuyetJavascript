## Biến trong Javascipt

### Có 3 cách khai báo biến trong javascript:
Là Var, Let, Const

* Dùng var khai báo biến.

 Cú pháp: Var *tenbien*; 

* Dùng let khai báo biến: Biến sử dụng trong phạm vi 1 khối. Có thể sử dụng để khai báo nhanh và sử dụng tạm thời, có hiệu lực trong 1 khối.

Ví dụ:

    if {
    let username="bachdangtuan";
    }

=> Sử dụng trong phạm vi lệnh if, ngoài phạm vi lệnh if không có hiệu lực. Anh em hiểu chứ?

* Dùng Const khai báo biến: Const là một hằng số khi khai báo biến bằng const thì phải gán giá trị cho nó luôn, sau này không thể thay đổi giá trị này được.

Ví dụ:

    Const username = "bachdangtuan";

----------------------------------------------

### Cách đặt tên cho biến trong Javascript

#### Quy tắt đặt tên:

Được sử dụng chữ,số, dấu __, -, viết hoa.

Đặc biệt (KHÔNG ĐỂ SỐ Ở ĐẦU TIÊN).

Ví dụ đặt tên sai:

    var 0username; ==> đặt tên kiểu này là sai.

#### Khai báo nhiều biến trên 1 hàng

Viết trên cùng 1 hàng, cách nhau bởi giấu phẩy (,) và kết thúc phải có giấu chấm phẩy (;).

Ví dụ:

    var abcd, _tuan, dangtuan93, abcd__2;

----------------------------------------------

### Cách gán giá trị cho biến 

Tức là khai báo biến và gán giá trị cụ thể cho biến vừa đặt.

#### Vừa khai báo và gán luôn
     
    var username = "hovaten"; 

có nghĩa là biến username có giá trị là **hovaten**

#### Khai báo biến xong mới gán

    var username;
    username = "hovaten";

    