---
layout: post
author: a4ade
---
aylardır blog veya benzeri günlük ayarında birşey tutmadığım için komple işin raconunu unutmuşum. bu github pages denilen üreme organından pek hallice sistemin yapısını tam çözemesem de çat pat bişeyler kurduk tıngırdatıyoruz bakalım.

bugün birden çok konuya değinicem ama bu jekyll'de nasıl kategori vs yapılıyor bilmediğimden bir makale içinde bir sürü konu yazıcam. makalenin tepesinde de sıralıcam isteyen istediğini gidip okusun. 


1. Kitap Yorumu
2. Günlük Hayattan Bukleler
3. Sikilen Kuşun Davası Olmaz

# Mühim Uyarı
Bu blogta metasploit nasıl kullanılır , frida ile ssl pinning nasıl bypass edilir , sqlmapa nasıl tamper verilir gibi dolu dolu konular olmayacağını önceden belirtmek isterim. Kafam basmıyor o kadarına benim.

## 1. Kitap Yorumu
![](https://i.hizliresim.com/wiBPSc.jpg)

Bu romalı yakışıklı abimiz Romalı bir köle. Hayatı boyunca tek aradığı şey içsel huzur , içsel huzuru nerede bulurum nasıl bulurum üzerine kafasının etini yiyip bitiriyor. En sonunda vardığı kanıları da bu şekilde kitap haline getiriyor. Kitap kafamdaki doluluk beni yanıltmıyorsa 86 sayfa civarındaydı bir oturuşta bitirilebilecek bi kitap ama 86 sayfası da dolu bir kitap. Epiktetos dayıyla tanrı konusunda kafamız çok uyuşmasa da içsel huzur konusunda bir çok konuda güzel noktalara dokunmuş beni bile gazlamayı başarmıştır. Kitaptan hoşuma giden bir yeri şöyle bırakayım;

```
Çocuğunuz, karınız, kocanız ya da çok sevdiğiniz birisi öldü mü? 
Böyle bir durumda herkes şöyle diyecektir:
“Bu bir yaşam döngüsüdür. Ölüm olur. Bazı şeyler kaçınılmazdır.”
Ama kendi çocuğumuz ya da çok sevdiğimiz birisi öldüğünde ağlamaya eğilimliyizdir.
“Ne kadar kederliyim. Ne kadar talihsiz bir insanım!”
Anımsayın: Bir başkasını ilgilendiren herhangi bir şeyi duyduğunuzda nasıl duygulanmıştınız?
Kendiniz böyle bir olayla karşılaştığınızda da bu duyguyu taşıyın.
Olayları kabullenmesini öğrenin, ölümü de zekanızla kabullenin.
```

Canım ülkemde bu tavrı takındığınızda muhtemelen çevreniz tarafından "senin kalbin taş olmuş , aq duygusuzu" şeklinde linç yersiniz. Yine de epiktetos dayı ufaktan güzel noktaya parmak atmış.

## 2. Günlük Hayattan Bukleler

Geçen gün otobüste kulaklık takılı şarkı modundayken ineceğim durağa yaklaşınca kulaklığı çıkardım. Ufak sevimli bi çocuk vardı annesiyle beraber oturuyordu. Çocuk "aa anne istiklal marşını ezberlemeyi unuttum" dedi. Annesinden beklediğim cevap "uyy çen ezberlemeyi mi unuttun" gibi yumuşak bir cevap olsa da verdiği cevabı ayakta alkışlayasım geldi. Çocuk dediği gibi direk "unutursun tabi , salak saçma youtuberleri izleyeceğine git istiklal marşını ezberle. saçma sapan serseri tipler bişey anlattıkları ettikleri yok" vs vs diye uzun bir punchline attı oğluna. Vallahi böyle ebeveynleri görmek gözlerimi yaşartıyor.

Youtube Türkiye tam olarak ahır yeminle bak. Arada önüme düşüyor video başlıklarına bakıyorum "Dünyanın en acı biberini yedim" , "1000tlye döner yedim" gibi başlıklar paso. Lan yediysen sen yedin ben bunu niye izliyim aq? Daha ilginci bunu izleyip zevk alan var mı? Andavalın biri kameranın karşısında yemek yiyor yada video açıp "selam dostlar şimdi bu videoyu izleyip gülmeyecem" diye 20 dakika video çekiyor. Bir grup diğer andaval da bunları izliyor. olm siz şaka mısınız aq? Hayatta hiç mi tutunacağınız şeyler yok , hiç mi bir uğraşınız sorumluluğunuz yok? Hadi küçük yaştakiler izliyor da ülkede o kadar küçük nüfus yok bunları aranızda izleyenler var. Nabıyonuz olm siz? 

## 2. Sikilen Kuşun Davası Olmaz

En sevdiğim konuya geldik. Küfür ederken sesimin yüksek desibelinin kulaklarınızda yaratacağı zarardan ben sorumlu değilim.

Geçtiğimiz gün kuş logolu malum siteye bir hack girişimi yaşandı ve vizyonsuzluğun dibine vuruldu. Olay hakkında naçizane yorumum ve piyasadaki magazinci boynuzu kırık arkadaşlar hakkında laflayayım;

Hack tarafının sosyal mühendislik ile yapıldığı çok belliydi. Twitter gibi bir yerde o şekil hesaplara erişim sağlaması için ya OAuth'ta bir açık bulacak , ya API'lerde bir şey bulacak ya da düz yetkili bir departmana sm yutturup intranete dalacaktı. Sosyal mühendislik çekerek panele kadar erişmesi büyük başarı. Çünkü sosyal mühendislik te çekse twitterden bahsediyoruz aq , milyon dolarlık firewallar var biri de düüt demedi mi? diyor insan içinden. Çünkü normal şekilde sm çekerek şifreyi direk alma olasılığı düşük , kuvvetle muhtemel karşıki bilgisayarda bulunan herhangi bir serviste buffer/heap overflow tarzı bir açık bulup (meşhur sorgusuz) onun vasıtasıyla daldı. Yani işin içinde teknik kesinlikle olacağına ihtimal vererek değerlendirdiğimde çok kıyak olay.

Ama madem bu kadar uğraştın girdin panele tweet atabiliyon istediğin hesaptan , panelden screen falan atıyon. Lan niye btc dileniyon? 12 BTC bizim kurla güzel para da olsa yapanın yurtdışı menşeli biri olduğunu düşünürsek alınan riske yapılacak işe değecek para değil. Çeksene dataları aq? Yada ilerleyip komple dbyi almaya çalışsana zaten yeteri kadar uğraşmışsın. Vizyonunuzun götüne madik atayım yapan yüzde yüz hintli falandır aq bu mallık başka bir millette olamaz valla imkan vermiyom. Rus falan olsa götüne koyar geçerdi twitterin onun bunun.

Şimdi işin asıl kısmına geldik. Adamlar twitteri hacklemiş , tamam çıkar yorumunu yaparsın bunda bişi yok aq bak ben bile yaptım. Ama şu siktiğimin olayı hakkında bir kere konuşun lütfen ya. Yapan adamlar ses etmiyor , piyasadan olanlar bir kere konuşuyor bu şirazesi bozuk ibneler 40 gün 40 gece olayla alakalı yorum yapıyor. Ya arkadaş size çalıştığınız şirketiniz bunun için mi para veriyor aq? Lafa geldi mi "yabancılar neler yapıyo , bide bizim türklere bak" dersiniz. Lan siz naptınız aq sektörüne ne katkınız dokundu kaç tane yazılı exploitiniz var? Yeni atak vektörü mü geliştirdiniz bizim milleti eleştiriyonuz? Adamın tek vasfı metasploit nedir , sqlmap nasıl kullanılır , pythonla brute forcer yazma gibi angut angut konuları sikik blogunda ele almak. Ha bide yeni olan olayları 1 yıl boyunca konuşmak. Çenenizin kemiği kitlene de biz de rahat edek aq. Bu yazı da burada biter , diğer yazıları da bu konseptte yapıcam kategorilendiremediğim için bu 3 başlığı 3 ayrı makaleye bölsem blogun düzeni bozulacaktı. Bu yüzden bu şekilde ele almak daha doğru geldi. Düzen bu yani , burdan devam. Hadi ben kaçtım.
