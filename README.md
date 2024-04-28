@keyframes fanim {0% {posisi latar belakang: 0% 0%;}25% {posisi latar belakang: 100% 100%;} 50% {posisi latar belakang: 0% 100%;} 75% {posisi latar belakang: 50% 50%;} 100% {posisi latar belakang: 0% 0%;}}
body{background-color:#000;font-family:var(--gaya-font);padding: 20px 25px;-webkit-user-select: none; -ms-pilih-pengguna: tidak ada; pilih pengguna: tidak ada;} a{dekorasi teks: tidak ada;}
body::before{/*content:"\00A9 feltdream.id";*/color:white;content:"Instagram: @rayyarrr";opacity:.5;ukuran font:11px;posisi:tetap;bawah:25px ;kanan:25px;z-index:2}
#bodyblur{opacity:.3;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.3);transition:semua 1 kemudahan;}
#wallpaper{width:100%;height:100%;transform: scale(2);transition:semua kemudahan 1,7 detik;}
#beneranblur{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.3);-webkit-backdrop-filter:blur(0px); backdrop-filter:blur(0px);transition:semua 3 detik dengan mudah;}

@keyframes jj{0% {transformasi: skala(1.1);} 50% {transformasi: skala(1.2);} 100% {transformasi: skala(1.1);}}
@keyframes rts{dari {transform:scale(.1);} ke {transform:scale(1);}}
@keyframes rto{dari {transform:scale(1);} ke {transform:scale(1.1);}}
@keyframes aniopa{0% {transformasi: skala(1);} 50% {transformasi: skala(.75);} 100% {transformasi: skala(1);}}
@keyframes rtf{dari {transformasi: putar(0deg);} ke {transformasi: putar(360deg);}} @keyframes rt{dari {transformasi: skala(.9);/* transformasi: putar(-5deg); */} ke {transformasi: skala(1);/* transformasi: putar(5 derajat); */}}
@keyframes kont{0% {kiri:-1px; atas:-3px;} 50% {kiri:1px; atas:3px;} 100% {kiri:-1px; atas:-3 piksel;}}

blockquote{position:absolute;opacity:0;visibility:hidden;/*background:var(--warna-bg);border: 1px solid rgba(255, 255, 255, 0.5);border-radius:10px;box- bayangan: rgba(255,255,255, 0,3) 0px 7px 29px 0px;*/transformasi: skala(.1);transisi:semua .3s kemudahan;margin-kiri:0;margin-kanan:0;warna:#fff;teks-bayangan : 0px 2px 2px rgba(0, 0, 0, .8);/*filter latar belakang:blur(2px);*/}
blockquote{width:400px;text-align:left;line-height:1.3em;padding:0}
/*blockquote::before{content:attr(data-text);opacity:.7;font-family: sans-serif;position:absolute;left:8px;top:8px;min-width:15px;font-size :16px;perataan teks:tengah}*/
blockquote p{font-size:var(--ukuran-teks);font-weight:400;line-height:1.5em;transition:all .5s ease;margin-left:40px;margin-right:40px}
blockquote > .gaya4{margin-top:15px;font-family:var(--gaya-font3);ukuran font:16px !important;font-weight:400;color:#FF3E34}
blockquote > .gaya3{ukuran font:17px;berat font:700;perataan teks:tengah}
blockquote > .gaya2{ukuran font:15px;berat font:400}
blockquote > #pesan6, blockquote > #pesan7{text-align:center}
blockquote > #pesanAkhir2, blockquote > #pesanAkhir3{font-family:var(--gaya-font3);font-size:19px !important;}
blockquote > #pesanAkhir, blockquote > #pesanAkhir2, blockquote > #pesanAkhir3{text-align:center;position: absolute;opacity:0;transform: scale(.1);}
blockquote p:not(#opsL, #kalimat, #pesan3, #ketlanjut, .gaya2, .gaya4){display:none;}
blockquote > #opsL{text-align:right;font-size:12px;font-weight:400;line-height:0;margin-top:24px;color:white;opacity:0;}

#Tombol{position:relative;opacity:0;margin:0;display:flex;align-items:left;list-style:none;transform: scale(.1);transition:all 1s ease;}
#Tombol a{cursor:pointer;display:inline-flex;align-items:center; margin:0;margin:12px 0 12px 0;transisi:semua .2s kemudahan;padding:10px;garis besar:0;border: .7px solid #808080;border-radius:15px;line-height:15px;background:rgba( 0,0,0,.2);warna:#fff;ukuran font:13px;berat font:700;spasi putih:nowrap;overflow:hidden;box-shadow: rgba(255,255,255, 0,3) 0px 7px 29px 0px;z-indeks:1}
#Bn{margin:12px 0 12px 12px !penting}

#Konten{nama-animasi: tidak ada;durasi-animasi: 3 detik;jumlah-iterasi-animasi: tak terbatas;posisi:relatif;opasitas:0;margin-top:50px;lebar:100%;tinggi:180px;transisi:semua . kemudahan 7 detik;}
#Konten > *{display:flex;align-items:center;text-align:center;justify-content:center;margin-top:1px;}
.kumpulan > img{display:none;background: rgba(255, 255, 255, 0.7);box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(5px);-webkit-backdrop- filter: blur(5px);batas: 1px solid rgba(255, 255, 255, 0.3);radius batas: 10%;padding:10px;lebar:85px;tinggi:85px;margin-top:20px;}
#ftAwal > img{width:130px;height:130px;margin-bottom:50px;}

#fotolove img{transition:all .5s ease;width:75px;height:75px;padding:0;background:none}
#loveIn img{display:inline-flex;background:none;width:130px;height:130px;transition:all .3s ease;}
#ket, #ketlanjut{text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);ukuran font:17px;berat font:700;warna:putih}
#ket{margin-top:15px !important;font-size:12px;font-weight:400;opacity:.8}
#ketlanjut{text-align:right;margin-top:25px;font-size:11px;font-weight:400;opacity:0;transition:all .7s ease;}

@keyframes menyisakan {0% {transform: scale(1.0);} 100% {transform: scale(.9);}}
.lovein{width:40px;height:40px;background:#fff;border-radius:50%;padding:10px;font-size:30px;display:flex;align-items:center;text-align:center;justify -content:center;transition:all .3s kemudahan;}
.lovein:hover{transformasi: skala(.9);}

.swal2-modal > *{ukuran font:16px;}
.swal2-title{line-height:1.3em;font-size:17px;text-align:center;padding:15px 30px 0 30px;}
.swal2-timer-progress-bar-container > *{opacity:.7;background:#00B6FF;margin:0 2px}
.swal2-modal{background:#EAEAEA;box-shadow: 0 4px 30px rgba(255.255.255, 0.3);backdrop-filter: blur(2px);-webkit-backdrop-filter: blur(2px);border: 1px solid rgba (255, 255, 255, 0,3);radius batas: 8px;lebar maksimal:330px;atas:-60px;}
.swal2-styled.swal2-confirm, .swal2-styled.swal2-cancel{position: relative;background-color: #4839eb;color: #fff;border-radius:18px;z-index: 1;transition: semua 0,2 S;}

.fa-heart, .fa-heart-broken {opacity:.3;color:white;font-size: 20px;position: absolute;animation: heartMove linear 1;top: -10vh;z-index: 0;}
@keyframes heartMove {0%{transform: TranslateY(-10vh) ;} 100%{transform: TranslateY(100vh) ;}}
.sembunyi, #pesanditolak > *, #kado2, #kado3{display:none !important}
