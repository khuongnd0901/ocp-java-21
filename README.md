# ocp-java-21
Cố gắng đậu Oracle Java SE 21 Developer Professional (1Z0-830)

# 🧠 Oracle Java SE 21 Developer Professional (1Z0-830)

> **Mục tiêu:** Đậu chứng chỉ OCP Java SE 21 và leverage cho định hướng **Senior Java Backend Developer**
> **Đối tượng:** Java Backend Developer ~5 năm kinh nghiệm
> **Thời gian:** 6–8 tuần (tối ưu – không học thừa)

---

## 🎯 Mục tiêu học

* Đậu chứng chỉ **Oracle Java SE 21 Developer Professional (1Z0-830)**
* Nắm vững Java hiện đại (17–21): records, sealed, virtual threads
* Tự tin phỏng vấn **Senior Java Backend Developer**

---

## 🗺️ Visual Roadmap (Tổng quan)

### 🟥 LEVEL 1 – CORE DECISION ZONES (🔥🔥🔥)

* Generics & Collections
* Concurrency & Virtual Threads
* Functional / Stream / Optional

### 🟧 LEVEL 2 – CORE LANGUAGE FEATURES (🔥🔥)

* OOP hiện đại (Records, Sealed, Pattern Matching)
* Exceptions

### 🟨 LEVEL 3 – SUPPORTING TOPICS (🔥)

* Module System
* Date / Time / IO

### 🟩 LEVEL 4 – LOW PRIORITY (biết là đủ)

* Annotations, Localization, Text Blocks

---

## ✅ Study Checklist

### 🟥 LEVEL 1 – CORE DECISION ZONES

#### ☐ Generics & Collections

* ☐ Generic class & method
* ☐ Bounded type (`<T extends Number>`)
* ☐ `List<? extends T>` (Producer – READ)
* ☐ `List<? super T>` (Consumer – WRITE)
* ☐ Raw type & type erasure
* ☐ `List`, `Set`, `Map` behavior
* ☐ `equals()` / `hashCode()` contract
* ☐ `Comparator` vs `Comparable`
* ☐ Immutable vs unmodifiable collection

#### ☐ Concurrency & Virtual Threads

* ☐ Thread lifecycle
* ☐ `synchronized` vs `volatile`
* ☐ Atomic classes
* ☐ Race condition
* ☐ ExecutorService lifecycle
* ☐ `submit()` vs `execute()`
* ☐ `shutdown()` / `awaitTermination()`
* ☐ Virtual Threads (Java 21)
* ☐ Platform thread vs Virtual thread

#### ☐ Functional / Stream / Optional

* ☐ Stream creation
* ☐ Intermediate vs Terminal operations
* ☐ Lazy evaluation
* ☐ Stream reuse (❌)
* ☐ Parallel stream behavior
* ☐ `Collectors` (grouping, mapping)
* ☐ `Optional.map` vs `flatMap`
* ☐ `orElse` vs `orElseGet`

---

### 🟧 LEVEL 2 – CORE LANGUAGE FEATURES

#### ☐ OOP hiện đại (Java 17–21)

* ☐ Inheritance & polymorphism
* ☐ Access modifiers (`protected` bẫy)
* ☐ Method overriding rules
* ☐ Records (canonical / compact constructor)
* ☐ Auto-generated methods in record
* ☐ Sealed classes (`permits`)
* ☐ Pattern matching (scope trong if/switch)

#### ☐ Exceptions

* ☐ Checked vs Unchecked
* ☐ Override + throws
* ☐ try-with-resources
* ☐ Suppressed exceptions
* ☐ Multi-catch

---

### 🟨 LEVEL 3 – SUPPORTING TOPICS

#### ☐ Module System

* ☐ `module-info.java` syntax
* ☐ `requires`
* ☐ `exports`
* ☐ `opens`
* ☐ `transitive`

#### ☐ Date / Time / IO

* ☐ `LocalDate`, `LocalDateTime`
* ☐ `Period` vs `Duration`
* ☐ Immutability
* ☐ `Path`
* ☐ `Files` API
* ☐ Checked exception trong IO

---

## 🧠 Oracle Exam Mindset – Hay bẫy kiểu gì?

### 🟥 Level 1 – Bẫy tư duy (giết senior)

* Generics: `extends` = đọc, **đừng add**
* Concurrency: luôn check **lifecycle + visibility**
* Stream: terminal op = **stream chết**

### 🟧 Level 2 – Bẫy chủ quan

* Record constructor rules
* Override method + checked exception

### 🟨 Level 3 – Bẫy đọc nhanh

* `exports` vs `opens`
* `Period` vs `Duration`

> **Câu thần chú:** *Compile được chưa? → Chạy có ổn không? → Có bẫy hành vi không?*

---

## 📆 Weekly Plan (tóm tắt)

* **Week 1:** Exam mindset + roadmap + setup
* **Week 2:** Generics & Collections
* **Week 3:** Concurrency & Virtual Threads
* **Week 4:** Functional / Stream
* **Week 5:** OOP hiện đại + Exceptions
* **Week 6:** Modules + Date/Time/IO
* **Week 7–8:** Enthuware full mock tests

---

## 🧪 Practice Strategy

* Udemy (Andrii Piatakha): học theo topic
* Enthuware: topic test → full test
* Ghi lỗi sai vào `ocp-notes.md`

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
