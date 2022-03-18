---
page_title: Politikalar ve Eklentiler
title: Liman MYS'de Politikalar
layout: skeleton
menu:
    main:
        name: "Özellikler"
        weight: 3
    nav:
        name: "Politikalar ve Eklentiler"
        weight: 1
        pre: "fa-cogs"
        post: "Liman MYS kabiliyetleri politika ve eklenti başlıklarıyla değerlendirilir."

---

<section id="policies" class="d-flex">
    <div class="container-fluid">
        <div class="row" data-aos="fade-up">
            <div class="container py-5">
                <div class="row">
                    <div class="col-12">
                        <h2>Liman MYS'de Politikalar</h2>
                        <p> Linux işletim sistemine sahip istemcileri ve kullanıcıları belirlenen ve ihtiyaç
                            duyulan kurallara bağlı olarak olarak uzaktan merkezi olarak yönetme imkanı sağlar.
                            Politikilarımız özellikle BT işletimini gerçekleştiren sistem yöneticilerinin
                            ihtiyaçları tespit edilerek geliştirilmiştir. Politikalarımız ile
                            kullanıcılarınızın, istemcilerinizin, sunucularınızın güncel, stabil ve güvenilir
                            olmasını sağlarsınız. </p>
                            <br>
                            <div class="text-center">
                            {{% image "liman-ozellikler.jpg" %}}
                            </div>
                            <br>
                            {{% policies %}}
                    </div>
                </div>
            </div>
        </div>
        {{% trial-banner %}}
        <div class="row" data-aos="fade-up">
            <div class="container py-5">
                <div class="row mb-5">
                    <div class="col-12">
                        <h2>Eklentiler</h2>
                        <p> Liman MYS, eklentileri aracılığıyla Linux ve Windows sunucuları yönetir. Eklentiler
                            mimarisi framework methoduyla çalışır, bu sebepten belirlenen ihtiyaçlar kadar Liman
                            MYS‘nin kabiliyetlerini genişletebilirsiniz. Eklentileri uzak sunucuları yönetmek,
                            log kaydı yapmak ve belirlenen görevleri yerine getirmek olduğu için Liman MYS
                            üzerinde hiç bir şekilde veri tutulmaz, yönetimi sağlanan mevcut sunucuların
                            verileri kullanılır. Bu sebeple, Liman MYS mevcut sistemlere down time korkusu
                            olmadan entegre olur. </p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-12 col-lg-6 order-1">
                        <h2>Domain Eklentisi</h2>
                        <p> Domain eklentisi ile AD, SAMBA sunucularını, kullanıcıları ve bilgisayarları yönetebilir, Palamar ile kolayca domaine alabilirsiniz. <br><br>
                        Eklenti özellikleri: </p>
                        <ul>
                            <li>Sunucu sistemler üzerinde kullanıcı, grup ve bilgisayar yönetimi yapılması
                            sağlanmaktadır.</li>
                            <li>Arayüz üzerinden MS Aktif Dizin ve SAMBA DC sunucular yönetilebilmelidir.</li>
                            <li>Yeni kullanıcı ekleme, düzenleme ve silme işlemleri yapılabilmelidir.</li>
                            <li>Yeni grup ekleme, düzenleme ve silme işlemleri yapılabilmelidir.</li>
                        </ul>
                        <br>
                        <a href="https://market.liman.dev/Application/liman.domain" target="_blank">Özelliklerin devamını gör...</a>
                    </div>
                    <div class="col-12 col-lg-6 order-2">
                        <a href="/images/policies/domain.jpg" data-gall="domain"
                            class="venobox">
                            <img src="/images/policies/domain.jpg" class="img-fluid" />
                            <div class="img-caption p-3 mb-5">
                                <div class="row">
                                    <div class="col"> Domain eklentisine daha yakından göz atmak için
                                        tıklayın... </div>
                                    <div class="col-auto align-self-center">
                                        <i class="fa fa-search fa-2x"></i>
                                    </div>
                                </div>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <div class="row gray" data-aos="fade-up">
            <div class="container py-5">
                <div class="row">
                    <div class=" col-12 col-lg-6 order-2 order-lg-1 "><a
                            href="/images/policies/postgresql.png" data-gall="jitsi" class="venobox">
                            <img src="/images/policies/postgresql.png" class="img-fluid" />
                            <div class="img-caption p-3 mb-5">
                                <div class="row">
                                    <div class="col"> PostgreSQL eklentisine daha yakından göz atmak için tıklayın...
                                    </div>
                                    <div class="col-auto align-self-center">
                                        <i class="fa fa-search fa-2x"></i>
                                    </div>
                                </div>
                            </div>
                        </a> </div>
                    <div class=" col-12 col-lg-6 order-1 order-lg-2 ">
                        <h2>PostgreSQL Eklentisi</h2>
                        <p> PostgreSQL eklentisi ile kullanıcı ekleyebilir, sorgu yapabilir, yedek alabilir, replikasyon ve daha bir çok işlemi gerçekleştirebilirsiniz. </p>
                        <p> Özellik listesi: </p>
                        <ul>
                            <li>Kullanıcı ekleme, yetkilendirme, silme</li>
                            <li>Veritabanı oluşturma, yedekleme, tablo ekleme, SQL dump yükleme ve vacuum işlemi</li>
                            <li>Veritabanları üzerinde sorgu çalıştırma, sorguları listeleme, CSV çıktılarını alma, kayıtlı sorguları çalıştırma işlemi</li>
                            <li>Veritabanı yedekleme işlemi (dump)</li>
                            <li>Replikasyon özelliği</li>
                            <li>Pgbench ile performans testi</li>
                            <li>Postgres config düzenleme özelliği</li>
                            <li>Postgres firewall kural ekleme</li>
                            <li>Servisi yeniden başlatma, durdurma özelliği</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="row" data-aos="fade-up">
            <div class="container py-5">
                <div class="row">
                    <div class="col-12 col-lg-6">
                        <h2>DNS Eklentisi</h2>
                        <p> DNS eklentisi sayesinde Samba ve Aktif Dizin sunucularınızın DNS kısmını sorunsuzca ve kolay bir şekilde yönetebileceksiniz.<br><br>
                        Eklenti üzerinde kolayca zone kayıtları üzerinde manipülasyon gerçekleştirilebilmektedir. Zone ekleme, zone düzenleme ve zone silme işlemleri hızlıca yapılabilmektedir. </p>
                    </div>
                    <div class="col-12 col-lg-6">
                        <a href="/images/policies/dns2.jpg" data-gall="dns" class="venobox">
                            <img src="/images/policies/dns2.jpg" class="img-fluid" />
                            <div class="img-caption p-3 mb-5">
                                <div class="row">
                                    <div class="col"> DNS eklentisine daha yakından göz atmak için tıklayın...
                                    </div>
                                    <div class="col-auto align-self-center">
                                        <i class="fa fa-search fa-2x"></i>
                                    </div>
                                </div>
                            </div>
                        </a>
                        <a href="/images/policies/liman-mys-dns-2.png" data-gall="dns"
                            class="venobox d-none">
                            <img src="/images/policies/liman-mys-dns-2.png" class="img-fluid" />
                        </a>
                        <a href="/images/policies/liman-mys-dns-3.png" data-gall="dns"
                            class="venobox d-none">
                            <img src="/images/policies/liman-mys-dns-3.png" class="img-fluid" />
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <div class="row info reverse">
            <div class="container py-5">
                <div class="row" data-aos="zoom-in">
                    <div class=" col-12 col-lg-2 text-center text-lg-left "> <img
                            src="/images/captain-reverse.svg" class="img-fluid" /> </div>
                    <div
                        class=" col-12 justify-content-end col-lg-7 d-flex flex-column text-center text-lg-left mt-3 mt-lg-0 ">
                        <h2>Bu bilgi dikkatinizi çekebilir?</h2>
                        <p> Liman'ın mimarisi hakkında detaylı bilgi için bu bağlantıyı kullanabilirsiniz. </p>
                    </div>
                    <div class=" col-12, col-lg-3 align-self-end text-center text-lg-left mt-3 mt-lg-0 "> <a
                            href="{{< relref "limanin-mimarisi.md" >}}" class="btn btn-secondary btn-lg">Liman Mimarisi</a> </div>
                </div>
            </div>
        </div>
        <div class="row" data-aos="fade-up">
            <div class="container py-5">
                <div class="row">
                    <div class=" col-12 col-lg-6 order-2 order-lg-1 ">
                        <a href="/images/policies/sambafileshare.jpg" data-gall="pxe" class="venobox">
                            <img src="/images/policies/sambafileshare.jpg" class="img-fluid" />
                            <div class="img-caption p-3 mb-5">
                                <div class="row">
                                    <div class="col"> SambaFileShare eklentisine daha yakından göz atmak için
                                        tıklayın... </div>
                                    <div class="col-auto align-self-center">
                                        <i class="fa fa-search fa-2x"></i>
                                    </div>
                                </div>
                            </div>
                        </a>
                    </div>
                    <div class="col-12 col-lg-6 order-1">
                        <h2>SambaFileShare Eklentisi</h2>
                        <p> Samba dosya paylaşımı eklentisi ile paylaşım izinlerini dosya ve klasör bazlı ayarlayabilir, smb.conf üzerinde paylaşım oluşturabilirsiniz.<br><br>
                        Eklentide yapabilecekleriniz:<br>
                        Samba dosya paylaşımı oluşturma<br>
                        Klasör ve dosya bazlı izinleri değiştirme (Acl)<br>
                        Samba servis durumunu kontrol etme </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="row gray" data-aos="fade-up">
            <div class="container py-5">
                <div class="row">
                    <div class="col-12 col-lg-6 order-1">
                        <h2>Depo Eklentisi</h2>
                        <p> Bu eklentinin aynalama sekmesi bölümünde uzaktaki depoları yerel sunucunuza çekebilir ve yerel sunucunuzdaki depoları kullanarak her türlü depo işlemlerini uzaktaki sunucuya bağlı kalmadan gerçekleştirebilirsiniz.
                        Yerel depo sekmesi sayesinde de kendi .deb paketlerinizden oluşan bir yerel depo oluşturabilirsiniz. Ve kendi yerel deponuzu ağınızdaki istemcilerle paylaşabilirsiniz. Ek olarak, yine bu sekme içerisinde IP üzerinden dosya paylaşabilmeniz için her türden dosya yükleme işleminin yapılabildiği "Dosyalar" bölümü bulunmakta.
                        Son olarak, paket arama bölümünde de hem aynalama hem de yerel depodaki paketlerin detaylarını görüntüleyebilir ve bu paketleri tekrardan indirebilirsiniz.
                        </p>
                    </div>
                    <div class="col-12 col-lg-6 order-2">
                        <a href="/images/policies/depo.jpg" data-gall="repo" class="venobox">
                            <img src="/images/policies/depo.jpg" class="img-fluid" />
                            <div class="img-caption p-3 mb-5">
                                <div class="row">
                                    <div class="col"> Depo eklentisine daha yakından göz atmak için
                                        tıklayın... </div>
                                    <div class="col-auto, align-self-center">
                                        <i class="fa fa-search fa-2x"></i>
                                    </div>
                                </div>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
