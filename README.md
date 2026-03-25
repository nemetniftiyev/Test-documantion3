# Test-documantion3
# BookNest - QA Documentation

## * Layihə Haqqında
BookNest kitablar və müəlliflər haqqında məlumat platformasıdır. Bu sənəd layihə üçün hazırlanmış test planı, checklistlər, test caselər və yekun test summary reportu özündə birləşdirir. Məqsəd – platformanın sabitliyini, təhlükəsizliyini və istifadəçi dostu olmasını təmin etməkdir.

---

## * Test Plan
- **Funksional Testlər:** Əsas səhifə, kitab siyahısı, detallı səhifələr, qeydiyyat və giriş, qruplar bölməsi.  
- **Compatibility Testing:** Müxtəlif brauzerlərdə (Chrome, Firefox, Safari, Edge) və cihazlarda.  
- **Performance Testing:** Səhifə yüklənmə sürəti, media yükləmə vaxtı.  
- **Security Testing:** Şifrə gücü, yanlış giriş cəhdləri.  
- **UX Testing:** Mobil menyu, font oxunaqlılığı, rəng kontrastı, ikonların görünüşü, footer linkləri.  

---

## * Test Checklist
- [ ] Əsas səhifə problemsiz yüklənir  
- [ ] Kitab janrları düzgün siyahılanır  
- [ ] Digər səhifələr səhifələr açılır   
- [ ] Qeydiyyat prosesi uğurla tamamlanır    
- [ ] Login və logout funksiyaları işləyir  
- [ ] Qruplarda rəy əlavə etmək mümkündür  
- [ ] Media faylları uğurla yüklənir  
- [ ] Chrome, Firefox, Safari, Edge üzərində testlər uğurludur  
- [ ] Mobil versiyalarda UI elementləri düzgün görünür  
- [ ] Səhifə yüklənmə sürəti qənaətbəxşdir  
- [ ] Şifrə minimum tələblərə cavab verir  
- [ ] Yanlış giriş cəhdində xəbərdarlıq göstərilir  
- [ ] Footer linkləri düzgün işləyir  

---

## * Test Caselər
Test case-lər ayrıca `test-cases.md` faylında saxlanılır. Burada hər bir funksional, uyğunluq, performans və təhlükəsizlik ssenarisi addım-addım təsvir olunmuşdur.  
Misal:  
- **TC01 - Əsas səhifənin yüklənməsi**  
- **TC04 - Parol bərpa funksiyası**  
- **TC10 - Media faylı yükləmək**   
- **TC25 - Mobil menyu istifadəsi**  

---

## * Test Summary Report
- **Ümumi test caselər:** 40 
- **Uğurlu nəticələr:** 34 (84%)  
- **Uğursuz nəticələr:** 6 (16%)  

**Əsas problemlər:**  
- Mobil versiyada bəzi UI elementlərinin yerləşməsi düzgün deyil  
- Media fayllarının yüklənməsində performans problemi müşahidə olunur  

**Tövsiyələr:**  
- Mobil UI optimizasiyası aparılsın  
- Media faylları üçün yükləmə optimizasiyası tətbiq edilsin  
- Təhlükəsizlik tədbirləri gücləndirilsin  

---

## 🏁 Nəticə
BookNest platforması ümumilikdə stabil və işləkdir. Əsas funksiyalar uğurla testdən keçib. Mövcud problemlərin həlli ilə platforma daha etibarlı, sürətli və istifadəçi dostu olacaq.
