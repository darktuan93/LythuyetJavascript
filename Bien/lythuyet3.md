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

