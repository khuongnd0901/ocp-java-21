# 📝 OCP Java SE 21 (1Z0-830) – Personal Notes & Mistakes Log

> **Mục đích:** Ghi lại *NHỮNG GÌ ĐÃ SAI* khi làm Enthuware / mock test
> ❌ Không ghi lý thuyết lan man
> ✅ Chỉ ghi rule, bẫy, pattern dễ trượt

---
## Chủ đề chính:
* Handling Date, Time, Text, Numeric and Boolean Values
* Controlling Program Flow
* Using Object-Oriented Concepts in Java
* Handling Exceptions
* Working with Arrays and Collections
* Working with Streams and Lambda expressions
* Packaging and Deploying Java Code
* Managing Concurrent Code Execution
* Using Java I/O API
* Implementing Localization

---

## 📌 Cách sử dụng file này (rất quan trọng)

* Mỗi **câu sai / câu phân vân** → ghi 1 entry
* Không copy đáp án
* Luôn trả lời 3 câu hỏi:

  1. ❌ Mình sai ở đâu?
  2. 📐 Rule Java chính xác là gì?
  3. 🧠 Lần sau gặp lại, nhận diện thế nào?

---

## 🔥 GENERICS & COLLECTIONS

### ❌ Vấn đề / Câu hỏi

PECS – sử dụng `? extends` và `? super`

### ❌ Mình sai vì

* Nghĩ rằng `List<? extends Number>` có thể add `Integer`

### ✅ Rule đúng

* `? extends T` = chỉ đọc (producer), **không add** (trừ `null`)

### ⚠️ Bẫy Oracle

* Đề cho biến kiểu wildcard rồi gọi `add()`

### 🧠 Nhận diện nhanh lần sau

* Thấy `extends` → **READ ONLY**

---

## 🔥 CONCURRENCY & VIRTUAL THREADS

### ❌ Vấn đề / Câu hỏi

Virtual thread + ExecutorService lifecycle

### ❌ Mình sai vì

* Nghĩ rằng submit task xong là chắc chắn chạy

### ✅ Rule đúng

* Phải quản lý lifecycle: `shutdown()` / `close()` đúng lúc

### ⚠️ Bẫy Oracle

* Task submit nhưng executor bị shutdown sớm

### 🧠 Nhận diện nhanh lần sau

* Luôn check **executor lifecycle** trước khi kết luận

---

## 🔥 FUNCTIONAL / STREAM / OPTIONAL

### ❌ Vấn đề / Câu hỏi

Stream reuse

### ❌ Mình sai vì

* Nghĩ rằng có thể gọi `stream.count()` rồi `stream.forEach()`

### ✅ Rule đúng

* Stream **chỉ dùng 1 lần** – terminal operation đóng stream

### ⚠️ Bẫy Oracle

* Đề gọi nhiều terminal operations trên cùng stream

### 🧠 Nhận diện nhanh lần sau

* Thấy terminal op → stream **CHẾT**

---

## 🧱 OOP HIỆN ĐẠI (RECORDS / SEALED / PATTERN MATCHING)

### ❌ Vấn đề / Câu hỏi

Record constructor

### ❌ Mình sai vì

* Quên rằng record canonical constructor phải match component list

### ✅ Rule đúng

* Canonical constructor **không khai báo type** lại

### ⚠️ Bẫy Oracle

* Đề cho constructor sai signature

### 🧠 Nhận diện nhanh lần sau

* Constructor record ≠ class constructor

---

## ⚠️ EXCEPTIONS

### ❌ Vấn đề / Câu hỏi

Override method với checked exception

### ❌ Mình sai vì

* Nghĩ rằng subclass có thể throw exception rộng hơn

### ✅ Rule đúng

* Override **không được throw checked exception rộng hơn**

### ⚠️ Bẫy Oracle

* Method override + throws clause

### 🧠 Nhận diện nhanh lần sau

* Checked exception trong override = **chặt hơn hoặc bằng**

---

## 📦 MODULE SYSTEM

### ❌ Vấn đề / Câu hỏi

(requires, exports, opens…)

### ❌ Mình sai vì

* …

### ✅ Rule đúng

* …

### ⚠️ Bẫy Oracle

* …

### 🧠 Nhận diện nhanh lần sau

* …

---

## 🕒 DATE / TIME / IO

### ❌ Vấn đề / Câu hỏi

(Duration vs Period, immutable, path…)

### ❌ Mình sai vì

* …

### ✅ Rule đúng

* …

### ⚠️ Bẫy Oracle

* …

### 🧠 Nhận diện nhanh lần sau

* …

---

## 🧪 FULL MOCK TEST SUMMARY

### 🧾 Test name / ngày làm

* …

### 📊 Score

* …%

### 🔁 Nhóm lỗi lặp lại

* …

### 🎯 Việc cần ôn lại

* …

---

## 🧠 TOP 10 RULE PHẢI THUỘC TRƯỚC NGÀY THI

1. …
2. …
3. …
4. …
5. …
6. …
7. …
8. …
9. …
10. …

---

## 🚀 Ghi chú cuối

> File này chính là **cheat sheet cá nhân** trước ngày thi.
> Trước khi vào phòng thi: đọc lại file này, **KHÔNG đọc sách mới**.
