# Discord SuperVisor Bot

# Kurulum
* Bu projeyi zip halinde indir.
* Herhangi bir klasöre zipi çıkart.
* Githuba Yükle Gizle ama
* Glitch Aktar
* Daha sonra `src`dosyasındaki `Settings` dosyasının içindeki `Config.json`, `Settings.json` dosyalardaki bilgileri doldur.
* ```npm install``` yazarak tüm modülleri kur.
* Kurulum bittikten sonra ```node Rahibe.js``` yaz ve botu başlat.


## Botun İntentlerini Açmayı Unutma!
* [Açmak İçin Tıkla](https://discord.com/developers/applications)
<img src="https://cdn.discordapp.com/attachments/818953120452575322/851116463166849054/3P4KKB.png"/>

***Tadaaa 🎉. Artık supervisor botun hazır. Dilediğin gibi kullanabilirsin.***


## Settings.json Bilgi

```json
{
    "Token": "TOKEN",
    "GuildID": "SUNUCU_ID",
    "Prefix": ["PREFİX"],
    "BotVoice": "SES KANALI",
    "Status": "DURUM",
    "Tag": "TAG",
    "UnTag": "TAG"
}
```

## Config.json Bilgi

```json
{
    "Yetkili": {
        "AbilityYT": "TÜM_KOMUTLARA_ERİŞİM",
        "BanYT": "BAN_YETKİ",
        "jailYT": "JAİL_YETKİ",
        "muteYT": "MUTE_YETKİ",
        "vmuteYT": "VMUTE_YETKİ",
        "registerYT": "KAYIT_YETKİ"
    },
    "Roller": {
        "Jailed": "JAİL_ROL",
        "Muted": "MUTE_ROL",
        "VMuted": "VMUTE_ROL",
        "Booster": "BOOSTER_ROL",
        "VIP": "VIP_ROL"
    },
    "Register": {
        "e1": "ERKEK1_ROL",
        "e2": "ERKEK2_ROL",
        "e3": "ERKEK3_ROL",
        "k1": "KADIN1_ROL",
        "k2": "KADIN2_ROL",
        "k3": "KADIN3_ROL",
        "unreg": "KAYITSIZ_ROL",
        "süpheli": "ŞÜPHELİ_ROL",
        "TagRol": "TAG_ROL"
    },
    "Log": {
        "HosgeldinKanal": "HOŞGELDİN_KANAL",
        "Sohbet": "SOHBET_KANAL",
        "RolLog": "ROLLOG_KANAL",
        "SesLog": "SESLOG_KANAL",
        "ModLog": "MODLOG_KANAL",
        "CezaPuanLog": "CEZAPUANLOG_KANAL",
        "BanLog": "BANLOG_KANAL",
        "RegisterLog": "KAYITLOG_KANAL",
        "MuteLog": "MUTELOG_KANAL",
        "JailLog": "JAİLLOG_KANAL",
        "VMuteLog": "VMUTELOG_KANAL"
    },
    "Diger": {
        "onay": "<a:atlas_onay:852922602385047604> ŞEKLİNDE DEĞİŞTİRİN",
        "red":"<a:atlas_red:852922603010392124> ŞEKLİNDE DEĞİŞTİRİN"
    }
}
```


# İçerikler

## • Genel {
  - [x] Me
  - [x] Avatar  
  - [x] Çek 
  - [x] Git
  - [x] Snipe
  - [x] Kilit
  - [x] Me
  - [x] Nuke
  - [x] Rol-İnfo
  - [x] Say
  - [x] Mod-Log
## };
## • Moderasyon {
  - [x] Ban
  - [x] Unban
  - [x] Jail
  - [x] Unjail
  - [x] Mute
  - [x] Unmute
  - [x] Vmute
  - [x] Unvmute
  - [x] Sicil
  - [x] Cezapuanı
  - [x] Cezapuanı-Sıfırla
## };
## • Kayıt {
  - [x] Erkek
  - [x] Kadın
  - [x] Kayıtsız
  - [x] İsim
  - [x] İsimler
  - [x] Kayıtlarım
  - [x] Top Teyit
## };
## • Stat {
  - [x] Me
  - [x] Top
  - [x] Top-Text
  - [x] Top-Voice
  - [x] Stat-Sıfırla
## };
