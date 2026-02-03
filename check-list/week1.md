# 📆 DAILY CHECKLIST – WEEK 1 (OCP Java SE 21 – 1Z0-830)

> **Điều kiện đầu vào:**
>
> * Đã mua khóa Udemy (Andrii Piatakha)
> * Đã cài IDE (IntelliJ)
> * Đã cài JDK 21
>
> **Mục tiêu tuần 1:** Set đúng mindset OCP, hiểu đề thi đánh vào đâu, *chưa cần học sâu*
>
> ⏱ Thời gian: **45–60 phút/ngày**

---

## 🟢 DAY 1 – Hiểu cuộc chơi

### ☑ Việc cần làm

* ☑ Mở syllabus chính thức 1Z0-830
* ☑ Đọc:

    * Số câu: 50 câu
    * Thời gian: 120 phút
    * Format đề
* ☑ Lướt danh sách **chủ đề chính** (chỉ đọc tiêu đề)

### ☑ Việc KHÔNG làm

* ☑ Không học Java
* ☑ Không ghi chép chi tiết

### 🎯 Output cuối ngày

* ☑ Hiểu: **OCP = đọc code + rule Java**, không phải lý thuyết
* ☑ Biết Level 1 gồm: **Generics – Concurrency – Stream**

---

## 🟢 DAY 2 – Quét nhanh Java basics theo “exam mindset”

### ☐ Việc cần làm

* ☐ Udemy (Andrii Piatakha):

    * Java Basics
    * Data Types
    * Control Flow
* ☐ Xem ở tốc độ **x1.5 – x2**

### ☐ Việc KHÔNG làm

* ☐ Không pause ghi note
* ☐ Không code theo video

### 🎯 Output cuối ngày

* ☐ Nhận diện bẫy:

    * Scope
    * Shadowing
    * Fall-through
* ☐ Nhận ra: Oracle thích code **nhìn tưởng đúng nhưng sai**

---

## 🟢 DAY 3 – OOP scan nhanh

### ☐ Việc cần làm

* ☐ Udemy:

    * Inheritance
    * Polymorphism
    * Access modifiers
* ☐ Tập trung đặc biệt:

    * `protected` + package
    * Method overriding rules

### ☐ Việc KHÔNG làm

* ☐ Không đào sâu design pattern
* ☐ Không tối ưu code

### 🎯 Output cuối ngày

* ☐ Biết: override sai = **compile fail**
* ☐ Biết: `protected` là **bẫy kinh điển** trong OCP

---

## 🟢 DAY 4 – Đụng Enthuware sớm

### ☐ Việc cần làm

* ☐ Enthuware:

    * Tạo **mini test 10–15 câu (mixed topics)**
* ☐ Làm test nghiêm túc (không tra Google)

### ☐ Sau khi làm

* ☐ Mở / tạo file `ocp-notes.md`
* ☐ Ghi **ít nhất 2 lỗi sai đầu tiên**

### 🎯 Output cuối ngày

* ☐ Bị “đánh tỉnh” về độ bẫy của đề
* ☐ Bắt đầu quen cách Oracle ra câu hỏi

---

## 🟢 DAY 5 – Records & Sealed (Java 21 highlight)

### ☐ Việc cần làm

* ☐ Udemy:

    * Records
    * Sealed classes
    * Pattern matching (`if`, `switch`)
* ☐ Viết **5–10 dòng code test** trong IDE

```java
sealed interface Shape permits Circle {}
record Circle(int r) implements Shape {}
```

### ☐ Việc cần làm thêm

* ☐ Nếu có lỗi / thắc mắc → ghi **1 entry** vào `ocp-notes.md`

### 🎯 Output cuối ngày

* ☐ Hiểu: record constructor ≠ class constructor
* ☐ Hiểu scope của pattern matching

---

## 🟢 DAY 6 – Tổng kết tuần

### ☐ Việc cần làm

* ☐ Mở `README.md`
* ☐ Xem lại **Study Checklist**
* ☐ Đánh dấu:

    * 🔥 Cần học rất kỹ
    * 😐 Học vừa
    * ❌ Để sau

### 🎯 Output cuối ngày

* ☐ Biết chắc: **Week 2 = Generics & Collections (trận đánh đầu tiên)**
* ☐ Không còn mơ hồ lộ trình

---

## ✅ CHECKPOINT SAU WEEK 1

Sau tuần 1, bạn **KHÔNG cần**:

* Thuộc API
* Làm được đề khó

Nhưng bạn **BẮT BUỘC**:

* ☐ Có repo GitHub
* ☐ `README.md` hoàn chỉnh
* ☐ `ocp-notes.md` có **3–5 lỗi sai thật**
* ☐ Biết rõ **Generics – Concurrency – Stream** là tử huyệt

---

## ❌ Sai lầm cần tránh tuần 1

* Học quá sâu Java core
* Ghi chép như sinh viên
* Nghĩ “cái này dễ rồi” → skip

---

> **Ghi nhớ:** Tuần 1 không làm bạn giỏi hơn, nhưng quyết định bạn có đậu OCP hay không.
