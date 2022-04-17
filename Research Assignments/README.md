# Araştırma Ödevleri:

- [Araştırma Projesi 1 - Lateinit](#1)
- [Araştırma Projesi 2 - Tools Namespace](#2)
- [Öğrenci Cevapları](#x)


### <a name="1"></a> Araştırma Projesi 1

- Lateinit neden kullanıyoruz?
- Lateinit kullanımından bahseder misiniz?
- Lateinit için bir örnek kullanım gösterir misiniz ?

Cevaplar:

Kotlin programlama dilinde birden çok değişken ve değişken tanımlama türleri vardır.

Val, sabit değer tanımlamak için kullanılır. Tanımlandıktan sonra tekrar değiştirilemez. 

Var normal değişken tanımlamak için kullanılır. Tanımladıktan sonra dilediğinizde değerini değiştirebilirsiniz. 

Kotlin'deki "lateinit" anahtar sözcüğü, gelecekte başlatılması garanti edilen değişkenleri bildirmek için kullanılır. 
Lateinit sadece var olan değişkenlerde kullanılır. Bu değişkeni herhangi bir yerde, tanımlama yapmadan kullanmaya çalışırsak Kotlin “UninitializedPropertyAccessException” hatası verecektir.

Lateinit kullanmanın temel amacı, derleyiciye bu değişkenin geç başlatılacağını söylemektir ve başlatılana kadar da bellekte yer almaz.


### <a name="2"></a> Araştırma Projesi 2


- Layout dizini içinde xml dosyalarımız için kullandığımız namespace nedir ?
- Neden kullanılmaktadır ?
- Nasıl kullanılmalıdır ?
- Bir adet Tools (tools namespace) attribute kullanımını gösterir misiniz ? 
