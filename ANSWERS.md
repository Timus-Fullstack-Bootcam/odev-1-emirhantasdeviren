# Cevaplar

## 1. JavaScript nedir ve tarihsel gelişiminden bahsedin
   
JavaScript, dinamik web sitesi içeriği oluşturmak ve kontrol etmek için kullanılan high level, interpreted scripting dilidir.
Web sayfasını manuel olarak yeniden yüklemenizi gerektirmeden, tarayıcıda hareket eden, yenilenen veya dinamik şekilde değişen içerikler oluşturmanızı sağlar.

JavaScript 1995 yılında Brendan Eich tarafından Netscape'te mühendis olarak çalışırken yaratılmıştır. Başlangıçta Mocha adı altında geliştirildi, daha sonra LiveScript ve son olarak JavaScript olarak yeniden adlandırıldı.
   
Netscape ve Sun Microsystems Aralık 1995'te JavaScript'i duyurdu.
Hızlı bir şekilde yaygın kullanım kazandı ve farklı tarayıcılar arasında uyumluluğu sağlamak için standartlaştırma için European Computer Manufacturers Association'a (ECMA) devredildi.
Bu, JavaScript'in dayandığı standart olan ECMAScript'in oluşturulmasına yol açtı.
   
JavaScript başlangıcından bu yana önemli ölçüde gelişmiştir.
ECMAScript 5'in (ES5) 2009'da piyasaya sürülmesi standartlaştırılmış JSON desteği ve strict mode'u getirdi.
ECMAScript 2015 (ES6) sınıflar, modüller, template literals ve arrow functions gibi birçok yeni özellik getirmiştir.
   
2009 yılında Node.js tanıtıldı ve JavaScript'in sunucu tarafı programlamaya erişimini genişleterek geliştiricilerin backend hizmetleri oluşturmak için JavaScript kullanmasına olanak tanıdı.
   
Dilin popülerliği, karmaşık uygulamalar geliştirmeyi kolaylaştıran çok sayıda ortam ve kütüphaneyi (Angular, React ve Vue.js gibi) ortaya çıkarmıştır.

## 2. Java ile javascript arasındaki fark nedir

   İkisinin isminde Java geçse de aslında aralarında herhangi bir ilişki, yakınlık bulunmamaktadır. JavaScript'in çıktığı dönemde Java popülerliğini kazanmaya başlamıştı. Bu nedenle tamamen pazarlama amaçlı
   adının içinde Java geçsin insanların ilgisini çeksin diye JavaSript adına geçilmiş.

- Java compiled (derlenen) bir dildir, JavaScript ise interpreted (yorumlanan) bir dilrdi. Yani bir Java kodu derleyici ile JVM (Java Virtual Machine) üzerinde çalışacak bytecode'lara dönüştürülür.
  JavaScript ise satır satır okunarak motor tarafından çalıştırılır, buna ayrıca JIT (just in time) execution da denir.
- Java statik data tipli, nesne bazlı bir dildir, JavaScript ise dinamik data tipli, prototip bazlı bir dildir.
- Java JVM'nin çalışabildiği herhangi bir aygıtta çalışabilen bir dildir. Bilgisayar uygulamaları, Android uygulamaları ve backend servisleri yazılabilir.
  JavaScript ise öncelikli olarak web uygulamarı için kullanılır ayrıca Electron ile bilgisayar uyugulamaları da yazılabilir (örn. VS Code)

## 3.Javascript teki veri tipleri nelerdir açıklayınız

JavaScript temelinde iki farklı veri tipi barındırır.

1. İlkel Tipler
   1. string
   3. number
   4. bigint
   5. boolean
   6. undefined
   7. symbol
   8. null
2. Obje Tipi

#### İlkel Tipler
##### string
`string` bir yazıyı temsil eden ardışık karakterlerdir.
##### number
`number` 64 bit double-precision floating point format (IEE 754) standardına uygun sayısal veriyi temsil eden bir tiptir.
##### bigint
`bigint` 8 bit ile 64 bit arasında değişebilen tam sayıları temsil eden bir tiptir.
##### boolean
`boolean`, `true` veya `false` değerine sahip olabilen mantıksal bir veridir.
##### undefined
`undefined` bir değer atanmayan değişkene verilen varsayılan değerdir.
##### symbol
`symbol` eşsiz bir değer olmasını garanti veren bir tiptir.
##### null
`null` var olmayan bir objeyi veya adresi temsil eden bir tiptir.

#### Obje Tipi
Obje, başka bir obje veya ilkel tiplerden oluşan koleksiyon tipidir.

## 4. null ile undefined arasıdaki fark nedir açıklayınız

`null` var olmayan bir objeyi veya adresi göstermek için kullanılır. Yani yokluk durumunu belirtir. `undefined` ise hiçbir değer verilmemiş (`null` dahil) değişkene atınan otomatik değerdir. Yani belirsizlik durumunu belirtir.

## 5. NaN nedir açıklayınız

Not-A-Number drumunu temsil eden `number` tipinde bir değerdir.
Başarısız veri tipi dönüştürmelerini, gerçek sayı değeri vermeyen matametiksel ifadeleri, matametikte belirsiz formu örn. 0/0 gibi durumları temsil eder.

## 6. Javascript’te yorum satırı eklemenin kaç farklı yolu vardır

İki farklı yol vardır.

1. Tek satır
   ```js
   // console.log("Bu bir yorum satırı olmuştur.");
   ```
2. Çoklu satır
   ```js
   /*
   console.log("Bir veya birden fazla satırı");
   console.log("yorum yapmak için kullanılır.);
   */
   ```

## 7. Global değişken ne demektir açıklayınız

Bir programın herhangi bir parçasınnın erişebildiği değişkenlere *global değişken* denir.

## 8. Javascript’te this anahtar kelimesi nedir açıklayınız

`this` anahtar kelimesi bir objenin referansı için kullanılır. Fonksiyonlardaki kullanımı fonksiyonun çağrılma şekline göre değişir. Sınıflarda ise örnek sınıfın referansıdır.

## 9. `==` ile `===` farkını örnekler ile açıklayınız

İki değişkenin eşitliğine bakılırken, `==` iki verinin aynı tipte olmasını sağlayacak şekilde veri dönüştürmesi yapıp daha sonra eşitliği kontrol eder. `===` ise veri dönüştürmesi yapmadan eşitliği kontrol eder.

## 10. let var const farkını tablo yapınız

| Özellik                 | var              | let              | const            |
|-------------------------|------------------|------------------|------------------|
| Kapsam                  | Fonksiyon        | Blok             | Blok             |
| Hoisting (Yukarı Çekme) | Evet             | Hayır            | Hayır            |
| Tekrar Değişken Tanımı  | Yapılabilir      | Yapılamaz        | Yapılamaz        |
| Yeni Değer Atanması     | Yapılabilir      | Yapılabilir      | Yapılamaz        |
| Başlangıç Değeri        | İsteğe Bağlı     | İsteğe Bağlı     | Zorunlu          |
| Global                  | Evet (global)    | Hayır            | Hayır            |

