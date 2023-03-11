# day1
i am learning software. this is what learned on the first day
//Tek satırlık yorum/açıklama (comment) oluşturuldu.
/*
 * Çok satırlı yorum/açıklama oluşturuldu.
 * Ctrl + S: Bulunduğumuz dosyayı kaydeder.
 * Ctrl + Shift + S: Açık bütün dosyaları kaydeder.
 * Ctrl + K,C: Bulunduğunuz satırı yorum satırına alır.
 * Ctrl + K,U: Bulunduğunuz satırı yorum satırından çıkarır.
 * Ctrl + K,D: Kod düzenin formatlar, parantezleri hizalar.
 * Ctrl + E,W: Tüm içeriği ekrana sığdırma veya geri alma işlemini yapar.
 * Ctrl + D: Bulunduğu satırı kopyalar.
 */

//namespace: Program dosyalarını (.cs) bir isim altında toplamak için kullanılır. Bu ismi alan dosyalar birbirini direk görebilir. İçerisine yazılan nesnelerin adres belirteci olarak kullanılır. Script (oyun vb) programcılığında dosyalar arası iletişim olmadığından kullanıldığı görünmez.
namespace Ders00
{
    //Nesne (object): En genel program parçalarından en küçüğüne kadar temelinde object adı verilen yapı (struct) bulunmaktadır. Ortak olarak her nesnede bu yapının özelliklerini görürüz.

    /* Nesne Türleri:
     * class (sınıf): Classification (sınıflandırma) olarak kullanılır. Özellikler ve işlevler barıdırarak veri değişikliğine bağımlı şekillenen nesneler oluşturur. En sık kullanılan nesne türüdür.
     * enum (enumurate): Numaralandırma nesnesidir, sabit içeriklere numara verir. (Örn: Haftanın günleri, yılın ayları)
     * interface (arabirim): Soyut bir nesnedir, sınıflar için manifesto görevi görür. Sııfları özelliklerini kısıtlamak için kullanılır.
     */

    /// <summary>
    /// Program.cs genel anlamda C# projelerinin başlangıç noktasıdır. Bu özet yazı bunu belirtmek için yazılmıştır. Main() metodunu kullanarak temel kodlarınıza başlayabilirsiniz.
    /// Bu yapı nesnelere ve onların içrisindeki özelliklere eklenebilir.
    /// </summary>
    internal class Program
    {
        /// <summary>
        /// Bu metot başlangıç noktasını belli eder, içersine akışınızı yazarak uygulamanıza başlayabilirsiniz.
        /// </summary>
        /// <param name="args">Bu alan dışarıdan gelecek bilgi akışı içindir. Parametre alanı olarak bilinir.</param>
        static void Main(string[] args)
        {
        }
    }
    /// <summary>
    /// 
    /// </summary>
    enum Gunler { Pazar, Pazartesi, Sali, Carsamba, Persembe, Cuma, Cumartesi }
}
