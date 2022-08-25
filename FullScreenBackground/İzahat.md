### background xüsusiyyətləri
- background-origin(default value:padding-box) - arxa fon şəklinin hardan başlayacağını müəyyən edir:
    - padding-box: hansı qutunun içindədirsə onun sol küncündən başlayır
    - border-box: hansı qutunun içindədirsə, onun sərhədi də daxil olmaqla sol küncdən başlayır
    - content-box: qutunun içindəki kontentin sol küncündən başlayır
- background-attachment(default value:scroll) - arxa fon şəklinin səhifəylə birlikdə necə hərəkət edəcəyini müəyyən edir
    - scroll: yəni tutaq ki səhifəni  çox aşağı scroll etsək o yuxarıda qalacaq və görünməyəcək.
    - fixed: yeri sabitdir, scroll edəndə yenə eyni yerdə qalır.
- background -color(default value:transparent) arxa fona rəng verməyi təmin edir
    - müəyyən rəng, red blue vs 
    - transparent - şəffaf, ağ yəni(?)
- **background- clip(bu sanki mənə background-attachment-in rəng üçün versiyası kimi gəldi, amma tam anlamadım)**

### background-un hər bir xüsusiyyətini tək tək yazmaq yerinə, bir anda elan etmək olur
Ornək:
background-image: url(random image);
background -attachment: fixed;
bacground-repeat: no repeat;

belə də yaza bilərik

background: url(random image]) fixed no repeat;
