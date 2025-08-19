

# 🧵 Pointer Operations in C++

## 🎯 Aim

To study and implement **pointer operations** in C++ and understand the difference between **Call by Value** and **Call by Reference**.

---

## 📚 Theory

* **Call by Value** → Function gets a copy, originals remain unchanged.
* **Call by Reference** → Function gets address/reference, originals can be modified.

---

## 📊 Comparison Table

| ⚙️ Feature       | 📦 Call by Value | 🔗 Call by Reference |
| ---------------- | ---------------- | -------------------- |
| Data Passed      | Copy             | Address/reference    |
| Affects Original | ❌ No             | ✅ Yes                |
| Memory Use       | Extra copy       | No extra copy        |
| Safety           | Safer            | Risk of side effects |
| Use Case         | Read-only ops    | In-place updates     |

---

## 📋 Algorithms

### 🔹 Employee Salary Increment (short)

1. Input employee details (years, research work, pipeline, profit, salary).
2. Count how many conditions are met.
3. If ≥3 → increase salary by 20%, print updated salary.
4. Else → print "Not eligible".

---

### 🔹 Reverse String using Pointers (short)

1. Input string `str`.
2. Point `ptr` to first character.
3. Print characters in reverse using pointer arithmetic.

---

## 🧠 Conclusion

* 📦 Call by Value → Safe, works on copies.
* 🔗 Call by Reference → Efficient, modifies originals.
* ✅ Use **Value** for read-only, **Reference** for in-place updates.


