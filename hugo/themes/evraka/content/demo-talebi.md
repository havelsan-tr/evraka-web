---
title: "Demo Talebi"
title_hidden: true
menu:
  main:

    weight: 4

---

<div class="row">
<div class="col-12 col-lg-6">
    <h2>Deneyim için Formu Doldurun</h2>
    <p>
        Ücretsiz Demo İsteyin! Kağıda dayalı bütün süreçlerinizi dijital ortamda yönetmek, mevzuat ve yönergelere uygun belge üretmek için ilk adımı EVRAKA ile başlatabilirsiniz.
    </p>
    <p>
        EVRAKA ile belge üzerinden yürütülen iş süreçleri otomatik hale gelir, karar verme süreçleri hızlanır, işlem kuyrukları ve tamamlanma süresi kısalır, insan hataları ortadan kalkar, zaman kaybı ve maliyetler azalırken, kalite ve verimlilik artar.
    </p>
</div>
<div class="col-12 col-lg-6">
    <style>
        .form-group > label {
            font-weight: 600;
            font-size: 14px;
            text-transform: uppercase;
            color: rgba(0,0,0, 0.7);
        }
        .form-control {
            border-bottom: 2px rgba(0,0,0,0.2) solid;
        }
    </style>
    <div id="uyari"></div>
    <form id="contact" action method="post">
        <div class="form-group">
            <label for="kurum-adi">Kurum Adı</label>
            <input name="kurum-adi" type="text" class="form-control" id="kurum-adi">
        </div>
        <div class="form-group">
            <label for="name">İletişim kurulacak kişinin adı ve soyadı</label>
            <input name="name" type="text" class="form-control" id="name">
        </div>
        <div class="form-group">
            <label for="email">E-posta adresi</label>
            <input name="email" type="email" class="form-control" id="email">
        </div>
        <div class="form-group">
            <label for="telefon">Telefon</label>
            <input name="telefon" type="text" class="form-control" id="telefon">
        </div>
        <div class="form-group">
            <label for="aciklama">Mesaj</label>
            <textarea class="form-control" id="aciklama" name="aciklama" rows="3"></textarea>
        </div>
        <small>
                Bu iletişim formu reCAPTCHA from Google ile korunmaktadır.<br>
              <a href="https://policies.google.com/privacy">Gizlilik Politikası</a>
              <a href="https://policies.google.com/terms">Hizmet Koşulları</a></small> <br> <br>
        <button type="submit" id="contactButton" class="btn btn-primary">Gönder</button>
    </form>
</div>
</div>
