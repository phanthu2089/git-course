## Compare
// 2 dấu bằng == kiểm tra giá trị
// 3 dấu bằng ===  : kiểm tra kiểu dữ liệu và giá trị
recommend dùng ===  vì chặt chẽ hơn
## for in :
1. lặp các thuộc tính trong object
2. truy cập imdex - trong array [1] -- truy cập đến index:0,1
## forEach :
1. lấy value, index trong mảng array
array_name.forEach((value, index) {
   console.log(`text ${value} text ${index}`)
});
## For...of  (array)
1. Lặp qua các phần tử trong mảng
 for (const value of array) {
 //code here
 }
 ## Continue
 1. bỏ qua vòng lặp, đoạn code > chạy qua vòng lặp tiếp theo
 ## break
 1. gặp đúng điều kiện thì bỏ qua tất cả và thoát