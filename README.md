<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" type="text/css" href="css/style.css">
        <title>Portofolio</title>
    </head>
    <style>
        /* css reset */
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, th,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	vertical-align: baseline;
}
/* end of css reset */
*{
    text-decoration: none;
    margin: 0;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, Arial;
    position: relative;
}

.clear{
    clear: both;
}

#black{
    background-color: black;
    color: white;
}

b{
    font-size: 30px;
}

p{
    font-size: 15px;
}

.container{
    background-color: #F0F0F0F0;
}

.head{
    display: flex;
    height: 40px;
    padding: 5px;
    margin-bottom: 80px;
}

/* nav */
.nav{
    width: 20%;
}

.nav ul{
    padding: 8px;
}

.nav ul li{
    display: inline-block;
    padding: 10px;
    font-size: 14px;
    font-weight: 500;
    border-radius: 10px;
    color: black;
}

.nav ul li:hover{
    color: white;
    background-color: black;
}

#black:hover{
    background-color: white;
    color: black;
}

/* end of nav */

.wrapper{
    width: 78%;
    margin: auto;
}

.wrap{
    height: 300px;
    margin-top: 30px;
    padding: 20px;
}

.head img{
    float: left;
    width: 40px;
    height: 40px;
    padding-left: 40px;
}

.head p{
    float: left;
    padding: 7px;
    width: 70%;
    font-weight: 500;
}

.portofolio{
    display: flex;
    width: 85%;
}

.portofolio img{
    height: 30%;
}

.portofolio p{
    padding: 5px 0 30px 20px;
}

.portofolio b{
    font-size: 40px;
}

.history{
    width: 50%;
}

.list{
    width: 40%;
    margin: auto;
}

.list ul{
    padding: 20px;
}

.list ul li{
    display: inline-block;
    margin: 3px;
    padding: 5px;
    background-color: whitesmoke;
    border: 1px solid black;
    border-radius: 10px;
}

.desc{
    display: flex;
    width: 92%;
}


.descprof{
    margin-right: 40px;
    text-align: center;
    padding: 0 5px 5px 5px;
    box-sizing: border-box;
}

.descprof p{
    font-size: 12px;
}

.descprof b{
    font-size: 12px;
}

.form{
    width: 100%;
    height: 300px;
    border: 2px solid black;
    border-radius: 10px;
    display: flex;
    padding: 5px;
    box-sizing: border-box;
}

.form b{
    font-size: 40px;
    padding: 34px 60px 0 20px;
}

.form p{
    font-size: 13px;
    font-weight: 500;
    color: #aaa;
}

#nama input,#email input{
    border: none;
    padding: 10px;
    border-radius: 5px;
}

textarea {
    height: 80px;
    padding: 5px 10px;
    box-sizing: border-box;
    border: none;
    border-radius: 6px;
    resize: none;
}

#submit{
    background-color: black;
    padding: 10px;
    font-size: 14px;
    font-weight: 500;
    border-radius: 10px;
    color: white;
    border: none;
}

#submit:hover{
    background-color: white;
    color: black;
}

.footer{
    height: 100px;
    margin-top: 100px;
}

.footer img{
    margin-left: 12%;
}

.footer ul{
    float: right;
    margin-right: 12%;
}

.footer ul li{
    display: inline;
    padding: 5px;
    color: black;
}

.footer ul li:hover{
    color: white;
    background-color: black;
    border-radius: 5px;
}

.footer p{
    padding-top: 20px;
    text-align: center;
}

.footerimg{
    padding: 5px;
    position: absolute;
    bottom: 0;
    right: 0;
    margin-right: 10px;
}
    </style>
    <body>
        <div class="container">
            <div class="head">
                <img src="picture/pep.png" alt="">
                <p>Rafi Ikhwan Purnama</p>
                <div class="nav">
                    <ul>
                        <a href=""><li>About</li></a>
                        <a href=""><li>Contact</li></a>
                        <a href=""><li id="black">View Work</li></a>
                    </ul>
                </div>
            </div>
            <div class="wrapper">
                <div class="wrap">
                    <div class="portofolio">
                        <img src="picture/ggl.png" alt="">
                        <p><b>Google</b><br><br>
                        Google LLC adalah sebuah perusahaan multinasional Amerika Serikat yang berkekhususan pada jasa dan produk Internet. Produk-produk tersebut meliputi teknologi pencarian, komputasi web, perangkat lunak, dan periklanan daring. Sebagian besar labanya berasal dari AdWords.</p>
                    </div>
                </div>
                <div class="wrap" style="display: flex;">
                    <div class="history">
                        <p><b>Sejarah Google</b><br><br>
                        Google didirikan oleh Larry Page dan Sergey Brin saat masih mahasiswa Ph.D. di Universitas Stanford. Mereka berdua memegang 16 persen saham perusahaan. Mereka menjadikan Google sebagai perusahaan swasta pada tanggal 4 September 1998. Pernyataan misinya adalah "mengumpulkan informasi dunia dan membuatnya dapat diakses dan bermanfaat oleh semua orang", dan slogan tidak resminya adalah "Don't be evil". Pada tahun 2006, kantor pusat Google pindah ke Mountain View, California. </p>
                    </div>
                    <div class="list">
                        <ul>
                            <li>UI DESIGN</li>
                            <li>UX DESIGN</li>
                            <li>PROTOTYPING</li>
                            <li>BRANDING</li>
                            <li>HTML/CSS</li>
                            <li>WIREFRAMING</li>
                            <li>INFORMATION ARCHITECTURE</li><br>
                            <li>USER RESEARCH</li>
                            <li>USER INTERVIEWS</li>
                            <li>LEADERSHIP</li>
                            <li>FIGMA</li>
                            <li>ADOBE SUIT</li>
                        </ul>
                    </div>
                </div>
                <div class="wrap">
                    <b> Deskripsi Google</b><br><br>
                    <div class="desc">
                        <div class="descprof">
                            <img src="picture/larry.png" alt="">
                            <b>Larry Page</b><br>
                            <p>CEO Google Inc.</p>
                        </div>
                        <p>Perusahaan ini diperkirakan mengoperasikan lebih dari satu juta server di beberapa pusat data di seluruh dunia dan memproses lebih dari satu miliar kueri pencarian dan sekitar 24 petabita data buatan pengguna setiap harinya. Pada bulan Desember 2012, Alexa menyebut google.com sebagai situs web paling banyak dikunjungi di dunia. Situs-situs Google dalam bahasa lain masuk peringkat 100 teratas, sebagaimana halnya situs milik Google seperti YouTube dan Blogger. Google menempati peringkat kedua di basis data ekuitas merek BrandZ. Dominasi pasarnya menuai kritik mengenai hak cipta, penyensoran, dan privasi. Pada tahun 2014, Google juga mendapat penghargaaan dari Business Indeed sebagai perusahaan yang memiliki merk paling bernilai.</p>
                    </div>
                </div>
                <div class="wrap">
                    <div class="form">
                        <b>Kirim Pesan</b>
                        <form action="">
                            <table align="center">
                                <tr>
                                    <td><p>Nama</p></td>
                                    <tr id="nama">
                                        <td><input type="text" placeholder="Masukkan Nama Anda"></td>
                                    </tr>
                                </tr>
                                <tr>
                                    <td><p>Email</p></td>
                                    <tr id="email">
                                        <td><input type="text" placeholder="Masukkan Email Anda"></td>
                                    </tr>
                                </tr>
                                <tr>
                                    <td><p>Pesan</p></td>
                                    <tr>
                                        <td><textarea name="pesan" id="" cols="50" rows="10" placeholder="Masukkan Pesan Anda"></textarea></td>
                                    </tr>
                                </tr>
                                <tr>
                                    <td><input id="submit" type="submit" value="Submit"></td>
                                </tr>
                            </table>
                        </form>
                    </div>
                </div>
            </div>
            <div class="footer">
                <img src="picture/Google.png" alt="">
                <ul>
                    <a href=""><li>Dribble</li></a>
                    <a href=""><li>LinkedIn</li></a>
                    <a href=""><li>About</li></a>
                    <a href=""><li>Contact</li></a>
                </ul>
                <div class="clear"></div>
                <p>Copyright @ 2022 Rafi Ikhwan Purnama All Right Reserved</p>
                <div class="footerimg">          
                    <img src="picture/linkedin.png" alt=""><br>
                    <img src="picture/dribble.png" alt="">
                </div>      
            </div>
        </div> 
    </body>
</html>
