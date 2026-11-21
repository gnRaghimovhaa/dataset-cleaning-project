# Dataset Cleaning Summary

## Dataset müqayisəsi

Çirkli və təmiz datasetlərin keyfiyyət müqayisəsi aparıldı.

### Sətir sayı

Çirkli dataset 100 sətirdən ibarət idi. Təmizləmə prosesindən sonra dublikat məlumatların silinməsi nəticəsində dataset 88 sətir oldu.

### Boş dəyərlər

Çirkli datasetdə `created_at` sütununda 0.1 nisbətində boş dəyər mövcud idi. Təmizləmə prosesindən sonra bütün sütunlarda boş dəyər nisbəti 0 oldu.

### Dublikat məlumatlar

Təmizləmədən əvvəl `application_id` sütununda 13 dənə dublikat dəyər mövcud idi. Təmizləmə prosesindən sonra duplicate dəyərlər silindi və unikal ID tələbi təmin edildi.

### Status formatları

`status` sütununda fərqli yazılış formaları mövcud idi. Bu dəyərlər eyni formata gətirilərək məlumatların standartlaşdırılması təmin edildi.

## Nəticə

Dataset təmizləmə prosesi uğurla tamamlandı. Boş dəyərlər, duplicate ID-lər və məlumat formatı problemləri aradan qaldırıldı. Təmizlənmiş dataset analiz üçün hazır vəziyyətə gətirildi.
