# ocp-java-21
Cố gắng đậu Oracle Java SE 21 Developer Professional (1Z0-830)

# 🧠 Oracle Java SE 21 Developer Professional (1Z0-830)

> **Mục tiêu:** Đậu chứng chỉ OCP Java SE 21 và leverage cho định hướng **Senior Java Backend Developer**
> **Đối tượng:** Java Backend Developer ~5 năm kinh nghiệm
> **Thời gian:** 6–8 tuần (tối ưu – không học thừa)

---

## 🎯 Chiến lược tổng thể

### ❌ Không làm

* Không học Udemy từ đầu đến cuối theo thứ tự
* Không học lại Java cơ bản một cách máy móc
* Không làm mock test khi chưa hiểu exam mindset

### ✅ Sẽ làm

* Học theo **tỷ trọng ra đề**
* Tập trung **đọc code + phân tích hành vi**
* Dùng **practice test để dẫn đường học**

---

## 📊 Tỷ trọng nội dung trong đề thi (ước lượng thực tế)

| Chủ đề                                  | Tỷ trọng | Mức ưu tiên |
| --------------------------------------- | -------- | ----------- |
| Generics & Collections                  | ~20%     | 🔥🔥🔥      |
| Concurrency (incl. Virtual Threads)     | ~20%     | 🔥🔥🔥      |
| Functional / Stream / Lambda            | ~15%     | 🔥🔥        |
| OOP hiện đại (Records, Sealed, Pattern) | ~15%     | 🔥🔥        |
| Exceptions                              | ~10%     | 🔥          |
| Modules                                 | ~10%     | 🔥          |
| IO / NIO / DateTime                     | ~10%     | 🔥          |

👉 **3 mảng đầu quyết định đậu hay trượt**

---

## 🧰 Công cụ & tài nguyên sử dụng

* **Udemy:** Andrii Piatakha – OCP Java 21 (1Z0-830)
* **Sách:** OCP Java 21 – Jeanne Boyarsky & Scott Selikoff (đọc chọn lọc)
* **Practice Test:** Enthuware (bắt buộc)
* **JDK:** Java 21 (LTS)
* **IDE:** IntelliJ IDEA

---

## 📆 Kế hoạch học chi tiết theo tuần

### 🗓 Tuần 0 – Setup (1–2 ngày)

**Mục tiêu:** Chuẩn bị đúng công cụ

* Cài JDK 21, IDE
* Mua Udemy + Enthuware
* Download syllabus chính thức Oracle
* Tạo file ghi chú: `ocp-notes.md`

---

### 🗓 Tuần 1 – Exam mindset + scan syllabus

**Mục tiêu:** Hiểu Oracle hỏi kiểu gì

* Xem Udemy (x1.5): Java basics, OOP overview (scan nhanh)
* Đọc skim sách OCP

✅ Kết quả cần đạt:

* Nhận diện dạng câu hỏi code-based
* Bắt đầu thấy các pattern bẫy

---

### 🗓 Tuần 2 – OOP hiện đại (ăn điểm chắc)

**Tập trung:**

* Records
* Sealed classes
* Pattern matching

Ví dụ:

```java
sealed interface Shape permits Circle, Square {}
record Circle(int r) implements Shape {}
```

⚠️ Bẫy thường gặp:

* Record constructor
* equals/hashCode auto-generated
* Scope của pattern matching

---

### 🗓 Tuần 3 – 🔥 Generics & Collections (QUAN TRỌNG NHẤT)

**Phải nắm chắc:**

* PECS (`extends` / `super`)
* Wildcards
* Raw types
* Behavior của `List`, `Set`, `Map`

👉 Tuần này **không chắc → rất dễ trượt**

---

### 🗓 Tuần 4 – Functional Programming & Stream

**Học hành vi, không học API:**

* Lazy evaluation
* Intermediate vs Terminal operations
* `Collectors` hay ra đề

⚠️ Bẫy:

* Stream reuse
* `Optional.map` vs `flatMap`

---

### 🗓 Tuần 5 – 🔥 Concurrency & Virtual Threads

**Senior advantage zone**

* Thread safety
* Memory visibility
* `synchronized` vs `volatile`
* Virtual threads (Java 21)

So sánh:

* Platform thread vs Virtual thread
* Executor cũ vs mới

---

### 🗓 Tuần 6 – Modules + IO + DateTime

**Học đủ dùng để thi**

* Modules: `requires`, `exports`, `opens`
* IO / NIO: đọc hiểu code
* DateTime:

  * `Period` vs `Duration`

---

### 🗓 Tuần 7–8 – 🔥 Practice Tests (QUYẾT ĐỊNH ĐẬU)

* Làm 2–3 full test Enthuware
* Review **từng câu sai**
* Ghi lại lỗi vào `ocp-notes.md`

🎯 Đánh giá mức sẵn sàng:

* ≥ 80% → thi ngay
* 75–80% → ôn lại Generics + Concurrency
* < 75% → delay thi

---

## ✅ Checklist trước ngày thi

* [ ] PECS & Wildcards
* [ ] equals / hashCode contract
* [ ] Checked vs unchecked exception
* [ ] Stream lifecycle
* [ ] Virtual thread usage
* [ ] `synchronized` vs `volatile`
* [ ] Module descriptor syntax
* [ ] Immutability
* [ ] Record constructors
* [ ] Pattern matching scope

---

## 🚀 Sau khi đậu

* Cập nhật CV:

```
Oracle Certified Professional
Java SE 21 Developer (1Z0-830)
```

* Chuẩn bị phỏng vấn Senior Java
* Học tiếp AWS SAA (System Design + Cloud)

---

## 📝 Ghi chú cá nhân

> File này dùng để theo dõi tiến độ và làm note ôn tập.
> Mục tiêu là **đậu OCP + nâng level Senior**, không phải sưu tầm chứng chỉ.
