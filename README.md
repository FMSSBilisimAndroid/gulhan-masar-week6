# gulhan-masar-week6
Coroutine Scope and Endless Loop

<img width="1440" alt="Screen Shot 2022-10-02 at 12 45 29 AM" src="https://user-images.githubusercontent.com/109763090/193430090-8dc04dcc-a259-49de-a357-8fcfa26b5d0b.png">

## Dongu kilitlenir.
## Sonsuz döngü oldugundan Coroutine Scope icindeki doNetworkCall fonsiyonu hicbir sey döndürmez.


## Coroutine Scope 

 * Kotlin Coroutines, asenkron olarak çalışan kodu basitleştirmek için Android'de kullanabileceğimiz bir asenkron tasarım modelidir. Android'de, Main Thread’i  bloklayabilecek ve uygulamamızın yanıt vermemesine neden olabilecek uzun süreli işlemleri yönetmemize yardımcı olur.


## Suspend Fonksiyonlar

* Suspend fonksiyonlar durdurulabilir ve yeniden başlatılabilir. Uzun süren bir işlemi yürütüp, thread bloklaması olmadan tamamlanmasını sağlar. Fonksiyon oluştururken ‘fun’ kelimesinin önüne gelen ‘suspend’ kelimesiyle oluşturulur ve bir coroutine içerisinde çalışmak zorundadır
