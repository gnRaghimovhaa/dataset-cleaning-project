# Dataset Təmizləmə Layihəsi

## Layihənin məqsədi

Bu layihənin məqsədi təcrübə proqramına müraciət edən namizədlərin məlumatlarını daha keyfiyyətli və istifadəyə yararlı etməkdir. Bu layihədə problemlər aşkar olunacaq və dataset təmizlənəcək, yəni datasetdə olan təkrar, dublikat, səhv format, boş dəyərlər kimi porblemlər aradan qaldırılıb clean-dataset.csv faylı yaradılacaq.

# Datasetdəki Problemlər

-yanlış formatda yaxud boş tarix məlumatları
-təkrarlanan İD-lər
-dublikat dəyərlər
-fərqli yazılışda sütun dəyərləri
-uyğunsuz məlumat formatları

# İstifadə olunan alətlər

-Jupyter Notebook
-Python
-Pandas
-Github
-Visual Studio

 ## Təmizləmə addımları

- `created_at` sütunundakı boş dəyərlər dataset sintetik olduğu üçün təsadüfi tarixlərlə dolduruldu.
- `application_id` sütunundakı dublikat dəyərlər unikal ID tələbini qorumaq üçün təmizləndi.
- Boş qalan `application_id` dəyərləri yeni unikal ID ilə dolduruldu.
- `status` sütunundakı fərqli yazılış formaları eyni formata gətirildi.

## Fayllar

- `cleaning_dataset.ipynb` - Dataset təmizləmə prosesinin kodlarını və analiz nəticələri olan notebook.
- `Data_Dictionary.md` - Dataset sütunlarının adı, tipi və izahını göstərir.
- `raw.csv` - İlkin xam dataset faylı.
- `dirty.csv` - Problemləri (boş dəyərlər, duplicate-lər və format uyğunsuzluqları) olan çirkli dataset.
- `clean.csv` - Təmizlənmiş və analiz üçün hazır dataset.
- `clean25.csv` - 25 sətirlik praktik nümunənin təmizlənmiş versiyası.

> QEYD : Dataset sütunları haqqında ətraflı məlumat üçün `data_dictionary.md` faylına baxa bilərsiniz.

## Nəticə

Sonda isə təmizləmə prosesi tamamlandı və bütün problemlər aradan qaldırıldı.Təmizlənmiş `clean.csv` faylı analiz üçün hazır vəziyyətə gətirildi.

## Öyrənilənlər və məhdudiyyətlər
Bu layihə zamanı dataset təmizləmə prosesinin əsas mərhələləri, boş dəyərlərin aşkarlanması, dublikat məlumatların aradan qaldırılması və məlumat formatlarının standartlaşdırılması öyrənildi. Həmçinin təmizləmə prosesindən əvvəl və sonra dataset keyfiyyətinin müqayisə edilməsi praktiki olaraq tətbiq edildi. Dataset sintetik olduğu üçün real müraciət məlumatlarını tam əks etdirmir və nəticələr real biznes məlumatlarına tam uyğun olmaya bilər.
