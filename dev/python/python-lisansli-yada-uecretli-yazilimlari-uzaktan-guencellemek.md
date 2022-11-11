# Python Lisanslı Yada Ücretli Yazılımları Uzaktan Güncellemek

Merhabalar. Freelance çalışan bir yazılımcı olarak ürettiğim yazılımları genelde birçok kişiye satıyorum. Ve bu yazılımlar ya lisanslı yada ücretli olarak satıldığı için güncellemeleri kullanıcılara elle göndermek zorunda kalıyordum. Şimdi bunu nasıl çözeceğimizi göreceğiz.



## Github Hesabı Açılması

https://github.com/

* [x] Sayfaya giriş yapıp `Sign Up` kısmından gerekli bilgileri girerek kayıt olalım
* [x] Python kodunuzun içine `os.system("git pull --rebase")` komutunu ekleyelim.
* [ ] Bu komut sayesinde yazılımız ile repo arasındaki fark farkedilip güncellenecektir.
* [x] Bir private repo açıp içine python dosyalarımızı yükleyelim.

## Gitfront io Hesabı Açılması

https://gitfront.io/

* [x] Sayfaya giriş yapıp `Get Started` kısmından gerekli bilgileri girerek kayıt olalım

<figure><img src="https://www.hizliresim.com/qn242sw.png" alt=""><figcaption></figcaption></figure>

\* \[x] Add Repository Kısmından githuba yüklediğimiz reponun ssh url'ini girelim \*

<figure><img src="hhttps://www.hizliresim.com/oumfggz.png" alt=""><figcaption></figcaption></figure>

\*\[x] Ve bize vereceği keyi repomuza deploy edip build yapalım. \*\[x] \`View\`'e basıp karşımıza çıkan \`clone\` tuşundan link alıp istediğimiz cihaza \` git clone\` yöntemiyle klonlayabiliriz artık

## Yazılım Güncellemesi

* [x] Güncellediğiniz yazılım dosyalarını github'daki reponuza sürükleyin
* [x] Ve gitfronttan reponuzun üzerine tıklayıp rebuild edin.
* [x] Artık dağıttığınız müşteri programı yeniden başlattığında `os.system("git pull --rebase")` komutu çalıştığında yazılım yeni haliyle güncellenmiş olacaktır. Tabiki müşterinin yazılım üzerinde oynama yapmaması gerekiyor.
