# Dataset Cleaning Summary

## Dataset müqayisəsi

Çirkli və təmiz datasetlərin keyfiyyət müqayisəsi aparıldı.

### Sətir sayı

Çirkli dataset 100 sətirdən ibarət idi. Təmizləmə prosesindən sonra məlumat itkisi olmaması üçün dublikat qeydlər silinmədi və unikal ID-lərlə saxlanıldı.

### Boş dəyərlər

Çirkli datasetdə `created_at` sütununda boş dəyərlər mövcud idi. Boş və etibarsız tarixlər süni məlumatla doldurulmadı, missing value kimi saxlanıldı. Digər sütunlardakı boş dəyərlər uyğun qaydalarla idarə edildi.

### Dublikat məlumatlar

Təmizləmədən əvvəl `application_id` sütununda 13 dənə təkrar dəyər mövcud idi. Bu qeydlər fərqli məlumatlar saxladığı üçün silinmədi. Əvəzinə hər qeyd üçün unikal ID yaradıldı.

### Status formatları

`status` sütununda fərqli yazılış formaları mövcud idi. Bu dəyərlər eyni formata gətirilərək məlumatların standartlaşdırılması təmin edildi.

## Nəticə

Dataset təmizləmə prosesi zamanı tarix formatları standartlaşdırıldı, etibarsız tarixlər və boş tarixlər, duplicate ID problemləri məlumat itkisi olmadan həll edildi və status formatları uyğunlaşdırıldı. Təmizlənmiş dataset analiz üçün hazır vəziyyətə gətirildi.
