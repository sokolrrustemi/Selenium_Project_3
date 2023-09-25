# Proje Adı: TestingProject_3 > techno.study & e-junkie.com
https://techno.study/tr/  &  https://e-junkie.com/wiki/demo/  environment’larının bazı fonksiyonlarının test edilmesi.

## Proje Açıklaması:
Bu proje, Techno Study'nin "/tr" alanının test edilmesi sürecine odaklanırken, aynı zamanda daha önce hotfix edilmiş olan E-Junkie environment'ının da bazı fonksiyonlarının test edilmesini içerir. İki ana bölümden oluşur: Birinci bölümde, Techno Study web sitesinin testi ve kullanılabilirliğinin artırılması yer alırken, ikinci bölümde ise E-Junkie environment'ının işlevselliğinin kontrol edilmesi hedeflenir.

### Proje Dosyaları
[Techno Study User Story & Test Case](https://docs.google.com/spreadsheets/d/1bj8hUQpKCPcmBBXvw10sdSty96mn-lTe/edit?usp=drive_link&ouid=108357966207576195639&rtpof=true&sd=true)

[E-Junkie User Story & Test Cases](https://docs.google.com/spreadsheets/d/1kX-Inssewg-ZS_opwR4XcXJ1GYjoaHJ9/edit?usp=drive_link&ouid=108357966207576195639&rtpof=true&sd=true)

[Screenshots](https://drive.google.com/drive/folders/1qRt0JuKU38YVHPPfabLohDIbW4kgtpGz?usp=drive_link)

## Başlarken

### Gereksinimler

Bu proje, aşağıdaki sistemler ve gereksinimler ile test edilmiştir:

- **İşletim Sistemleri:**
    - Windows 10, 11
    - macOS Big Sur
    - Ubuntu 20.04 LTS   
<br>
- **Entegre Geliştirme Ortamları (IDE):**
    - IntelliJ IDEA 2021.2
    - Eclipse 2021-06   
<br>
- **Programlama Dili:**
    - Java 8SE, 11, 20   
<br>
- **Bağımlılıklar:**
    - Selenium WebDriver 4.11.0
    - TestNG 6.14.3, 7.4.0   

### Kurulum
Proje kurulumu için aşağıdaki adımları takip edebilirsiniz:

0. IntelliJ IDEA Community Edition'ı [buradan](https://www.jetbrains.com/idea/download/) indirin ve kurun.
1. Java 8SE (JDK 1.8)'i [buradan](https://www.oracle.com/java/technologies/downloads/#java8-windows) indirin ve kurun.
   (JDK 20 de, [buradan](https://www.oracle.com/java/technologies/downloads/#java20) indirilebilir.)
2. [IntelliJ'de Maven projesi açma](https://www.jetbrains.com/help/idea/maven-support.html#create_new_maven_project) 
3. [IntelliJ'de TestNG Kullanımı](https://www.jetbrains.com/help/idea/testng.html)
4. Proje bağımlılıklarını yönetmek için Maven kullanıyorsanız, `pom.xml` dosyasını güncelleyerek gerekli bağımlılıkları ekleyin:

   ```xml
   <dependencies>
       <!-- Selenium WebDriver -->
       <dependency>
           <groupId>org.seleniumhq.selenium</groupId>
           <artifactId>selenium-java</artifactId>
           <version>4.11.0</version>
       </dependency>
   
       <!-- TestNG -->
       <dependency>
           <groupId>org.testng</groupId>
           <artifactId>testng</artifactId>
           <version>7.4.0</version>
       </dependency>

    <!-- SLF4J (Simple Logging Facade for Java) -->
    <dependency>
        <groupId>org.slf4j</groupId>
        <artifactId>slf4j-nop</artifactId>
        <version>1.7.36</version>
    </dependency>

    <!-- Commons IO -->
    <dependency>
        <groupId>commons-io</groupId>
        <artifactId>commons-io</artifactId>
        <version>2.11.0</version>
    </dependency>
    
    <!-- Diğer bağımlılıklarınız -->
   
   </dependencies>

### Programı Çalıştırma

  Bu projeyi klonlamak ve IntelliJ IDEA kullanarak açmak için aşağıdaki adımları takip edebilirsiniz:

1. Proje deposunu bilgisayarınıza klonlayın:

   ```bash
   git clone https://github.com/ebuzer33/Selenium_Project_3.git

Bu komut, projenin yerel bir kopyasını oluşturacaktır.

2. IntelliJ IDEA'yi açın.

3. IntelliJ IDEA'de "File" menüsünden "Open" seçeneğine tıklayın ve projenizin klonladığı dizini seçin.

5. Proje içindeki ana test sınıflarını bulun ve bu sınıfı (ya da metodları) çalıştırın (`@test` anotasyonunun olduğu satırlar). 
Projenizi çalıştırmak için geliştirme ortamınızın "Run" veya "Debug" seçeneklerini kullanabilirsiniz.

6. Sonuçları Kontrol Etme: Proje başarıyla çalıştığında veya test senaryolarınızı çalıştırdığınızda, sonuçları geliştirme ortamınızın konsolunda veya projenizin kullanıcı arayüzünde görebilirsiniz.


## Yardım

Eğer projemle ilgili herhangi bir sorunuz, geri bildiriminiz veya destek talebiniz varsa, lütfen aşağıdaki iletişim yöntemlerinden birini kullanarak bize ulaşın:

- **E-posta:** [io.mersys.test.team1@gmail.com](mailto:io.mersys.test.team1@gmail.com)

- **GitHub:** [TechnoStudy & E-Junkie Tests](https://github.com/ebuzer33/Selenium_Project_3.git)

Bizimle iletişime geçmekten çekinmeyin, her türlü sorunuzu ve geri bildiriminizi bekliyoruz. 
Projemizin geliştirilmesine katkıda bulunmak veya herhangi bir sorunu çözmek için buradayız! 👋

## Katılımcılar: (TEMSİLİDİR)

| İSİM         | E-MAIL               | GITHUB                          | POZİSYON |
|--------------|----------------------|---------------------------------|----------|
| Zehra Kara   | z_kara@gmail.com     | https://github.com/zeh_kara     | QA Lead  |
| Hasan Yavuz  | yavuz_h@gmail.com    | https://github.com/hasan045     | SM       |
| Ali Yeşil    | ali.yesil@gmail.com  | https://github.com/ayesil00     | PO       |
| Ayşe Yılmaz  | ayilmaz@yahoo.com    | https://github.com/ayse099      | Tester   |
| Fikri Solmaz | f.solmaz@hotmail.com | https://github.com/fikri_solmaz | Tester   |

## Sürüm Geçmişi

* 0.2
    * Çeşitli hata düzeltmeleri ve optimizasyonlar
    * [Commit değişikliklerini görüntüle](https://github.com/ebuzer33/Selenium_Project_3/commits/main/src)
* 0.1
    * İlk Sürüm

## Lisans
2023 ©Techno Study

Bu yazılımın ve ilgili dokümantasyon dosyalarının ("Yazılım") bir kopyasını alan herhangi bir kişiye, kullanma, kopyalama, değiştirme, birleştirme hakları da dahil olmak üzere ancak bunlarla sınırlı olmamak üzere, kısıtlama olmaksızın Yazılım üzerinde işlem yapmasına işbu belge ile ücretsiz olarak izin verilmektedir. Aşağıdaki koşullara bağlı olarak Yazılımın kopyalarını yayınlayabilir, dağıtabilir, alt lisans verebilir ve/veya satabilir ve Yazılımın sağlandığı kişilerin bunu yapmasına izin verebilirsiniz:

Yukarıdaki telif hakkı bildirimi ve bu izin bildirimi, Yazılımın tüm kopyalarına veya önemli bölümlerine dahil edilecektir.

YAZILIM, TİCARİ ELVERİŞLİLİK, BELİRLİ BİR AMACA UYGUNLUK VE İHLAL ETMEME GARANTİLERİ DAHİL ANCAK BUNLARLA SINIRLI OLMAMAK ÜZERE AÇIK VEYA ZIMNİ HERHANGİ BİR GARANTİ OLMAKSIZIN "OLDUĞU GİBİ" SAĞLANIR. YAZARLAR VEYA TELİF HAKKI SAHİPLERİ HİÇBİR DURUMDA, YAZILIM VEYA KULLANIM VEYA DİĞER İŞLEMLERDEN KAYNAKLANAN, YAZILIMDAN VEYA KULLANIMDAN VEYA DİĞER İŞLEMLERDEN KAYNAKLANAN, BİR SÖZLEŞME DAVASINDAN, HAKSIZ FİİLDEN VEYA BAŞKA BİR ŞEKİLDE HERHANGİ BİR İDDİA, ZARAR VEYA DİĞER SORUMLULUKTAN SORUMLU OLMAYACAKTIR. YAZILIM.

