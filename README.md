﻿# SmartFileReader
Bu proje, Word (.docx), Excel (.xlsx), PDF (.pdf) ve metin (.txt) dosyalarını yükleyerek içeriklerini okuma, yazar bilgilerini alma ve arama yapma işlemlerini gerçekleştiren bir Windows Forms uygulamasıdır.

Özellikler
Farklı formatlardaki dosyaları (docx, xlsx, pdf, txt) yükleyerek içeriklerini okuyabilir.
Dosya yazarı, oluşturulma tarihi ve sahibi gibi bilgileri görüntüleyebilir.
Dosya içeriğinde arama yaparak belirli kelimeleri içeren dosyaları listeleyebilir.
Kullanıcı dostu bir arayüz sunar.

Kurulum

Gereksinimler
Windows işletim sistemi
.NET Framework
Visual Studio (derleme ve düzenleme için)
Microsoft Office (Word ve Excel dosyaları için)
iTextSharp kütüphanesi (PDF okuma için)

Adımlar
Proje dosyalarını indirin veya klonlayın:
git clone <repository-url>
Visual Studio ile projeyi açın.
Gerekli bağımlılıkları yüklenin:
Microsoft.Office.Interop.Word
Microsoft.Office.Interop.Excel
iTextSharp

Projeyi derleyin ve çalıştırın.

Kullanım

Dosya Yükleme: "Dosya Yükle" butonuna basarak bilgisayarınızdaki dosyaları yükleyin.

Dosya Bilgilerini Görme: Yüklenen dosyaların ismi, yazarı, oluşturulma tarihi ve sahibi veri tablosunda listelenir.

Arama: Aramak istediğiniz kelimeyi girerek "Ara" butonuna basın. Arama sonucunda ilgili dosyalar listelenecektir.
