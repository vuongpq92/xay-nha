# Mo Hinh 3D Kien Truc Nha Pho 3 Tang + Tum San Thuong (39.4m2)

Ung dung hien thi mo hinh 3D tuong tac kien truc va noi that thuc te cong trinh nha pho tai Phuong Binh Phu, Quan 6, TP.HCM (Thua 22, To 31, hem 4m thong ra Hau Giang).

## Trai Nghiem Truc Tuyen (GitHub Pages)
Sau khi kich hoat GitHub Pages, truy cap truc tiep tai:
- **Mo Hinh 3D Tuong Tac**: https://vuongpq92.github.io/xay-nha/
- **Ban Ve Ket Cau & Kich Thuoc CAD 2D**: https://vuongpq92.github.io/xay-nha/ketcau.html

---

## Thong So Kien Truc Ky Thuat

- **Dien tich dat quy hoach**: 39.4 m2 (mat tien vat goc xeo ranh lo gioi 2.92m).
- **Quy mo cong trinh**: 1 Tret, 2 Lau, 1 Tum san thuong (Tong chieu cao ~15.5m).
- **Chieu cao cac tang chuan**:
  - **Tang Tret**: 4.0m (Cot 0.00m -> +4.00m).
  - **Lau 1**: 4.0m (Cot +4.00m -> +8.00m).
  - **Lau 2**: 4.0m (Cot +8.00m -> +12.00m).
  - **Tum & San Thuong**: 3.5m (Cot +12.00m -> +15.50m).
- **Cua chinh tang tret**: Nhom kinh Xingfa 4 canh mau xam den, kich thuoc lot long **Ngang 2.15m x Cao 2.36m** (chuan Lo Ban), **toan bo tuong mat tien tret, tru cot va vach kẹp cua deu son trang dong bo 100%** voi cac tang lau phia tren, bac them op da hoa cuong den kim sa.
- **Cau thang tang tret**: Cau thang chu U dao chieu 180 do, ban thang rong **0.80m**, gom **21 bac cung Sinh**, chieu nghi tai cao do +2.00m, hanh lang ben hong rong **0.86m**.
- **Nha ve sinh tang tret**: Rong **1.20m**, bo tri bon cau khoi va ban da lavabo am ban, cua mo doi dien tuong hanh lang kin dao.
- **Cua hau ra sau**: Kich thuoc **Ngang 1.08m x Cao 2.15m**, thang truc hanh lang tao luong doi luu khong khi xuyen suot ngoi nha.
- **He cua so dong nhat Lau 1 & Lau 2 (Mat tien vat & Tuong hong phong sau)**: Tat ca 4 cua so deu dong nhat kich thuoc **Ngang 1.08m x Cao 1.26m** (bau cua cao 0.90m, da lanh-to cao 1.84m). Thiet ke chuan theo anh mau thuc te: O fix kinh suot lay sang phia tren cao 0.34m, phia duoi la 2 canh mo nhom Xingfa xam den lap nan hoa dong mang hoa van qua tram noi 3D (Diamond Medallions) sang trong.
- **Ban cong thut vao (Loggia) & Cua di Xingfa 2 canh Lau 1 & Lau 2**: Mang tuong thang mat tien thut vao 1.0m tao ban cong rong 1.52m x sau 1.0m co lan can kinh 1.1m, lap **bo cua di 2 canh nhom kinh Xingfa co o fix tren kich thuoc Ngang 1.20m x Cao 2.36m** (chuan theo anh mau thuc te), canh mo quay ra ban công, den LED tran chieu sang am cúng loai bo hoan toan khoang toi.
- **Tum & San Thuong (Cot +12.0m -> +15.5m)**: Khoi Tum (phong tho, tum thang, giat phoi) duoc **doi sat 100% ve vach sau nha** (dai 4.5m tu Z = -5.265m den -0.765m), mai tum dat bon nuoc inox va may NLMT. Mat truoc tum co **Cua di nhom kinh Xingfa duoc doi lech sang ben trai (thang truc hanh lang tu cau thang len)**, danh mang tuong dac ben phai rong 2.3m cho phong tho trang nghiem khong bi gio lua truc dien. Cua mo ra **San thuong phia truoc sieu rong rai (~6.0m chieu dai, dien tich >20m2)** voi **Gian lam Pergola 4 cot thep hop vuong van (3.1m x 2.3m)** nam gon 100% trong ranh nha khong bi loi ra ngoai, bo ban ghe cafe chill duoi bong mat va tiec BBQ ngoai troi, bon cay canh uon gon theo lan can goc vat.

---

## Cong Nghe Phat Trien
- **Three.js (r128)**: Render 3D WebGL truc tiep tren trinh duyet khong can cai dat plugin.
- **OrbitControls**: Dieu khien xoay 360 do, pan, zoom muot ma tren ca PC va cam ung cham dien thoai.
- **Tween.js**: Chuyen canh camera goc nhin thong minh.
- **Mobile Responsive UI/UX**:
  - **Zen Mode (`👁️`)**: Nut an/hien 100% giao dien de chiem nguong mo hinh 3D toan man hinh khong bi che khuat.
  - **Header thu gon thong minh**: O che do di dong (<768px), header tu dong thu nho thanh badge vien bo tron chi chiem <6% chieu cao man hinh, bam de bung xem day du thong tin.
  - **Thanh camera cuon ngang**: Cho phep nguoi dung dien thoai vuot ngang chuyen nhanh 10 goc camera dac sac (Tum, Ban cong Xingfa, Cua so vat, Cau thang U...).
  - **Auto Camera FOV**: Tu dong can chinh goc nhin rong (FOV 54) khi cam doc dien thoai de bao quat toan bo 15.5m chieu cao toa nha.


