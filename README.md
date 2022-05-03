### Member Adding Bot
Telegram Kanal,Grup User Elave Edmek Ucun Program!

<img src="https://te.legra.ph/file/50771de1bcd2e67af5ae4.jpg" width="1000" height="1000">
</p>


     [DegGixM]("https://t.me/DegGixM") 
     

<p align="center">
  <img src="https://raw.githubusercontent.com/th3unkn0n/TeleGram-Scraper/master/.image/20191203_205322.jpg" width="470" height="150">
</p>

## • API Quraşdırma
* http://my.telegram.org saytına daxil olun və daxil olun.
* API inkişaf alətlərinə klikləyin və tələb olunan sahələri doldurun.
* istədiyiniz proqram adını qoyun və platformada digərini seçin Misal:
* Tətbiq yarat düyməsini kliklədikdən sonra "api_id" və "api_hash"-ı kopyalayın (setup.py-də istifadə olunacaq)
* 
## •Necə Quraşdırılır və İstifadə Edilir

`$ pkg install -y git python`

`$ git clone https://github.com/th3unkn0n/TeleGram-Scraper.git`

`$ cd TeleGram-Scraper`

* Quraşdırma tələbləri

`$ python3 setup.py -i`

* Quraşdırm Konfiqurasiya Faylı (api ID, api HASH)

`$ python3 setup.py -c`

* İstifadəçi Məlumatlarını Maratmaq üçün

`$ python3 scraper.py`

* (adı dəyişsəniz, member.csv defoltdur, ondan istifadə edin)
* Toplanmış məlumatlara toplu sms göndərin

`$ python3 smsbot.py members.csv`

* Yeniləmə Aləti
* 
`$ python3 setup.py -u`
