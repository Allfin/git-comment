Berikut adalah daftar **konvensi pesan commit** yang sering digunakan dalam pengembangan perangkat lunak, terutama dengan **Git**, untuk menjaga riwayat commit terorganisir dan deskriptif.

---

### **Konvensi Commit yang Sering Digunakan**

#### **1. `feat` (Feature)**
Digunakan untuk menambahkan fitur baru pada proyek.

- **Contoh:**
  - `feat: add user authentication`
  - `feat: implement dark mode toggle`

---

#### **2. `fix` (Bug Fix)**
Digunakan untuk memperbaiki bug atau masalah dalam kode.

- **Contoh:**
  - `fix: resolve header alignment issue`
  - `fix: correct typo in login error message`

---

#### **3. `refactor` (Refactoring)**
Digunakan untuk mengubah struktur atau kualitas kode tanpa mengubah perilaku fungsionalitas.

- **Contoh:**
  - `refactor: simplify API request logic`
  - `refactor: reorganize folder structure`

---

#### **4. `style` (Styling)**
Digunakan untuk perubahan yang hanya terkait dengan format, seperti indentasi, spasi, tanda baca, atau kode linting. Tidak ada perubahan logika kode.

- **Contoh:**
  - `style: fix ESLint warnings`
  - `style: reformat code to match coding guidelines`

---

#### **5. `docs` (Documentation)**
Digunakan untuk memperbarui atau menambahkan dokumentasi proyek.

- **Contoh:**
  - `docs: update README with installation instructions`
  - `docs: add API usage examples`

---

#### **6. `test` (Testing)**
Digunakan untuk menambahkan atau memperbarui pengujian.

- **Contoh:**
  - `test: add unit tests for login component`
  - `test: update integration tests for API`

---

#### **7. `chore` (Chore)**
Digunakan untuk tugas-tugas yang tidak terkait langsung dengan fungsionalitas atau fitur, seperti pembaruan dependensi atau konfigurasi build.

- **Contoh:**
  - `chore: update Tailwind CSS to version 3.2`
  - `chore: configure Prettier for project`

---

#### **8. `perf` (Performance)**
Digunakan untuk perubahan yang meningkatkan kinerja.

- **Contoh:**
  - `perf: optimize database queries`
  - `perf: reduce image load time`

---

#### **9. `ci` (Continuous Integration)**
Digunakan untuk perubahan pada konfigurasi alat CI/CD seperti GitHub Actions, Jenkins, atau GitLab CI.

- **Contoh:**
  - `ci: fix deployment script`
  - `ci: add Node.js caching in GitHub Actions`

---

#### **10. `build` (Build System)**
Digunakan untuk perubahan yang memengaruhi sistem build atau dependensi eksternal.

- **Contoh:**
  - `build: update Webpack config for production`
  - `build: switch from npm to yarn`

---

#### **11. `revert` (Revert Commit)**
Digunakan untuk membatalkan commit sebelumnya.

- **Contoh:**
  - `revert: undo commit 123abc`

---

#### **12. `ci` (Continuous Integration/Deployment)**
Digunakan untuk perubahan pada konfigurasi atau skrip deployment/CI.

- **Contoh:**
  - `ci: fix Dockerfile for production build`
  - `ci: add caching for build pipeline`

---

#### **13. `hotfix`**
Digunakan untuk perubahan cepat dalam situasi darurat, biasanya untuk memperbaiki masalah kritis.

- **Contoh:**
  - `hotfix: resolve critical login issue`
  - `hotfix: fix broken deployment`

---

#### **14. `merge`**
Digunakan untuk commit hasil penggabungan (*merge*) dari branch lain.

- **Contoh:**
  - `merge: feature/login into main`
  - `merge: resolve conflicts with develop branch`

---

### **Format Konvensional: Conventional Commits**
Sebagian besar tim menggunakan format *Conventional Commits* yang mencakup **tipe**, **deskripsi**, dan kadang **scope**:

```plaintext
<type>(<scope>): <short description>
```

- **`<type>`:** Jenis commit (misal: feat, fix, refactor).
- **`<scope>`:** Opsional, menjelaskan bagian kode yang diubah (misal: login, header).
- **`<short description>`:** Deskripsi singkat perubahan.

---

### **Contoh Lengkap:**
```plaintext
feat(header): add sticky header with scroll animation
fix(auth): resolve token expiration issue
refactor(api): simplify error handling logic
docs(readme): update project setup instructions
chore(deps): update axios to version 1.2.3
```

Dengan mengikuti konvensi ini, riwayat commit Anda akan lebih rapi, profesional, dan mudah dikelola! 🚀
