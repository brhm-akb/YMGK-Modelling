KAPLAN-YORKE HARİTASI

Kaplan-Yorke haritası, karmaşık sistemlerin kaotik davranışlarını görselleştirmek için kullanılan bir grafiksel araçtır. İlk olarak Edward Lorenz tarafından geliştirilen bir yöntem olan Kaplan-Yorke haritası, kaos teorisi ve dinamik sistemler teorisinde önemli bir yere sahiptir. Bu harita, bir sistemdeki kaotik davranışın ne zaman ortaya çıktığını ve bu davranışın şiddetini belirlemeye yardımcı olur.

Kaplan-Yorke haritası oluşturmak için, sistemdeki davranışı analiz etmek için bir parametre seçilir. Bu parametre, sistemin kaotik olup olmadığını ve kaosun ne zaman ortaya çıktığını belirlemek için önemlidir. Bu parametre genellikle sistemdeki belirli bir özelliği kontrol eden bir parametre olabilir. 

![image](https://github.com/brhm-akb/YMGK-Modelling/assets/65442206/5670d9af-1afa-4519-8d02-b1ffd0b8a993)

burada mod, gerçek argümanlara sahip modulo operatörüdür . Harita yalnızca bir sabit α'ya bağlıdır.

HESAPLAMA YÖNTEMİ

Yuvarlama hatası nedeniyle, modulo operatörünün ardışık uygulamaları, bilgisayarda kayan nokta işlemi olarak uygulandığında yaklaşık on veya yirmi yinelemeden sonra sıfır verecektir. Aşağıdaki eşdeğer algoritmayı uygulamak daha iyidir:

![image](https://github.com/brhm-akb/YMGK-Modelling/assets/65442206/eb600568-a698-4261-8d96-36d498373264)

Kısa sayıda yinelemeden sonra modulo operatörünün veriminin sıfır olmasını önlemenin başka bir yolu da şudur:

![image](https://github.com/brhm-akb/YMGK-Modelling/assets/65442206/9a914f24-18bc-4cd4-8c2b-e332bf1c0ae4)

bu, daha birçok yinelemeden sonra da olsa sonuçta sıfıra dönecektir.

