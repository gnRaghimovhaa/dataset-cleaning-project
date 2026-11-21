# Data Dictionary
| Sutun adi | Tip | Izahi | Numune |
|---|---|---|---|
| application_id | Integer | Müraciətin unikal identifikasiya nömrəsi | 1 |
| created_at | Date | Müraciətin qeydə alınma tarixi | 2025-06-01 |
| status | String | Müraciətin cari vəziyyəti ilə bağlı məlumat | PENDING |
| score | Integer | Müsahibədən sonra qiymətləndirmənin 100 ballıq şkalada dəyəri | 98 |




## Status üçün icazəli dəyərlər

- PENDING
- ACCEPTED
- REJECTED


## Təmizləmə qaydaları

- Status dəyərləri vahid böyük hərf formatına (`UPPERCASE`) gətirildi.
- Təkrarlanan application_id dəyərləri yoxlanıldı və unikal saxlanıldı.
- Tarix sütununda format fərqləri `YYYY-MM-DD` formasına uyğunlaşdırıldı.
- Mövcud olmayan tarixlər (məsələn, 2026-02-30) aşkar edilərək boş dəyər kimi saxlanıldı.
- Boş dəyərlər təhlil edildi və səbəbi README sənədində qeyd olundu.
