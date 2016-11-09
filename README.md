                                               <.> <.>  <.>BÁO CÁO HỌC HÀM<.> <.> <.>
<ul> <li>1.Khái niệm hàm:Là một đơn vị độc lập của chương trình.</li>a) Khái niệm: hàm là một đoạn chương trình đọc lập thực hiện một công việc và trả về kết quả cho chương trình gọi nó. </li>b) Đặc điểm:Là một đơn vị độc lập của chương trình.</li>
Không cho phép xây dựng một hàm bên trong một hàm khác.
<ul>2.Cú Pháp:

<ul> <li>Mẫu chung của các hàm như sau:</li>
</li>Kieu_tra_ve Ten_ham(Danh_sach_tham_so)</li>
</li>{ khai báo biến cục bộ;
    </li>lệnh;
    </li>return[biểu thức];
 </li>}</li>
 <li>Trong đó:
 </li>Các thành phần của hàm bao gồm:</li>
</ul>
<li> Nguyên mẫu của hàm
<li> Kiểu giá trị của ham
<li> Tên hàm
<li> Các tham số của hàm
<li> Nội dung cua hàm
<ul> <li>Ví dụ: tìm max của hai số a,b:

int max(int a,int b)

{

  if (a>b) return a;
  
  else return b;
  
}
<ul>3. Hàm có đối con trỏ
<ul> <li>đối của hàm kiểu dữ liệu nào thì tham soó thực tương ứng phải là địa chỉ của biến kiểu tương ứng.
<li>sử dụng khi muốn bảo lưu kết quả tính toán của các đối số trong hàm.
