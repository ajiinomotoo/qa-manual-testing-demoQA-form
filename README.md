# 🧪 QA Manual Testing – DemoQA Form

## 📌 Project Overview

Proyek ini merupakan hasil praktik **manual testing** pada fitur *Automation Practice Form* di DemoQA.
Pengujian dilakukan untuk memastikan fungsi form berjalan dengan baik serta untuk mengidentifikasi bug atau anomali pada sistem.

---

## 🌐 Application Under Test

* URL: https://demoqa.com/automation-practice-form

---

## 🧑‍💻 Tester

* Nama: Aji Nugroho
* Role: QA Manual Tester

---

## 🧰 Testing Scope

Pengujian mencakup:

* Form submission (positive & negative case)
* Validasi input (email, mobile number, name)
* UI interaction (dropdown, date picker, modal)
* Edge case (input panjang)
* File upload

---

## 🧪 Testing Approach

Pengujian dilakukan menggunakan beberapa pendekatan:

* Positive Testing
* Negative Testing
* Validation Testing
* Edge Case Testing
* UI Interaction Testing
* Exploratory Testing

---

## 📊 Test Summary

| Item                | Result |
| ------------------- | ------ |
| Total Test Scenario | 13     |
| Total Test Case     | 13     |
| Passed              | 11     |
| Failed              | 2      |

---

## 🐞 Defects Found

### 1. Validation Issue – Name Field

* Field Name menerima input angka
* Form tetap dapat disubmit tanpa validasi

### 2. UI Issue – Close Button

* Tombol **"Close"** pada modal konfirmasi tidak berfungsi
* Modal hanya bisa ditutup dengan klik di luar area

---

## 📁 Test Artifacts

Repository ini berisi:

* 📄 Test Plan
* 📄 Test Scenario
* 📄 Test Case & Execution
* 🐞 Bug Report
* 📊 Test Summary
* 📸 Bug Evidence (screenshot)

---

## 🧠 Conclusion

Secara keseluruhan, fitur form pada DemoQA berjalan dengan baik untuk skenario utama (positive case).
Sebagian besar test case berhasil dijalankan sesuai dengan ekspektasi.

Namun, ditemukan beberapa bug terkait validasi input dan interaksi UI, khususnya:

* Validasi pada field Name
* Fungsi tombol "Close" pada modal konfirmasi

Disarankan untuk:

* Memperbaiki validasi input pada field Name
* Memastikan seluruh elemen UI berfungsi dengan baik
* Melakukan regression testing setelah perbaikan

---

## 🚀 Notes

Project ini dibuat sebagai bagian dari pembelajaran dan pengembangan skill di bidang **Quality Assurance (QA)**, khususnya dalam **manual testing**.

---
