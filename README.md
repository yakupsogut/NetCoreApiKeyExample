NetCoreApiKeyExample: .NET Core API Anahtarları Kullanımı Örneği
================================================================

Bu proje, .NET Core API projelerinde API anahtarlarının nasıl kullanılacağını ve güvenli bir şekilde yönetileceğini anlamak için örnekler içermektedir. Ayrıca .NET Core'un en iyi uygulama yönergelerine uygun olarak geliştirilmiş kod parçaları içermektedir.

Proje Açıklaması
----------------

Bu örnek proje, .NET Core kullanarak basit bir API uygulamasını içermektedir. Proje, API anahtarlarını güvenli bir şekilde saklama, kullanma ve yönetme konularında pratik örnekler sunmaktadır.

Özellikler
----------

* API anahtarlarını nasıl güvenli bir şekilde saklayacağınızı öğrenin.
* API anahtarlarını istemcilere nasıl dağıtacağınızı anlayın.
* Projenizi .NET Core en iyi uygulama yönergelerine uygun olarak nasıl geliştireceğinizi görün.

Nasıl Kullanılır
----------------

1.  Bu depoyu klonlayın:
    
    ```sh    
    git clone https://github.com/KullaniciAdi/NetCoreApiKeyExample.git
    
2.  Proje dizinine gidin:
    
     ```sh     
    cd NetCoreApiKeyExample
    
3.  `appsettings.json` dosyasında yer alan `ApiKey` bölümüne API anahtarlarınızı ekleyin:
    
     ```sh     
    "Authentication": {
        "ApiKey": "your_api_key_here"
    }
  
Katkı Sağlama
-------------

Katkılarınızı memnuniyetle karşılıyoruz! Eğer projeye katkıda bulunmak isterseniz:

1.  Bu repo forklayın.
2.  Yeni bir branch oluşturun: `git checkout -b yeni-ozellik`
3.  Değişikliklerinizi commit edin: `git commit -m 'Yeni özellik: Açıklama'`
4.  Branch'inizi pushlayın: `git push origin yeni-ozellik`
5.  Bir Pull Request (PR) oluşturun.
