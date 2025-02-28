In this project, we will scrape a quote and details of the author from this site http//quotes.toscrape.com using python framework called BeautifulSoup and develop a guessing game using different data structures and algorithm. 
The user will be given 4 chances to guess the author of a famous quote, In every chance the user will be provided with a hint which can be the author’s birth date, first name’s first letter, second name’s first letter, etc. On successfully guessing the author, a message is printed and if the user fails to guess the answer even after all the 4 chances then again a message is printed along with the answer.
Approach:
1)Import module
  -requests help us grab the page, when the response is received it is stored in the form of a string
  -bs4 library is used to create beasutifulSoup object.
  -csv library helps reading and writing CSV files using python
  -sleep function from time module helps add delay in the execution of the program.
  -choice function from random module returns a random element.
2)Create a list to store values scraped
3)Scrape the details from this link: http//quotes.toscrape.com
4)Extract data
5)Game logic:
Return random items from the dictionary created
Set number of guesses
Write message for success and failure
Keep giving hints until either number of chances reach zero or the user gets it right.
----------------------------------------------------------------------------------------
Time Complexity: 
The time complexity of this code is O(N) because the while loop is iterating over quotes list N times.

Space Complexity:
The space complexity of this code is O(N) because the all_quotes list is storing N number of elements.

******************************************************************************************************************************************************************************

Bu projede, BeautifulSoup adlı Python frame'ini kullanarak http://quotes.toscrape.com sitesinden bir alıntıyı ve yazarına ait bilgileri alacağız. Daha sonra, farklı veri yapıları ve algoritmalar kullanarak bir tahmin oyunu geliştireceğiz.
Kullanıcıya ünlü bir alıntının yazarı hakkında tahminde bulunması için 4 hak verilecektir. Her tahmin hakkından sonra kullanıcıya bir ipucu sağlanacaktır. Bu ipuçları yazarın doğum tarihi, adının ilk harfi, soyadının ilk harfi gibi bilgiler olabilir. Kullanıcı doğru cevabı tahmin ederse bir başarı mesajı görüntülenir. Ancak, 4 hakkını da kullanmasına rağmen doğru tahminde bulunamazsa, bir başarısızlık mesajı gösterilir ve doğru cevap açıklanır.
Yaklaşım:
1)Modülleri içe aktar
  -requests: Web sayfasını almak için kullanılır, yanıt metin olarak saklanır.
  -bs4: BeautifulSoup nesnesi oluşturarak HTML içeriğini ayrıştırmak için kullanılır.
  -csv: CSV dosyalarını okumak ve yazmak için kullanılır.
  -time.sleep: Programın çalışmasını belirli süre duraklatmak için kullanılır.
  -random.choice: Bir listedeki rastgele bir öğeyi döndürmek için kullanılır.
2)Alınan verileri saklamak için bir liste oluştur
3)Belirtilen bağlantıdan (http://quotes.toscrape.com) verileri kazı
4)Verileri ayıkla
5)Oyun mantığı:
Rastgele bir alıntı seç.
Tahmin hakkını belirle (4 kez).
Başarı ve başarısızlık mesajlarını yaz.
Kullanıcı doğru tahminde bulunana veya tahmin hakkı tükenene kadar ipuçları sun.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Zaman Karmaşıklığı
Bu kodun zaman karmaşıklığı O(N)'dir, çünkü while döngüsü N kez quotes listesi üzerinde yinelenmektedir.

Uzay Karmaşıklığı
Bu kodun yer karmaşıklığı O(N)'dir, çünkü all_quotes listesi N öğeyi saklamaktadır.
