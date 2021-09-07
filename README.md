1)film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.<br><code>
select distinct replacement_cost from film</code><br>
2)film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?<br><code>
select count(distinct replacement_cost) from film</code><br>
3)film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?<br><code>
select count(*) from film
where title like 'T%' AND rating='G'</code><br>
4)country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?<br><code>
select COUNT(*) from country
where country like '%';</code><br>
5)city tablosundaki şehir isimlerinin kaçtanesi 'R' veya r karakteri ile biter?<br><code>
select COUNT(*) from city
where city ilike '%r';

                                   

