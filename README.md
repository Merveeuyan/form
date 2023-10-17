<!DOCTYPE html>
<html>
    <head>
        <title>satış sözleşmesi</title>
     </head>
     <body>
        <head>
            <h1>ABC Satış Sözleşmesi</h1>
        </head>
        <form>
            <fieldset>
                <legend>Sözleşme Onay</legend>
                <input type="checkbox" required>Aşağıda ki bilgileri onaylıyorum ve sözleşmeyi kabul ediyorum<br/>
                <input type="submit" name="gönder" value="Formu Kaydet">
                <input type="submit" name="reset" value="Formu Temizle">
            </fieldset>
            <fieldset>
                <legend>Kişisel Bilgiler</legend>
                <p>Form<br/> Güvenlik ID:<input type="text" placeholder="asdf" required></p>
                <p>Ad:<input type="text" name="Ad" placeholder="Adınızı girin"></p>
                <p>Soyad<input type="text" name="soyad" placeholder="Adınızı girin"></p>
                <p>Yaş:<input type="number" name="yaş"></p>
                <p>Mail Adresi:<input type="email" required></p>
                <p>Fotoğraf<br/>Ekle    <input type="submit" name="gonder" value="Dosya Seç">Dosya Seçilmedi</p>
            </fieldset>
            <fieldset>
                <legend>Diğer Bilgiler</legend>
                <strong>Buradaki alanlar mesleki deneyimi kapsar</strong>
                <p>sektöre giriş tarihi<input type="date"></p><br/>
                <p>sektör deneyimi
                    <input type="radio" name="secim" value="1-5 yıl" >1-5 yıl<br/>
                    <input type="radio" name="secim" value="6-10 yıl" >6-10 yıl<br/>
                    <input type="radio" name="secim" value="11-15 yıl">11-15 yıl<br/>
                    <input type="radio" name="secim" value="15 ve üzeri">15 ve üzeri</p>
                    <p>Programlama Dilleri &nbsp;<select name="diller" multiple>
                        <option value="1">C#</option>
                        <option value="2">PHP</option>
                        <option value="3">Java</option>
                        <option value="4">Python</option>
                        <option value="5">JavaScript</option>
                    </select></p>
            </fieldset>
            <fieldset>
                <legend>Sözleşme kopyası</legend>
                <textarea>Loren ıpsum, dizgi ve baskı endüstirinde kullanılan mıgır metinlerdir loern ipsum 
                    adı bilinmeyen bir matbaacının bir hurufet numune kitabı oluşturmak üzere bir yazı galserini alarak karıştırdığı 100lerden neri endüstri
                </textarea>
            </fieldset>
            <fieldset>
                <legend>Mail listesi</legend>
                <p>mail listesine katılmak <b>istiyorum</b><input type="radio" name="secim"></p>
                <p>mail listesine katılmak <b><u>istemiyorum</u></b><input type="radio" name="secim"></p>
            </fieldset>
        </form>
       
     </body>
</html>
