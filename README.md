# Sehiyye-Data-Analizi
Sehiyye datasinin R ile analizi


# Səhiyyə Məlumatlarının Analizi

## Layihənin Məqsədi
Bu layihədə səhiyyə məlumatları üzərində deskriptiv analiz, korrelyasiya analizi, anomaliya aşkarlanması, proqnozlaşdırma və hipotez testləri həyata keçirilmişdir.

---

## Deskriptiv Analiz 

![Deskriptiv Analiz](screenshots/yash.png)

![Yaş](screenshots/yashqrupu.png)

![Yaş qrupu  və Cins](screenshots/yashqrupu&cins.png)

Bu hissədə pasiyentlərin yaş strukturu analiz olunub. Nəticələr göstərir ki, sistemdə ən böyük pasiyent qrupu 41–65 yaş aralığıdır və ümumi datasetin 36.7%-ni təşkil edir.

Bu onu göstərir ki, tibbi müraciətlərin əsas hissəsi orta yaş qrupunda cəmləşir. Yəni insanlar yaş artdıqca daha çox tibbi nəzarətə və müayinəyə ehtiyac duyurlar.

19–40 yaş qrupu da yüksək paya sahibdir. Bu yaşlarda müraciətlər daha çox ümumi müayinələr və gündəlik sağlamlıq xidmətləri ilə əlaqəli ola bilər.

65 yaşdan yuxarı pasiyentlərin payının yüksək olması isə vacib göstəricidir. Çünki bu yaş qrupunda davamlı nəzarət və müalicə ehtiyacı daha çox olur.

Qrafikdə 0 yaşlı pasiyentlərin görünməsinin əsas səbəbi isə datasetdə bəzi körpələrin 1 yaşdan kiçik olması və 9 pasiyentin doğulduğu gün vəfat etməsi ilə əlaqəlidir. Yəni burada 0 yaş göstəricisi texniki olaraq yeni doğulmuş pasiyentləri ifadə edir.

Ümumilikdə analiz göstərir ki, yaş faktoru tibbi müraciət intensivliyinə birbaşa təsir edən əsas göstəricilərdən biridir.

Minimum yaş göstəricisinin 0 olması datasetdə doğum və ölüm tarixinin eyni günə təsadüf etdiyi, həmçinin 1 yaşdan kiçik pasiyentlərin mövcudluğu ilə əlaqədardır.





![Yaş qrupu üzrə sağ qalan/vəfat edən](screenshots/olumeaparanxestelik.png)

Minimum 500 müraciəti olan diaqnozlar arasında ən yüksək ölüm nisbətinə malik xəstəliklər göstərilmişdir. Nəticələrə əsasən, ağciyər xərçənginin irəliləmiş mərhələləri və şübhəli ağciyər xərçəngi hallarında ölüm riski ən yüksək səviyyədədir. Alzheimer xəstəliyi də yüksək ölüm göstəricisi ilə diqqət çəkir. Ümumilikdə analiz göstərir ki, ağır və xroniki xəstəliklər ölüm ehtimalını əhəmiyyətli dərəcədə artırır.

![Yaş qrupu üzrə sağ qalan/vəfat edən](screenshots/yash&olum&sag.png)

Bu hissədə pasiyentlərin ailə vəziyyəti və sağ qalma göstəriciləri analiz olunub.

Ümumi nəticələrə baxdıqda pasiyentlərin 75%-dən çoxunun sağ qaldığı, təxminən 25%-nin isə vəfat etdiyi görünür.

Yaş qrupları üzrə müqayisə etdikdə isə çox vacib bir tendensiya müşahidə olunur. Yaş artdıqca vəfat edən pasiyentlərin nisbəti də artır. Məsələn:

• 0–18 yaş qrupunda ölüm göstəricisi təxminən 8%-dir,

• 65 yaşdan yuxarı qrupda isə bu göstərici təxminən 47%-ə qədər yüksəlir.

Bu nəticə yaş faktorunun ölüm riski ilə birbaşa əlaqəli olduğunu göstərir.

![Yaş qrupu üzrə top diaqnoz ](screenshots/yashqrupudiaqnoz.png)

Yaş qrupları üzrə ən çox rast gəlinən üç diaqnoz təhlil edilmişdir. Nəticələr göstərir ki, viral sinusit bütün yaş qruplarında ən çox müşahidə olunan diaqnozlar sırasında yer alır və geniş yayılmış sağlamlıq problemi kimi seçilir. 19–40 yaş qrupunda normal hamiləlik müraciət sayı baxımından digər diaqnozları əhəmiyyətli dərəcədə üstələyir. 41 yaşdan yuxarı qruplarda isə yuxarı tənəffüs yolları xəstəlikləri üstünlük təşkil edir. Təhlil göstərir ki, diaqnozların paylanması yaş qrupları üzrə fərqlənir və tibbi xidmətlərə olan tələbatın strukturu yaş amilindən əhəmiyyətli dərəcədə asılıdır.





![Müraciət sayı](screenshots/encoxmuraciet.png)

![Diaqnoz](screenshots/encoxdiaqnoz.png)

![Cinslər üzrə Diaqnoz](screenshots/cinsuzrediaqnoz.png)

![Diaqnoz üzrə ölüm ](screenshots/diaqnozuzreolum.png)


![Klinik göstəricilər](screenshots/12klinikgosterici.png)


![BMI ](screenshots/bmiuzrepaylanma.png)

---

### Korrelyasiya Analizi

![Korrelyasiya](screenshots/korelyasiya.png)

Dəyişənlər arasındakı əlaqələr araşdırılmışdır.

---

## Anomaliya Analizi

![Anomaliya](screenshots/anomaliya.png)

Normadan kənar müşahidələr müəyyən edilmişdir.

---


## Hipotez Testləri

![Hipotez](screenshots/Hipotez.png)

Hipotez testlərinin nəticələri təqdim edilmişdir.

![Z test](screenshots/Ztest.png)

![Z test 2](screenshots/Ztest (2).png)

![Z test 3](screenshots/Ztest (3).png)

Statistik əhəmiyyətlilik yoxlanılmışdır.

---

## Nəticələr və Tövsiyələr

Əldə olunan nəticələr səhiyyə göstəricilərinin daha yaxşı başa düşülməsinə və risk faktorlarının müəyyən edilməsinə imkan verir.
