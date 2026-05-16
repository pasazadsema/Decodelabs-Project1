# BUSINESS INSIGHTS
- Yeni landing page 11.88% conversion göstərir, köhnə page isə 12.04% göstərir, istifadəçilər yeni dizaynda qərar verməkdə bir az çətinlik çəkir və CTA daha az diqqət çəkir, bu da conversion-un azalmasına səbəb olur, CTA button-lar daha görünən edilməli, səhifə daha sadə və istifadəçi üçün rahat hala gətirilməlidir
- 1 milyon istifadəçidə təxminən 1600 conversion itkisi yaranır, kiçik faiz fərqi böyük istifadəçi sayında real biznes itkisinə çevrilir və bu uzun müddətdə gəlirə təsir edir, A/B testdə hər bir element ayrıca yoxlanmalı, başlıq, button və dizayn hissələri ayrı-ayrılıqda optimallaşdırılmalıdır
- Günün saatlarına görə conversion stabil qalır və ciddi fərq yoxdur, istifadəçi davranışı günün vaxtından çox saytın dizaynı və ümumi təcrübəsindən asılıdır, buna görə fokus vaxt analizi yox, daha çox UX və istifadəçi axını (funnel) optimizasiyasına yönəlməlidir
- Qruplar balanslıdır (təxminən 147k vs 147k), bu nəticənin düzgün və etibarlı olduğunu göstərir, random seçim düzgün işləyib və nəticəyə ciddi təsir edən bias yoxdur, gələcək testlərdə də istifadəçilərin qruplara düzgün bölünməsi qorunmalıdır
- 3894 misassignment (səhv page və group uyğunluğu) tapılıb, yəni bəzi istifadəçilər yanlış səhifəyə yönləndirilib və bu nəticəyə az da olsa təsir edə bilər, sistemdə yoxlama mexanizmi əlavə edilməli, routing və test təyinetmə prosesi daha düzgün qurulmalıdır
# ANALIZ
- Dataset ölçüsü təxminən 294,478 istifadəçi üzərində qurulub və control ilə treatment qrupları demək olar ki, balanslıdır (~147k vs ~147k)
- Data cleaning zamanı 3894 misassignment aşkarlandı və silindi, bu ümumi datanın təxminən ~1.3% hissəsidir
- Control conversion rate: 12.04%
- Treatment conversion rate: 11.88%
- Günlük conversion rate analizində stabil trend müşahidə olunur
- Günlər arasında ciddi fərq yoxdur (variation çox aşağıdır)
- Yeni landing page performansı köhnə page-dən aşağıdır
- Fərq kiçik görünür (0.16%), amma böyük user basede ciddi itki yaradır
- Data göstərir ki dəyişiklik conversionu artırmayıb, azaldıb
- yeni variant hazırda daha zəif performans göstərir