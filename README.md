<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box;}

body { 
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.header {
  position: fixed;
  overflow: hidden;
  background-color: #f8f8f8;
  background-image: linear-gradient(90deg, #46074E 0%, rgba(25, 123, 208, 0.8) 100%);
  width: 1335px;
}

.header a {
  float: left;
  color: white;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  position: 100%;
  font-size: 18px; 
  line-height: 25px;
  border-radius: 20px;
  margin-left: 20px;
  margin-right: 20px;
}

.header img{
  margin-left: 90px;
}

.header a:hover {
  background-color: #ddd;
  color: black;
}

.header a.active {
  background-color: dodgerblue;
  color: white;
}

.header-right {
  float: right;
}

@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  
  .header-right {
    float: none;
  }
}

.rectangle {
    background-color: #195395;
    border: 1px solid rgba(255, 255, 255, 0.2);
    border-radius: 10px;
    width: 140px;
    height: 50px;
}

.konten {
    width: 100% ;
    height: 100%;
    
}

.konten img{
    border: 1px solid rgba(255, 255, 255, 0.4);
    display: inline-block;
    background-image: linear-gradient(90deg, #46074E 0%, rgba(25, 123, 208, 0)
    100%);
    border-radius: 6px;
    width: 280px;
    height: 158px;
    margin-left: 20px;
    margin-top: 45px;
}

.section1 h2{
    position: absolute;
    margin-left: 6%;
    margin-top: -8%;
    font-size: 36px;
    line-height: 43px;
    text-align: left;
    color: #FFFFFF;
}

.section2{
    margin-top: 95px;
    color: #4A4A4A;
    font-family: Ubuntu;
    font-size: 16px;
    line-height: 30px;
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;   
}

hr{
    float: center;
    width: 90%; 
    border: 1px solid #EAEAEA;  
}

.inimely {
    background-image: linear-gradient(90deg, #46074E 0.36%, rgba(25, 123, 208,0.8) 100%);
    border-radius: 22.5px;
    width: 200px;
    height: 45px;
    color: #FFFFFF;
    font-family: Ubuntu;
    font-size: 15px;
    line-height: 18px;
    text-align: center;
}

.melycantik {
    border: 1px solid #46074E;
    border-radius: 22.5px;
    width: 200px;
    height: 45px;
    color: #336195;
    font-family: Ubuntu;
    font-size: 15px;
    line-height: 18px;
    text-align: center;
}

.hint1 {
  font-family: 'Times New Roman', Times, serif;
  
}

.footer {
    height: 80px;
    width: 100%;
    background-color: linear-gradient(90deg,#46074E 0%,rgba(25,123,208,0.8)100%);
    background-image: linear-gradient(90deg, #46074E 0%, rgba(25, 123, 208, 0.8) 100%);
    text-align: center;
    color: white;
    padding: 17px;
}
</style>
</head>

<body>
<div class="header"> 
    <br>
    <img src="logolucu.jpg" width="50" height="50">
    <div class="header-right">
      <a class="home">Home</a/>
      <a class="#Tentang kami">Tentang kami</a/>
<a class="#layanan kami">Layanan kami</a/>
      <a class="#artikel">Artikel</a/>
      <a class="#hubungi kami">Hubungi kami</a/>
    <a class="box">
      <span class="box"><i class="fa fa-search"></i></span>
      <input type="search" id="search" placeholder="Search..." />
    <a href="#Daftar Online" class="rectangle">Daftar Online</a>
    </div>
  </div>

  <div class="section1">
    <img src="layanankami.jpg" width="100%" height="300vh"></a>
    <h2>LAYANAN KAMI</h2>
  </div>
  
  <div class="konten">
    <center>
      <img src="makanan1.jpg" alt="">
      <img src="makanan2.jpg" alt="">
      <img src="makanan3.jpg" alt="">
      <br>
      <img src="minuman1.jpg" alt="">
      <img src="minuman2.jpg" alt="">
      <img src="minuman3.jpg" alt="">
    </center>
  </div>
  <br>
<hr>

  <div class="section2">
    <h2>HUBUNGI KAMI</h2>
    <h3>KANTOR PUSAT</h3>
    <h4>Gedung Ir. H. M. Suseno - JL. R.P Soeroso No.6, Menteng, Jakarta Pusat</h4>
    <h4>Phone: (+62 21) 398 38706 - Fax: (+62 21) 316 1701</h4>
    <h4>Hotline: +6281519040071 / +6211998167</h4>
    <br>
    <button class="inimely">LOKASI KAMI</button>
    <button class="melycantik">KIRIM PESAN</button> 
  </div>
<br>
<br>
<br>
<br>

  <div class="footer">
    <p> Copyright © 2022 - Inaklug Indonesia | Hak cipta dilindungi undang-undang </p>
  </div>

</body>
</html>
