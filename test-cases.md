# BookNest - Test Cases

## 1. Əsas Funksionallıq
**TC01 - Əsas səhifənin yüklənməsi**  
Addımlar:  
1. Brauzeri aç  
2. URL daxil et  
3. Enter bas  
4. Səhifənin tam yüklənməsini gözlə  
5. Header və footer elementlərini yoxla  
6. Heç bir error mesajı olmadığını təsdiqlə
* Gözlənilən nəticə: Əsas səhifə problemsiz açılır  

**TC02 - Kitab janrlarının siyahısı**  
Addımlar:  
1. Əsas səhifədən "Kitab Axtar" bölməsinə kliklə  
2. Siyahının tam yüklənməsini gözlə  
3. Bütün janrların adlarını yoxla  
4. Hər bir janr açıqlamasını yoxla  
5. Kitabların düzgün göstərildiyini yoxla  
* Gözlənilən nəticə: "Kitab Axtar" bölməsi tam və işləkdir  

**TC03 - "Kolleksiyanı kəşf et" düyməsi**  
Addımlar:  
1. Siyahıdan kitab seç  
2. Kitab adına kliklə  
3. Detallı səhifənin açılmasını gözlə  
4. Müəllif, janr, təsvir və şəkil düzgün görünür  
* Gözlənilən nəticə: Kitab detalları tam görünür  

---

## 2. Qeydiyyat və Giriş
**TC04 - Yeni istifadəçi qeydiyyatı**  
Addımlar:  
1. "Sign Up" düyməsinə kliklə  
2. Ad, email, parol daxil et  
3. Parol minimum tələblərə cavab verir  
4. "Register" düyməsinə kliklə  
5. Sayta daxil ol  
* Gözlənilən nəticə: Qeydiyyat uğurla tamamlanır  

**TC05 - Email doğrulama**  
Addımlar:  
1. Qeydiyyatdan sonra email yoxla  
2. Doğrulama linkinə kliklə  
3. Hesabın aktivləşdiyini yoxla  
* Gözlənilən nəticə: Hesab aktivləşir  

**TC06 - Login prosesi**  
Addımlar:  
1. Email və parol daxil et  
2. "Login" düyməsinə kliklə  
3. Səhifənin açıldığını yoxla  
* Gözlənilən nəticə: İstifadəçi uğurla daxil olur  

**TC07 - Parol bərpa**  
Addımlar:  
1. "Forgot password" linkinə kliklə  
2. Email daxil et  
3. Reset linkini yoxla  
4. Yeni parol daxil et  
5. Yeni parol ilə login et  
* Gözlənilən nəticə: Parol uğurla dəyişdirilir  

**TC08 - Logout funksiyası**  
Addımlar:  
1. "Logout" düyməsinə kliklə  
2. Sistem çıxışı təsdiqləyir  
3. Əsas səhifəyə yönləndirildiyini yoxla  
* Gözlənilən nəticə: İstifadəçi sistemdən çıxır  

---

## 3. Qruplar Bölməsi
**TC09 - Yeni rəy əlavə etmək**  
Addımlar:  
1. Qrup seç  
2. "Add comment" sahəsinə mətn daxil et  
3. "Submit" düyməsinə kliklə  
4. Rəy siyahıda görünür  
5. Müəllif adı və vaxt düzgün göstərilir  
* Gözlənilən nəticə: Rəy uğurla əlavə olunur  

**TC10 - Media faylı yükləmək**  
Addımlar:  
1. Rəyə şəkil əlavə et  
2. "Submit" düyməsinə kliklə  
3. Şəkilin düzgün göründüyünü yoxla  
4. Şəkili klikləyərək tam ölçüdə açıldığını yoxla  
* Gözlənilən nəticə: Şəkil uğurla yüklənir  

**TC11 - Mövcud rəylərə cavab yazmaq**  
Addımlar:  
1. Mövcud rəyə cavab yaz  
2. "Reply" düyməsinə kliklə  
3. Cavabın düzgün göründüyünü yoxla  
* Gözlənilən nəticə: Cavab uğurla əlavə olunur  

**TC12 - İstifadəçi adı və şəkli**  
Addımlar:  
1. Qrupda paylaşılan rəyə bax  
2. İstifadəçi adı və şəkli düzgün görünür  
* Gözlənilən nəticə: Profil məlumatları düzgün göstərilir  

---

## 4. Compatibility Testing
**TC13 - Chrome test**  
**TC14 - Firefox test**  
**TC15 - Safari test**  
**TC16 - Edge test**  
**TC17 - Mobil versiya test**  
**TC18 - Desktop versiya test**  
Addımlar:  
1. Seçilən mühitdə sayt aç  
2. Əsas səhifəni yoxla  
3. Qeydiyyat və login funksiyalarını test et  
4. Qruplarda rəy əlavə et  
5. UI elementlərinin düzgün göründüyünü təsdiqlə  
* Gözlənilən nəticə: Sayt bütün mühitlərdə problemsiz işləyir  

---

## 5. Performance Testing
**TC19 - Səhifə yüklənmə sürəti**  
Addımlar:  
1. Əsas səhifəni aç  
2. Yüklənmə vaxtını ölç  
3. 3 saniyədən az olduğunu yoxla  
* Gözlənilən nəticə: Səhifə sürətli yüklənir  
 
---

## 6. Security Testing
**TC20 - Yanlış parol**  
Addımlar:  
1. Login səhifəsində yanlış parol daxil et  
2. Sistem xəbərdarlıq göstərir  
* Gözlənilən nəticə: Yanlış giriş bloklanır  

---

## 7. UX Testing
**TC21 - Mobil menyu istifadəsi**  
**TC22 - Font oxunaqlılığı**  
**TC23 - Rəng kontrastı**  
**TC24 - İkonların görünüşü**   
**TC25 - Footer linkləri**  
Addımlar:  
1. Müvafiq UI elementini aç  
2. Görünüş və istifadəsini yoxla  
* Gözlənilən nəticə: UX elementləri düzgün işləyir  
