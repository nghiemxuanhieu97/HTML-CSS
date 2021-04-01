# HTML-CSS

### **Học xong làm được gì?**
1. Xây dựng được giao diện website (giao diện tĩnh)
2. Phân tích giao diện website
3. Đặt tên class theo chuẩn BEM
4. Xây dựng layout với Flexbox
5. Làm hiệu ứng layout với animation
6. Xây dựng giao diện responsive
7. Các kỹ thuật nâng cao khác...

### **CSS selectors**
| Selector | Mô tả|
| --- | --- |
| .abc | Chọn tất cả thẻ có class="abc" |
| .name1.name2 | Chọn tất cả các thẻ có cả name1 và name2 được đặt trong thuộc tính class của nó. |
| .name1 <br>.name2 | Chọn tất cả các thẻ có class = "name2" là con của một phần tử có class="name1" |
| * | Chọn tất cả các thẻ |
| h2 | Chọn tất cả các thẻ h2 |
| div.box | Chọn tất cả thẻ div có class="box" |
| div, h2 | Chọn tất cả thẻ div và h2 |
|div p | Chọn tất cả thẻ p trong thẻ div |
| div > p | Chọn tất cả thẻ p là con trực tiếp của thẻ div |
| div + p | Chon thẻ p đứng liền kề sau thẻ div |
| div ~ p | Chọn tất cả thẻ p đứng sau thẻ div |

Reference: https://www.w3schools.com/cssref/css_selectors.asp

Priority: !important > Inline > #id > .class > tag-name > *

### **CSS variable:** when you want to define a value global and reuse in many places.

### **CSS units:**

**1. Absolute units:** px, pt, cm, mm, inch, pc

**2. Relative units:** %, rem, em, vw, vh, vmin, vmax, ex, ch
* % will depend on \<tag> which contain it. `font-size: 100% = 16px`
* rem will depend on \<html> 
* em will depend on  \<tag> **close to it** and that \<tag> have **font-size**
* vw - viewport width, vh - viewport height: kích thước trình duyệt. `1vw = 1% kích thước chiều ngang trình duyệt`

### **CSS pseudo-classes**
* :root - lớp giả tham chiếu tới html
* :hover - lướt chuột qua \<tag>
* :active - giữ chuột vào \<tag>
* :first-child - select đứa con đầu tiên
* :last-child - select đứa con cuối

### **CSS pseudo-elements**
* ::before - Trong một list thẻ con nằm trong \<tag> thì ::before luôn ở đầu
* ::after - Trong một list thẻ con nằm trong \<tag> thì ::before luôn ở đầu
* ::first-letter - Chữ cái đầu của text
* ::first-line - css cho dòng đầu tiên
* ::selection - css khi bôi chuột




