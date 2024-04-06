Complex squaring map

Matematikte , ikinci dereceden bir polinom eşlemesi olan karmaşık kare alma haritası , dinamik sistemlerdeki kaosun basit ve erişilebilir bir gösterimidir . Aşağıdaki adımları gerçekleştirerek oluşturulabilir:


1)Birim çember üzerinde bağımsız değişkeni ( açı) π'nin rasyonel katı olmayan herhangi bir karmaşık sayıyı seçin 

2)Bu sayının tekrar tekrar karesini alın.


Bu tekrarlama (yineleme), bağımsız değişkenleriyle tek başına tanımlanabilecek bir karmaşık sayılar dizisi üretir. Yukarıda (1)'i karşılayan herhangi bir başlangıç ​​açısı seçimi, adımların basitliğine ters düşen son derece karmaşık bir açı dizisi üretecektir. Dizinin kaotik olacağı , yani ayrıntılı başlangıç ​​açısı seçimine duyarlı olduğu gösterilebilir.

Yinelemenin kaotik olmasının gayri resmi nedeni, açının her yinelemede iki katına çıkması ve açı büyüdükçe iki katına çıkmanın çok hızlı büyümesidir, ancak 2π'nin ( radyan ) katları kadar farklılık gösteren açılar aynıdır. Dolayısıyla açı 2π'yi aştığında 2π'ye bölünerek kalana sarılmalıdır . Bu nedenle açı ikili dönüşüme (2 x mod 1 haritası olarak da bilinir ) göre dönüştürülür . Başlangıç ​​değeri z0 π'nin rasyonel katı olmayacak şekilde seçildiğinden, z n'nin ileri yörüngesi kendini tekrarlayamaz ve periyodik hale gelemez.

Daha resmi olarak yineleme şu şekilde yazılabilir:

![image](https://github.com/brhm-akb/YMGK-Modelling/assets/65442206/a97166ea-3fe8-43c6-a1f9-238b1ec87c85)

zn ukarıdaki adımların yinelenmesiyle elde edilen karmaşık sayılar dizisidir ve z0 ilk başlangıç ​​numarasını temsil eder. Bu yinelemeyi aynen çözebiliriz:

![image](https://github.com/brhm-akb/YMGK-Modelling/assets/65442206/57d954b2-5f80-4e5e-b781-87cdf81af75d)

θ açısıyla başlayarak başlangıç ​​terimini şu şekilde yazabiliriz:

z0=exp(iθ)

böylece

zn=exp(i2^nθ)

Bu, açının art arda iki katına çıkmasını netleştirir. (zn=cos(2^nθ) + isin(2^nθ) Euler formülüne göre)
