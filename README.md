<!DOCTYPE html>

<html>
    <!-- Belajar bikin website coy -->
<head>
    <title>My First Website</title> 
</head>
<body>

    <h1>Selamat datang</h1>
    <h3>Ini website pertama saya yang masih belajar</h3>
    <hr>
    <p>Jadi, apa yang akan saya tulis disini? kita bakal coba narok Hyperlink</p>
    <h3>Apa itu Hyperlink?</h3>
    <h4>Hyperlink adalah link yang bisa di tekan</h4>
    <br>
    <p>Kita tes google coba</p>
    Click this -->  

                                <!--target bisa _self kalo mau buka ke tab sendiri-->
    <a href="https://www.google.com" target=_blank title="Ini bakal ke google ya"> 
        Google
    </a>

    <h><p>bisa juga ke link manapun contoh Whatsapp, youtube, dll.</p></h>
    <br>
    <p>Ya itu tadi mencoba Hyperlink di google</p>
    <p>Sekarang kita mau nyoba buka ke page 2 pake Hyperlink</p>
    Click this to go to page 2 --->

    <a href="page2.html" target="_self" title="Ini bakal ke page 2">
        Halaman 2
    </a>

<p>oke coy sekarang kita tes gambar pake Hyperlink</p>

     <!--Kalo kebesaran kita pake command "height, width"-->
     <dl>
        <dt>
            <a href="https://en.wikipedia.org/wiki/Frank_Sinatra" target="_blank">
            <img src="Images/Frank Sinatra.jpg" height="250" alt="Frank Sinatra" title="Frank Sinatra"> 
    </a> 
    <dd>Frank Sinatra 1955</dd>
     </dl>
     <p>Ini adalah gambar Artis favorit gua coy</p>
     <p>Kalo lu teken tu gambar, lu bakal kebawa ke wikipedianya</p>
<h></h>
<br>
<p>oke coy tadi itu gambar, sekarang kita masuk ke Audio</p>
     <audio controls> <!--beberapa command untuk audio "autoplay, muted, loop"-->
         <source src="/Music/Five Minutes More.aac">
         <source src="/Music/Five Minutes More.mp3"> <!--Contoh backup kalo web tidak support .aac-->
    </audio>
    <p>ini salah satu lagu Frank Sinatra yang saya sering dengar belakangan ini</p>

    <h></h>
<br>
<p>oke coy sekarang kita masuk ke video</p>
      <!--  MP4, WebM, and Ogg  -->

     <video controls loop width="400">
          <source src="/Video/Frank Sinatra - Fly Me To The Moon (Live At The Kiel Opera House, St. Louis, MO_1965).mp4">
     </video>

     <p> oke coy tadi itu video konser Frank Sinatra fly me to the moon</p>
     <p>apa lagi yang dibahas?</p>


</body>
</html>
