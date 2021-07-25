## Các cấu trúc điều kiện trong Javascript

#### Cấu trúc vòng lặp for

Là vòng lặp có xác định giới hạn số lần lặp, dừng khi đạt giới hạn.

Ví dụ:

    var i;

    for (i = 0, i < 10, i++) {
        // câu lệnh thực thi.
    }

#### Cấu trúc vòng lặp while

Là vòng lặp không giới hạn số lần lặp, mà chỉ dừng khi có giá trị sai.

Ví dụ:

    var i = 1;

    while (i < 10 ) {
        document.write(i + '<br/>');
        i++;
    }

Ở ví dụ này thì cho biến i = 1, điều kiện lặp là i < 10. nếu không tăng i++ thì nó sẽ là điều kiện luôn luôn dẫn đến trường hợp lặp vô hạn, mãi mãi.

#### Vòng lặp do while

 Là vòng lặp thực hiện làm trước xong mới kiểm tra điều kiện.

 Ví dụ:

    var i = 1;

    do {
        document.write(i + '<br/>');
        i++;
    }
    while (i<10) ;