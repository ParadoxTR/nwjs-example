# ❓ NW.js nedir?

NW.js, HTML, CSS ve JavaScript ile masaüstü uygulamaları oluşturmak için bir frameworktür.

# 🤔 Neden NW.js?

Artıları | Eksileri
------------ | -------------
Çok geniş işletim sistemi desteği (Electron'un yaklaşık iki katı işletim sistemi). | Kötü pazarlama stratejisi.
Linux desteğini önemsiyor. | Küçük ekosistem.
Kaynak kodu korumaya izin veriyor. |
Intel destekli. |
Electron'a göre daha az kaynak kullanımı. |
Windows Installer boyutu 20MB'tan az olabilir. |
Basit. |
Vue, React vs. kullanılabilir. |
Düzgün kullanılırsa Mobil/Web/Masaüstü beraber kullanılabilir. |

> Kaynak: [xpda](https://xpda.net/)

# :clipboard: Örnek projeler ve daha fazlası.

:point_right:  [nw.js-example](/example/)

:point_right:  [nw.js-utilities](https://nwutils.io/)

# :wrench: Nasıl paketlenir?

1. Kendine özel kaynak dosyası oluşturabilirsin ama bu çok zor ve karmaşık aşamadır.
2. Manuel
  
  2.1- Manuel olarak NW.js son sürümünü indirin.
  
  2.2- Proje dosyasınızı nwjs.exe'nin yanına kopyalayınız.
  
  2.3- Proje dosyasınızın adını package.nw olarak değiştiriniz ( devDepencies'ten kullanıcı taraflı indirilmeyecek şeyleri silmeyi unutmayınız ). 
  
  2.4- Ardından NW.exe'yi Uygulamam.exe olarak değiştirin.(ResourceHacker gibi programlar kullanarak icon'u değiştirebilirsiniz.)
  
  2.5- Zip dosyasına ya da türevlerine koyup insanlarla paylaşabilirsiniz ya da installer yaparsınız sizin terchiniz.

3. NW-Builder ya da NW-Builder-Phoenix gibi otomatik yükleyicileri kullanabilirsiniz
