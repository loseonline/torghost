## TorGhost nedir?
TorGhost bir anonimleştirme betiğidir. TorGhost, tüm internet trafiğini SOCKS5 tor proxy üzerinden yönlendirir. DNS istekleri de tor üzerinden yönlendirilir, böylece DNSLeak engellenir. Komut dosyaları, sistemden çıkan güvenli olmayan paketleri de devre dışı bırakır. Ping isteği gibi bazı paketler kimliğinizi tehlikeye atabilir.

## Kaynaktan derleyin ve kurun
`git klonu https://github.com/usermusti/torghost.git`

"cd torghost"

`chmod +x build.sh`

`./build.sh`

## Nasıl kurulur ?
**Yeni kali güncellemesi izin hatasına neden oluyor, lütfen kaynaktan derleyip kurun**

` TorGhost, debian paket yöneticisi kullanılarak [en son sürüm](https://github.com/usermusti/torghost/releases) indirilerek kurulabilir `
` İndir `

` wget -c https://github.com/usermusti/torghost/releases/download/v3.0.2/torghost-3.0.2-amd64.deb`

**İndirilen klasörde yüklemek için dpkg kullanın**

`sudo dpkg -i torghost-*-amd64.deb`



#### Alternatif yöntem (önceki yükleme komut dosyası desteği)
*install.sh* betiği de aynı şeyi yapar. Eski öğreticileri takip eden kullanıcılar içindir.

`git klonu https://github.com/usermusti/torghost.git`

"cd torghost"

`chmod +x install.sh`

`./install.sh`


## Kullanım
Torghost v3.0 kullanımı:

` -s --start Torghost'u Başlat'

` -r --switch Yeni tor çıkış düğümü iste`

` -x -- Torghost'u Durdur `

` -h --help Bu yardımı yazdır ve çık`

` -u --update Güncellemeleri kontrol eder`




