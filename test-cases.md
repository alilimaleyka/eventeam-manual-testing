# Eventeam Test Cases

## TC-001: İstifadəçi qeydiyyatının yoxlanılması

**Precondition:**

* İstifadəçi Eventeam platformasına daxil olub.
* İstifadəçi hesabı mövcud deyil.

**Steps:**

1. Registration səhifəsinə keç.
2. Ad, soyad, email və şifrə məlumatlarını daxil et.
3. “Sign Up” və ya “Register” düyməsinə klik et.

**Expected Result:**

* İstifadəçi uğurla qeydiyyatdan keçməlidir.
* Sistem istifadəçini login səhifəsinə və ya əsas səhifəyə yönləndirməlidir.

---

## TC-002: Login funksiyasının yoxlanılması

**Precondition:**

* İstifadəçinin aktiv hesabı var.

**Steps:**

1. Login səhifəsinə keç.
2. Düzgün email və şifrə daxil et.
3. Login düyməsinə klik et.

**Expected Result:**

* İstifadəçi uğurla sistemə daxil olmalıdır.
* Dashboard və ya əsas səhifə açılmalıdır.

---

## TC-003: Yanlış login məlumatları ilə girişin yoxlanılması

**Precondition:**

* Login səhifəsi açıqdır.

**Steps:**

1. Yanlış email və ya yanlış şifrə daxil et.
2. Login düyməsinə klik et.

**Expected Result:**

* Sistem istifadəçini daxil etməməlidir.
* Uyğun error mesajı göstərilməlidir.

---

## TC-004: Event yaradılması funksiyasının yoxlanılması

**Precondition:**

* İstifadəçi sistemə daxil olub.

**Steps:**

1. “Create Event” səhifəsinə keç.
2. Event adı, tarix, saat, məkan və açıqlama məlumatlarını daxil et.
3. “Create” və ya “Submit” düyməsinə klik et.

**Expected Result:**

* Event uğurla yaradılmalıdır.
* Yaradılan event event list və ya dashboard-da görünməlidir.

---

## TC-005: Event detail page-in yoxlanılması

**Precondition:**

* Sistemdə ən azı bir event mövcuddur.

**Steps:**

1. Event list səhifəsinə keç.
2. Hər hansı event-ə klik et.
3. Event detail page-də məlumatları yoxla.

**Expected Result:**

* Event adı, tarix, saat, məkan və açıqlama düzgün görünməlidir.

---

## TC-006: Search funksiyasının yoxlanılması

**Precondition:**

* Event list səhifəsi açıqdır.

**Steps:**

1. Search input sahəsinə event adı yaz.
2. Search nəticələrini yoxla.

**Expected Result:**

* İstifadəçinin yazdığı açar sözə uyğun event-lər göstərilməlidir.

---

## TC-007: Filter funksiyasının yoxlanılması

**Precondition:**

* Event list səhifəsi açıqdır.

**Steps:**

1. Filter bölməsini aç.
2. Kateqoriya, tarix və ya məkan üzrə filter seç.
3. Nəticələri yoxla.

**Expected Result:**

* Seçilmiş filter-lərə uyğun event-lər göstərilməlidir.

---

## TC-008: Required field validation yoxlanılması

**Precondition:**

* Create Event səhifəsi açıqdır.

**Steps:**

1. Bütün input sahələrini boş saxla.
2. “Create” düyməsinə klik et.

**Expected Result:**

* Sistem boş required field-lər üçün validation mesajı göstərməlidir.
* Event yaradılmamalıdır.
