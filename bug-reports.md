# Eventeam Bug Reports

## BUG-001: Required field boş saxlandıqda validation mesajı göstərilmir

**Severity:** Medium
**Priority:** High
**Issue Type:** Functional
**Module:** Create Event / Form Validation
**Environment:** Windows, Chrome

**Steps to Reproduce:**

1. Eventeam platformasına daxil ol.
2. “Create Event” səhifəsinə keç.
3. Required field-ləri boş saxla.
4. “Create” düyməsinə klik et.

**Expected Result:**

* Boş required field-lər üçün validation mesajı göstərilməlidir.
* Event yaradılmamalıdır.

**Actual Result:**

* Validation mesajı göstərilmir və istifadəçi hansı sahənin səhv olduğunu başa düşmür.

---

## BUG-002: Yanlış login məlumatı daxil edildikdə error mesajı aydın deyil

**Severity:** Low
**Priority:** Medium
**Issue Type:** UI / Content
**Module:** Login
**Environment:** Windows, Chrome

**Steps to Reproduce:**

1. Login səhifəsinə keç.
2. Yanlış email və ya yanlış şifrə daxil et.
3. Login düyməsinə klik et.

**Expected Result:**

* İstifadəçiyə aydın error mesajı göstərilməlidir.

**Actual Result:**

* Error mesajı aydın deyil və istifadəçi problemin səbəbini başa düşmür.

---

## BUG-003: Event detail page-də məlumatlar tam görünmür

**Severity:** Medium
**Priority:** Medium
**Issue Type:** UI
**Module:** Event Detail Page
**Environment:** Windows, Chrome

**Steps to Reproduce:**

1. Event list səhifəsinə keç.
2. Hər hansı event-ə klik et.
3. Event detail page-də məlumatları yoxla.

**Expected Result:**

* Event adı, tarix, saat, məkan və açıqlama tam görünməlidir.

**Actual Result:**

* Bəzi event məlumatları tam görünmür və layout pozulur.

---

## BUG-004: Search nəticələri düzgün filterlənmir

**Severity:** Medium
**Priority:** Medium
**Issue Type:** Functional
**Module:** Search
**Environment:** Windows, Chrome

**Steps to Reproduce:**

1. Event list səhifəsinə keç.
2. Search input sahəsinə mövcud event adı yaz.
3. Nəticələri yoxla.

**Expected Result:**

* Axtarış nəticələri daxil edilən açar sözə uyğun göstərilməlidir.

**Actual Result:**

* Uyğun olmayan event-lər də nəticələrdə görünür.
