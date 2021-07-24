# Các toán tử trong Javascript

## Phép toán (cộng trừ nhân chia)

Cộng trừ nhân chia các giá trị trong 1 biến:

Ví dụ:  

        var a = 5;
        var b = 10; 
        var c = a + b; 
        var d = a - b;
        alert (c);

## Phép toán gán (gán cho biến mới có giá trị liên quan đến biến cũ)

Ví dụ:

    var x = 12;
    x = y; // x và y đều bằng 12.

    var x=10;
    var y=15
    x+=y; // x lúc này bằng x ban đầu cộng với y là bằng 25.

    var x=20;
    var y=15;
    x-=y; // x lúc này bằng x ban đầu trừ đi y là bằng 5.

Tương tụ như các phép toàn x*=y (x bằng x nhân y) và x/=y (x bằng x chia y).

## Phép toán quan hệ

    > lớn hơn
    < nhỏ hơn
    >= lớn hoặc hoặc bằng thì là True, nhỏ thì False
    <= nhỏ hơn hoặc bằng thì là True, lớn hơn thì False
    == bằng nhau thì là True, nhỏ hơn thì là False
    != khác nhau thì True, giống nhau thì False

## Toán tử lý luận

    &&: gọi là và hay AND , trả kết quả là True nếu 2 trường hợp đều đúng
    
    Ví dụ:

            if (a > 10 && b > 10){
                a + b > 10;
            } // Nếu a lớn 10 và b lớn 10 thì a cộng b chắc chắn lớn hơn 10.

    ||: gọi là Hoặc hay OR, trả kết quả là True nếu 1 trong 2 tường hợp đúng

    !: NOT hoặc gọi là Không