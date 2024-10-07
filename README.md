<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">



       <style>

body {
    background: black;
}

#posisi2 {
    position: absolute;
    top: 17%;
    left: 19%;
}

#posisi2.hover {
    position: absolute;
    top: -100%;
    left: 1%;
}


#posisi3 {
    position: absolute;
    top: -50%;
    left: 17.5%;
}

.contact {
    position: absolute;
    top: 91.3%;
    left: 120%;
    text-decoration: none;
    font-size: 12px;
    font-weight: bold;
    transition: 0.5s;
    width: 300px;
    color: darkblue;
}

.contact:hover {
    color: red;
    transition: 0.5s;
}

.contact:active {
    color: lime;
    transition: 0s;
}

#background1 {
    padding: 200px 190px;
    background: url('https://k.top4top.io/p_32019b48d0.jpg');
    background-size: cover;
    background-position: center;
    border: 2px solid transparent;
}

#background2 {
    position: absolute;
    top: 0%;
    left: 80%;
    padding: 200px 250px;
    background: white;
    border: 2px solid white;
}

#penghalang {
    position: absolute;
    top: 0%;
    left: 0%;
    padding: 200px 153px;
    background: transparent;
    border: 2px solid transparent;
}








#gambar {
    position: absolute;
    top: 7%;
    left: 29%;
    padding: 32px 38px;
    border-radius: 100px;
    background: url('https://h.top4top.io/p_3183e8hbg0.jpg ');
    background-size: cover;
    color: transparent;
    border: 2px solid transparent;
}

#gambar.hover {
    position: absolute;
    top: 182.8%;
    left: 154.09%;
    z-index: 1;
}

#gambar.hover1 {
    background: url('https://h.top4top.io/p_3183e8hbg0.jpg ');
    background-size: cover;
}

#gambar.hover2 {
    background: url('https://i.top4top.io/p_3183dwps91.jpg');
    background-size: cover;
}

#gambar.hover3 {
    background: url('https://j.top4top.io/p_318314aap2.jpg');
    background-size: cover;
}

#gambar.hover4 {
    background: url('https://c.top4top.io/p_3184xqptp0.jpg');
    background-size: cover;
}

#gambar.hover5 {
    background: url('https://h.top4top.io/p_3184koz5h0.jpg');
    background-size: cover;
    background-repeat: no-repeat;
}

#gambar.hover6 {
    background: url('https://l.top4top.io/p_3187370u70.jpg');
    background-size: cover;
}

#gambar.hover7 {
    background: url('https://b.top4top.io/p_3197wq3z61.jpg');
    background-size: cover;
}

#gambar.hover8 {
    background: url('https://a.top4top.io/p_3197cs83t0.jpg');
    background-size: cover;
}

#gambar.hover9 {
    background: url('https');
    background-size: cover;
}

#gambar.hover10 {
    background: url('https');
    background-size: cover;
}

#gambar.hover11 {
    background: url('https');
    background-size: cover;
}

#gambar.hover12 {
    background: url('https');
    background-size: cover;
}

#pilihgambar1 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https://h.top4top.io/p_3183e8hbg0.jpg');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;
}

#pilihgambar2 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https://i.top4top.io/p_3183dwps91.jpg');
    background-size: cover;
    border: 2px solid black; 
    border-radius: 100px;
}

#pilihgambar3 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https://j.top4top.io/p_318314aap2.jpg');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;
}

#pilihgambar4 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https://c.top4top.io/p_3184xqptp0.jpg');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;
}

#pilihgambar5 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https://h.top4top.io/p_3184koz5h0.jpg');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;
}

#pilihgambar6 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https://l.top4top.io/p_3187370u70.jpg');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;    
}

#pilihgambar7 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https://b.top4top.io/p_3197wq3z61.jpg');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;
}

#pilihgambar8 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https://a.top4top.io/p_3197cs83t0.jpg');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;    
}

#pilihgambar9 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;
}

#pilihgambar10 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;    
}

#pilihgambar11 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;
}

#pilihgambar12 {
    padding: 40px 48px;
    margin-left: 40px;
    background: url('https');
    background-size: cover;
    border: 2px solid black;
    border-radius: 100px;    
}







#login {
    position: absolute;
    top: 0%;
    left: 60%;
    width: 300px;
    font-size: 25px;
    font-weight: bold;
    padding: 12px 40px;
    color: black;
    border: 2px solid transparent;
    background: transparent;
}

#text {
    position: absolute;
    top: 30%;
    left: 54%;
    padding: 5px 120px;
    text-align: left;
    border: 2px solid transparent;
    background: transparent;
    outline: none;
}

#username {
    position: absolute;
    top: 25%;
    left: 54%;
    padding: 5px 120px;
    font-weight: bold;
    border: 2px solid transparent;
    background: transparent;
}

#garis1 {
    position: absolute;
    top: 34%;
    left: 84%;
    height: 1px;
    width: 190px;
    background: grey;
    border: 2px solid transparent;
}

#output1 {
    position: absolute;
    top: 27.5%;
    left: 6.2%;
    font-size: 17px;
    height: 20px;
    width: 250px;
    text-align: center;
    background: transparent;
    border: 2px solid transparent;
    font-weight: bold;
    font-family: roboto;
    color: white;
}

#pw {
    position: absolute;
    top: 55%;
    left: 54%;
    padding: 5px 120px;
    font-weight: bold;
    border: 2px solid transparent;
    background: transparent;
}

#textpw {
    position: absolute;
    top: 60%;
    left: 84%;
    height: 18px;
    width: 194px;
    text-align: left;
    border: 2px solid transparent;
    background: white;
    outline: none;
}

#garis2 {
    position: absolute;
    top: 64%;
    left: 84%;
    height: 1px;
    width: 190px;
    background: grey;
    border: 2px solid transparent;
}

#tekslanjut {
    position: absolute;
    top: -200%;
    left: 30%;
    background: transparent;
    color: transparent;
    border: 2px solid transparent;
    outline: none;
}


#birth {
    position: absolute;
    top: 40%;
    left: 70%;
    width: 200px;
    padding: 5px;
    font-weight: bold;
    border: 2px solid transparent;
    background: transparent;
}

#textbirth {
    position: absolute;
    top: 45%;
    left: 84%;
    height: 18px;
    width: 194px;
    text-align: left;
    border: 2px solid transparent;
    background: white;
    outline: none;
}

#garis3 {
    position: absolute;
    top: 49%;
    left: 84%;
    height: 1px;
    width: 190px;
    background: grey;
    border: 2px solid transparent;
}

#output2 {
    position: absolute;
    top: 32%;
    left: 6.2%;
    font-size: 17px;
    height: 20px;
    width: 250px;
    text-align: center;
    background: transparent;
    border: 2px solid transparent;
    font-weight: bold;
    font-family: roboto;
    color: white;
}













#tombolubah {
    position: absolute;
    top: 89.6%;
    left: 84%;
    padding: 7px 12px;
    border-radius: 50px;
    background: blueviolet;
    color: white;
    font-size: 11px;
    display: flex;
    text-align: center;
    border: 2px solid black;
    transition: 1s;
}

#tombolubah:hover {
    box-shadow: 0px 0px 10px 4px aqua;
    transition: 1s;
}

#tombolubah.hover1 {
    position: absolute;
    top: 270.6%;
    left: 56%;
    z-index: 2;
    box-shadow: 0 0 0 0;
    border: 2px solid transparent;
}


#enter1 {
    position: absolute;
    top: 89.6%;
    left: 175%;
    padding: 7px 30px;
    border-radius: 50px;
    background: blueviolet;
    color: white;
    font-size: 11px;
    display: flex;
    text-align: center;
    border: 2px solid black;
    transition: 1s;
}

#enter2 {
    position: absolute;
    top: 89.6%;
    left: 175%;
    padding: 7px 30px;
    border-radius: 50px;
    background: blueviolet;
    color: white;
    font-size: 11px;
    display: flex;
    text-align: center;
    border: 2px solid black;
    transition: 1s;
}

#peringatan {
    display: none;
    position: absolute;
    top: 66.7%;
    left: 82.5%;
    font-weight: bold;
    text-align: left;
    background: transparent;
    border: 2px solid transparent;
    width: 200px;
}

#peringatan2 {
    display: none;
    position: absolute;
    top: 66.7%;
    left: 82.5%;
    font-weight: bold;
    text-align: left;
    background: transparent;
    border: 2px solid transparent;
    width: 250px;
    color: red;
}


#fpw {
    position: absolute;
    top: -100%;
    left: -100%;
}










#pubah {
    display: none;
}

#pubah.hover {
    position: fixed;
    top: 63%;
    margin-left: 40px;
    font-size: 17px;
    background: transparent;
    border: 2px solid transparent;
    width: 300px;
    height: 20px;
    font-weight: bold;
    text-align: left;
    z-index: 3;
}

#pilihbg {
    display: none;
}

#pilihbg.hover {
    position: fixed;
    top: 60%;
    left: -0.3%;
    width: 120%;
    height: 40%;
    border: 2px solid transparent;
    z-index: 3;
}

#close {
    display: none;
}

#close.hover {
    position: fixed;
    top: 62.5%;
    left: 94%;
    padding: 10px 16px;
    border: 1px solid black;
    font-size: 25px;
    transition: 1s;
    z-index: 3;
}

#closebg {
    display: none;
}

#closebg.hover {
    position: fixed;
    top: 0%;
    left: 0%;
    width: 100%;
    height: 60%;
    color: transparent;
    background: transparent;
    transition: 1s;
    border: 2px solid transparent;
    z-index: 3;
}

#close:hover {
    color: red;
    border: 1px solid red;
    transition: 0.3s;
    box-shadow: 0px 0px 10px 3px red;
}

#close:active {
    box-shadow: 0px 0px 10px 2px lime;
    color: lime;
    transition: 0s;
}

#scroll {
    display: none;
}

#scroll.hover {
    position: fixed;
    top: 76%;
    left: 1.5%;
    overflow-x: scroll;
    overflow-y: hidden;
    width: 96%;
    height: 30%;
    z-index: 3;
}

#gabungkanscroll {
display: flex;
}

#pilihgambar1.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar2.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar3.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar4.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar5.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar6.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar7.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar8.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar9.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar10.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar11.hover {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}

#pilihgambar12.hover   {
    background: url('');
    display: inline-block;
  width: 1em;
  height: 1em;
  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='none' stroke='%23000' stroke-dasharray='24' stroke-dashoffset='24' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 11l6 6l10 -10'%3E%3Canimate fill='freeze' attributeName='stroke-dashoffset' dur='0.4s' values='24;0'/%3E%3C/path%3E%3C/svg%3E");
  background-color: currentColor;
  -webkit-mask-image: var(--svg);
  mask-image: var(--svg);
  -webkit-mask-repeat: no-repeat;
  mask-repeat: no-repeat;
  -webkit-mask-size: 100% 100%;
  mask-size: 100% 100%;
  transition: 1s;
}


























#posisinewbg {
    display: none;
    position: absolute;
    top: 25%;
    left: 15%;
}

#posisinewbg.hover {
  color: transparent;
}

#newbg {
    width: 900px;
    height: 380px;
    background: grey;
    border-radius: 30px;
    color: transparent;
    border: 2px solid black;
    opacity: 0.3;
}

#tatakan {
    position: absolute;
    top: -12.3%;
    left: 44.2%;
    padding: 42px 48px;
    border-radius: 100px;
    background: grey;
    color: transparent;
    border: 2px solid transparent;
}



#tulisan1 {
    position: absolute;
    top: 14%;
    left: 3%;
    font-size: 15px;
    color: white;
    border: 2px solid transparent;
    background: transparent;
    outline: none;
}



#tulisan2 {
    position: absolute;
    top: 14%;
    left: 15.35%;
    font-size: 15px;
    color: white;
    text-align: left;
    border: 2px solid transparent;
    background: transparent;
    outline: none;
}

#tulisan3 {
    position: absolute;
    top: 18.5%;
    left: 3.35%;
    font-size: 15px;
    color: white;
    text-align: left;
}

#tulisan4 {
    font-size: 14px;
    color: white;
    text-align: left;
    border: 2px solid transparent;
    background: transparent;
    outline: none;  
    width: 16px;
}

#tulisan4.hover {
    width: 8px;
}

#penghalang2 {
    position: absolute;
    top: -1%;
    left: -1%;
    padding: 180px 500px;
    background: transparent;
    color: transparent;
    border: 2px solid transparent   ;
    z-index: 1;
}
    </style>





</head>
<body>









































 
<div translate="no" id="posisi2">
    <button id="gambar">.</button>
    <button id="background1">.</button>
    <button id="background2">.</button>
    <a href="https://wa.me/081218451096" class="contact">have problem? click to contact me</a>  
    <button id="login">SIGN UP</button>
    <input type="text" id="text" placeholder="fill your name">


    <button id="username">username</button>
    <hr id="garis1">    
    <input type="text" id="output1">
    <input type="text" id="output2">

    <hr id="garis3">    
    <input type="number" placeholder="fill your age now" id="textbirth">
    <button id="birth">your age now</button>
    <button id="peringatan2"></button>

    <button id="penghalang">.</button>
    <input type="submit" id="tombolubah" value="change picture" onclick="tombolubah">

    <input type="submit" id="enter2" value="confirm">
    <input type="submit" id="enter1" value="confirm">
    <button type="subit" id="peringatan">*passsword incorrect</button>
    <p id="fpw"></p>
    <input type="text" id="tekslanjut">

    


    <button id="pw">password</button>
    <input translate="no" type="password" id="textpw" placeholder="fill the password">
    <hr id="garis2">
    



</div>


<button id="pilihbg" type="submit">.</button>
<button id="close" type="submit">X</button>
<button id="pubah">SELECT YOUR PHOTO PROFILE</button>
<button id="closebg" type="submit">.</button>

<div id="scroll">
<nav id="gabungkanscroll">
<button id="pilihgambar1">.</button>
<button id="pilihgambar2">.</button>
<button id="pilihgambar3">.</button>
<button id="pilihgambar4">.</button>
<button id="pilihgambar5">.</button>
<button id="pilihgambar6">.</button>
<button id="pilihgambar7">.</button>
<button id="pilihgambar8">.</button>
<button id="pilihgambar9">.</button>
<button id="pilihgambar10">.</button>
<button id="pilihgambar11">.</button>
<button id="pilihgambar12">.</button>
</nav>
</div>


<nav id="posisi3">
<input id="bayangan1">
<input id="bayangan2">
<input id="bayangan3">
<input id="bayangan4">
<input id="bayangan5">
<input id="bayangan6">
<input id="bayangan7">
<input id="bayangan8">
<input id="bayangan9">
<input id="bayangan10">
<input id="bayangan11">
<input id="bayangan12">



</nav>



<div id="posisinewbg">
<button id="newbg">.</button>
<button id="tatakan">.</button>
<input id="tulisan1" value="Happy birthday,"><input id="tulisan2">   
<button id="penghalang2">.</button>
<p id="tulisan3">
Selamat ulang tahun yang ke<input id="tulisan4"> tahun
<br>semoga kamu diberikan umur yang panjang dan kesehatan selalu 
<br>serta bisa menjadi orang yang berguna baik agama,
<br>negara dan bagi kedua orang tua kamu amin.
<br>btw jangan lupa bersyukur ya atas apa yang tuhan
<br>telah berikan kepada kamu baik ilmu maupun kesehatan 
<br>lalu ucapkan terimakasih kepada kedua orang tuamu karena telah
<br>berjuang melahirkan dan membesarkan kamu hingga saat ini
<br>
<br>
<br>message from ~p
</p>

</div>




























<script>
    ///pw///
    var peringatan = document.getElementById('peringatan')
    var peringatan2 = document.getElementById('peringatan2')
    var textpw = document.getElementById('textpw')
    var fpw = document.getElementById('fpw')
    var text = document.getElementById('text')
    var textbirth = document.getElementById('textbirth')
    var enter1 = document.getElementById('enter1')
    var enter2 = document.getElementById('enter2')
    var tekslanjut = document.getElementById('tekslanjut')
    var posisinewbg = document.getElementById('posisinewbg')
    var gambar = document.getElementById('gambar')
    var output1 = document.getElementById('output1')
    var output2 = document.getElementById('output2')
    var posisi2 = document.getElementById('posisi2')
    var tombolubah = document.getElementById('tombolubah');
    var tulisan4 = document.getElementById('tulisan4')
     
      ///harus isi password///
      enter1.addEventListener('click', function() {
    if (textpw.value === '') {
        peringatan2.textContent = 'you must fill the password';
        peringatan2.style.display = 'inline';
        peringatan.style.display = 'none';
        textpw.focus();
    }
    });


    ///harus isi umur///
    enter1.addEventListener('click', function() {
    if (textbirth.value === '') {
        peringatan2.textContent = 'you must fill the birthday';
        peringatan2.style.display = 'inline';
        peringatan.style.display = 'none';
        textbirth.focus();
    }
    });


     ///harus isi username///
     enter1.addEventListener('click', function() {
    if (text.value === '') {
        peringatan2.textContent = 'you must fill username';
        peringatan2.style.display = 'inline';
        peringatan.style.display = 'none';
        text.focus();
    }
    });
    

textpw.addEventListener('input', function(){
fpw.textContent = textpw.value;
});


enter1.addEventListener('click', function(){
setTimeout(function() {
peringatan.style.display = 'inline';
peringatan2.style.display = 'none';
}, 2000);
peringatan.style.color = 'red';
textpw.value = '';
enter2f();
});


enter1.addEventListener('mouseover', function(){
enter1.style.border = '2px solid red';
enter1.style.transition = '0s';
});


enter1.addEventListener('mouseout', function(){
enter1.style.border = '2px solid black';
enter1.style.transition = '0s';
});

function enter2f(){
    if (fpw.textContent === '1' && text.value.length > 0 && Number(textbirth.value) > 0) {
    enter1.style.display = 'none';
    peringatan.textContent = 'password correct';
    peringatan.style.color = 'lime';
    enter2.style.border = '2px solid lime';
    enter2.style.transition = '0s';
    tekslanjut.focus();
    peringatan2.style.display = 'none';
    }
}
   


///klik enter 2///
enter2.addEventListener('click', function(){
    posisinewbg.style.display = 'inline';
    gambar.classList.add('hover');
    posisi2.classList.add('hover');
    tombolubah.classList.add('hover1');
    tombolubah.style.transition = '0s';
    if (Number(textbirth.value) < 10) {
    tulisan4.classList.add('hover');}
});


///klik untuk masuk///
tekslanjut.addEventListener('keydown', function(tekslanjutklik){
if (tekslanjutklik.key === 'Enter') {
posisinewbg.style.display = 'inline';
    gambar.classList.add('hover');
    posisi2.classList.add('hover');
    tombolubah.classList.add('hover1');
    tombolubah.style.transition = '0s';
    if (Number(textbirth.value) < 10) {
        tulisan4.classList.add('hover');}
}
});

///klik enter 1///
textpw.addEventListener('keydown', function(klik1){
if (klik1.key === 'Enter') {
    klik1.preventDefault();
    enter1.click();
    enter1.style.border = '2px solid red'
    enter1.style.transition = '0s'
    setTimeout(function() {
    enter1.style.border = '2px solid black';
    enter1.style.transition = '0s'
    }, 500);
}
});


</script>






<script>
    ///ubah gambar///
    var scroll = document.getElementById('scroll')
    var tombolubah = document.getElementById('tombolubah')
    var pilihbg = document.getElementById('pilihbg')
    var close = document.getElementById('close')
    var closebg = document.getElementById('closebg')
    var pilihgambar1 = document.getElementById('pilihgambar1')
    var bayangan1 = document.getElementById('bayangan1')

    tombolubah.addEventListener('click', function(){
    pilihbg.style.display = 'inline';
    pilihbg.classList.add('hover');
    close.style.display = 'inline';
    close.classList.add('hover');
    scroll.style.display = 'inline';
    scroll.classList.add('hover');
    pubah.style.display = 'inline';
    pubah.classList.add('hover');
    closebg.style.display = 'inline';
    closebg.classList.add('hover');
    });

    ///tutup///
    close.addEventListener('click', function(){
    pilihbg.style.display = 'none';
    close.style.display = 'none';
    scroll.style.display = 'none';
    pubah.style.display = 'none';
    closebg.style.display = 'none';
    });

    closebg.addEventListener('click', function() {
    pilihbg.style.display = 'none';
    close.style.display = 'none';
    scroll.style.display = 'none';
    pubah.style.display = 'none';
    closebg.style.display = 'none';
    });



</script>

<script>
    ///untuk memindahkan jalur///
    var text = document.getElementById('text')
    var textpw = document.getElementById('textpw')
    var textbirth = document.getElementById('textbirth')

    text.addEventListener('keydown', function(p1){
        if (p1.key === 'Enter') {
        textbirth.focus();
        }
        if (p1.key === 'ArrowDown') {
        textbirth.focus();
        }

    });

    textbirth.addEventListener('keydown', function(p2){
        if (p2.key === 'Enter'){
        textpw.focus();
        }
        if (p2.key === 'ArrowUp') {
        text.focus();
        }
        if (p2.key === 'ArrowDown') {
        textpw.focus();
        }
    });

    textpw.addEventListener('keydown', function(p3) {
    if (p3.key === 'ArrowUp') {
    textbirth.focus();
    }
    });

</script>








<script>
    ///display untuk teks///
var text = document.getElementById('text')
var output1 = document.getElementById('output1')
var textbirth = document.getElementById('textbirth')
var output2 = document.getElementById('output2')
var angka = document.getElementById('angka')
var tulisan2 = document.getElementById('tulisan2')
var tulisan4 = document.getElementById('tulisan4')
var tulisan5 = document.getElementById('tulisan5')
var peringatan = document.getElementById('peringatan')
var peringatan2 = document.getElementById('peringatan2')
var enter1 = document.getElementById('enter1')


text.addEventListener('input', function(){
output1.value = text.value;
tulisan2.value = text.value;
tulisan5.value = text.value;
});



textbirth.addEventListener('input', function() {
    output2.value = textbirth.value;
    tulisan4.value = textbirth.value;

    if (Number(textbirth.value) > 30){
        textbirth.value = '';
        output2.value = '';
        peringatan2.style.display = 'inline';
        peringatan2.textContent = '*cant enter numbers more than 30';
        peringatan.style.display = 'none';
    }

    jk();
    jk1();
    jk2();
    jk3();
    jk4();
    jk5();
    jk6();
    jk7();
    jk8();
    jk9();
    jk10();
    jk11();
    jk12();
    jk13();
    jk14();
    jk15();
    jk16();
    jk17();
    jk18();
    jk19();
    jk20();
    jk21();
    jk22();
    jk23();
    jk24();
    jk25();
    jk26();
    jk27();
    jk28();
    jk29();
    jk30();
    jk31();
    jk32();
    jk33();
    jk34();
    jk35();
    jk36();
    jk37();
    jk38();
    jk39();
    jk40();
});

function jk() {
    if (output2.value === '') {
        output2.value = '';
    }
}

function jk1() {
    if (output2.value === '1') {
        output2.value = '1st';
    }
}

function jk2() {
    if (output2.value === '2') {
        output2.value = '2nd';
    }
}

function jk3() {
    if (output2.value === '3') {
        output2.value = '3rd';
    }
}

function jk4() {
    if (output2.value === '4') {
        output2.value = '4th';
    }
}

function jk5() {
    if (output2.value === '5') {
        output2.value = '5th';
    }
}

function jk6() {
    if (output2.value === '6') {
        output2.value = '6th';
    }
}

function jk7() {
    if (output2.value === '7') {
        output2.value = '7th';
    }
}

function jk8() {
    if (output2.value === '8') {
        output2.value = '8th';
    }
}

function jk9() {
    if (output2.value === '9') {
        output2.value = '9th';
    }
}

function jk10() {
    if (output2.value === '10') {
        output2.value = '10th';
    }
}

function jk11() {
    if (output2.value === '11') {
        output2.value = '11th';
    }
}

function jk12() {
    if (output2.value === '12') {
        output2.value = '12th';
    }
}

function jk13() {
    if (output2.value === '13') {
        output2.value = '13th';
    }
}

function jk14() {
    if (output2.value === '14') {
        output2.value = '14th';
    }
}

function jk15() {
    if (output2.value === '15') {
        output2.value = '15th';
    }
}

function jk16() {
    if (output2.value === '16') {
        output2.value = '16th';
    }
}

function jk17() {
    if (output2.value === '17') {
        output2.value = '17th';
    }
}

function jk18() {
    if (output2.value === '18') {
        output2.value = '18th';
    }
}

function jk19() {
    if (output2.value === '19') {
        output2.value = '19th';
    }
}

function jk20() {
    if (output2.value === '20') {
        output2.value = '20th';
    }
}

function jk21() {
    if (output2.value === '21') {
        output2.value = '21st';
    }
}

function jk22() {
    if (output2.value === '22') {
        output2.value = '22nd';
    }
}

function jk23() {
    if (output2.value === '23') {
        output2.value = '23rd';
    }
}

function jk24() {
    if (output2.value === '24') {
        output2.value = '24th';
    }
}

function jk25() {
    if (output2.value === '25') {
        output2.value = '25th';
    }
}

function jk26() {
    if (output2.value === '26') {
        output2.value = '26th';
    }
}

function jk27() {
    if (output2.value === '27') {
        output2.value = '27th';
    }
}

function jk28() {
    if (output2.value === '28') {
        output2.value = '28th';
    }
}

function jk29() {
    if (output2.value === '29') {
        output2.value = '29th';
    }
}

function jk30() {
    if (output2.value === '30') {
        output2.value = '30th';
    }
}

function jk31() {
    if (output2.value === '31') {
        output2.value = '31st';
    }
}

function jk32() {
    if (output2.value === '32') {
        output2.value = '32nd';
    }
}

function jk33() {
    if (output2.value === '33') {
        output2.value = '33rd';
    }
}

function jk34() {
    if (output2.value === '34') {
        output2.value = '34th';
    }
}

function jk35() {
    if (output2.value === '35') {
        output2.value = '35th';
    }
}

function jk36() {
    if (output2.value === '36') {
        output2.value = '36th';
    }
}

function jk37() {
    if (output2.value === '37') {
        output2.value = '37th';
    }
}

function jk38() {
    if (output2.value === '38') {
        output2.value = '38th';
    }
}

function jk39() {
    if (output2.value === '39') {
        output2.value = '39th';
    }
}

function jk40() {
    if (output2.value === '40') {
        output2.value = '40th';
    }
}

</script>

<script>
     var gambar = document.getElementById('gambar') 
    var gambar1 = document.getElementById('pilihgambar1') 
    var gambar2 = document.getElementById('pilihgambar2') 
    var gambar3 = document.getElementById('pilihgambar3') 
    var gambar4 = document.getElementById('pilihgambar4') 
    var gambar5 = document.getElementById('pilihgambar5') 
    var gambar6 = document.getElementById('pilihgambar6') 
    var gambar7 = document.getElementById('pilihgambar7') 
    var gambar8 = document.getElementById('pilihgambar8') 
    var gambar9 = document.getElementById('pilihgambar9') 
    var gambar10 = document.getElementById('pilihgambar10') 
    var gambar11 = document.getElementById('pilihgambar11') 
    var gambar12 = document.getElementById('pilihgambar12') 
    var bayangan1 = document.getElementById('bayangan1') 
    var bayangan2 = document.getElementById('bayangan2') 
    var bayangan3 = document.getElementById('bayangan3') 
    var bayangan4 = document.getElementById('bayangan4') 
    var bayangan5 = document.getElementById('bayangan5') 
    var bayangan6 = document.getElementById('bayangan6') 
    var bayangan7 = document.getElementById('bayangan7') 
    var bayangan8 = document.getElementById('bayangan8') 
    var bayangan9 = document.getElementById('bayangan9') 
    var bayangan10 = document.getElementById('bayangan10') 
    var bayangan11 = document.getElementById('bayangan11') 
    var bayangan12 = document.getElementById('bayangan12') 
    var scroll = document.getElementById('scroll')

    gambar1.addEventListener('click', function() {
    gambar.classList.add('hover1');
    bayangan1.focus();

    gambar1.classList.add('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.remove('hover');


    gambar.classList.remove('hover2')
    gambar.classList.remove('hover3')
    gambar.classList.remove('hover4')
    gambar.classList.remove('hover5')
    gambar.classList.remove('hover6')
    gambar.classList.remove('hover7')
    gambar.classList.remove('hover8')
    gambar.classList.remove('hover9')
    gambar.classList.remove('hover10')
    gambar.classList.remove('hover11')
    gambar.classList.remove('hover12')
    });




    ///
    gambar2.addEventListener('click', function() {

    gambar.classList.add('hover2');
    bayangan2.focus();
    gambar1.classList.remove('hover');
    gambar2.classList.add('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.remove('hover');


    gambar.classList.remove('hover3')
    gambar.classList.remove('hover4')
    gambar.classList.remove('hover5')
    gambar.classList.remove('hover6')
    gambar.classList.remove('hover7')
    gambar.classList.remove('hover8')
    gambar.classList.remove('hover9')
    gambar.classList.remove('hover10')
    gambar.classList.remove('hover11')
    gambar.classList.remove('hover12')
    });





    ///
    gambar3.addEventListener('click', function() {
    bayangan3.focus();
    gambar1.classList.remove('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.add('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.remove('hover');




    gambar.classList.add('hover3')
    gambar.classList.remove('hover4')
    gambar.classList.remove('hover5')
    gambar.classList.remove('hover6')
    gambar.classList.remove('hover7')
    gambar.classList.remove('hover8')
    gambar.classList.remove('hover9')
    gambar.classList.remove('hover10')
    gambar.classList.remove('hover11')
    gambar.classList.remove('hover12')
    });




    ///
    gambar4.addEventListener('click', function() {
    bayangan4.focus();
    gambar1.classList.remove('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.add('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.remove('hover');



    gambar.classList.add('hover4');
    gambar.classList.remove('hover5')
    gambar.classList.remove('hover6')
    gambar.classList.remove('hover7')
    gambar.classList.remove('hover8')
    gambar.classList.remove('hover9')
    gambar.classList.remove('hover10')
    gambar.classList.remove('hover11')
    gambar.classList.remove('hover12')
    });





    ///
    gambar5.addEventListener('click', function() {
    bayangan5.focus();
    
    gambar1.classList.remove('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.add('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.remove('hover');




    gambar.classList.add('hover5');
    gambar.classList.remove('hover6')
    gambar.classList.remove('hover7')
    gambar.classList.remove('hover8')
    gambar.classList.remove('hover9')
    gambar.classList.remove('hover10')
    gambar.classList.remove('hover11')
    gambar.classList.remove('hover12')
    });




    ///
    gambar6.addEventListener('click', function() {
    bayangan6.focus();
    gambar1.classList.remove('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.add('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.remove('hover');




    gambar.classList.add('hover6');
    gambar.classList.remove('hover7')
    gambar.classList.remove('hover8')
    gambar.classList.remove('hover9')
    gambar.classList.remove('hover10')
    gambar.classList.remove('hover11')
    gambar.classList.remove('hover12')
    });




    ///
    gambar7.addEventListener('click', function() {
    bayangan7.focus();
    gambar1.classList.remove('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.add('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.remove('hover');




    gambar.classList.add('hover7');
    gambar.classList.remove('hover8')
    gambar.classList.remove('hover9')
    gambar.classList.remove('hover10')
    gambar.classList.remove('hover11')
    gambar.classList.remove('hover12')
    });




    ///
    gambar8.addEventListener('click', function() {
    bayangan8.focus();
    gambar1.classList.remove('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.add('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.remove('hover');




    gambar.classList.add('hover8');
    gambar.classList.remove('hover9')
    gambar.classList.remove('hover10')
    gambar.classList.remove('hover11')
    gambar.classList.remove('hover12')
    });




    ///
    gambar9.addEventListener('click', function() {
    bayangan9.focus();
    gambar1.classList.remove('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.add('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.remove('hover');




    gambar.classList.add('hover9');
    gambar.classList.remove('hover10')
    gambar.classList.remove('hover11')
    gambar.classList.remove('hover12')
    });




    ///
    gambar10.addEventListener('click', function() {
    bayangan10.focus();
    gambar1.classList.remove('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.add('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.remove('hover');




    gambar.classList.add('hover10');
    gambar.classList.remove('hover11')
    gambar.classList.remove('hover12')
    });




    ///
    gambar11.addEventListener('click', function() {
    bayangan11.focus();
    gambar1.classList.remove('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.add('hover');
    gambar12.classList.remove('hover');




    gambar.classList.add('hover11');
    gambar.classList.remove('hover12')
    });





    ///
    gambar12.addEventListener('click', function() {
    bayangan12.focus();
    gambar1.classList.remove('hover');
    gambar2.classList.remove('hover');
    gambar3.classList.remove('hover');
    gambar4.classList.remove('hover');
    gambar5.classList.remove('hover');
    gambar6.classList.remove('hover');
    gambar7.classList.remove('hover');
    gambar8.classList.remove('hover');
    gambar9.classList.remove('hover');
    gambar10.classList.remove('hover');
    gambar11.classList.remove('hover');
    gambar12.classList.add('hover');



    gambar.classList.add('hover12');
    });



    bayangan1.addEventListener('keydown', function(gambar100) {
    if (gambar100.key === 'ArrowRight') {
    gambar2.click();
    bayangan2.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan2.addEventListener('keydown', function(gambar200) {
    if (gambar200.key === 'ArrowRight') {
    gambar3.click();
    bayangan3.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan3.addEventListener('keydown', function(gambar300) {
    if (gambar300.key === 'ArrowRight') {
    gambar4.click();
    bayangan4.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan4.addEventListener('keydown', function(gambar400) {
    if (gambar400.key === 'ArrowRight') {
    gambar5.click();
    bayangan5.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan5.addEventListener('keydown', function(gambar500) {
    if (gambar500.key === 'ArrowRight') {
    gambar6.click();
    bayangan6.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan6.addEventListener('keydown', function(gambar600) {
    if (gambar600.key === 'ArrowRight') {
    gambar7.click();
    bayangan7.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan7.addEventListener('keydown', function(gambar700) {
    if (gambar700.key === 'ArrowRight') {
    gambar8.click();
    bayangan8.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan8.addEventListener('keydown', function(gambar800) {
    if (gambar800.key === 'ArrowRight') {
    gambar9.click();
    bayangan9.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan9.addEventListener('keydown', function(gambar900) {
    if (gambar900.key === 'ArrowRight') {
    gambar10.click();
    bayangan10.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan10.addEventListener('keydown', function(gambar1000) {
    if (gambar1000.key === 'ArrowRight') {
    gambar11.click();
    bayangan11.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan11.addEventListener('keydown', function(gambar1100) {
    if (gambar1100.key === 'ArrowRight') {
    gambar12.click();
    bayangan12.focus();
    scroll.scrollBy({
    left: 150,
    behavior: 'smooth'
    });
    }
    });

    bayangan12.addEventListener('keydown', function(gambar1200) {
    if (gambar1200.key === 'ArrowLeft') {
    gambar11.click();
    bayangan11.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });

    bayangan11.addEventListener('keydown', function(gambar100) {
    if (gambar100.key === 'ArrowLeft') {
    gambar10.click();
    bayangan10.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });

      bayangan10.addEventListener('keydown', function(gambar900) {
    if (gambar900.key === 'ArrowLeft') {
    gambar9.click();
    bayangan9.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });

  bayangan9.addEventListener('keydown', function(gambar800) {
    if (gambar800.key === 'ArrowLeft') {
    gambar8.click();
    bayangan8.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });

  bayangan8.addEventListener('keydown', function(gambar700) {
    if (gambar700.key === 'ArrowLeft') {
    gambar7.click();
    bayangan7.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });

  bayangan7.addEventListener('keydown', function(gambar600) {
    if (gambar600.key === 'ArrowLeft') {
    gambar6.click();
    bayangan6.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });

  bayangan6.addEventListener('keydown', function(gambar500) {
    if 
    (gambar500.key === 'ArrowLeft') {
    gambar5.click();
    bayangan5.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });

  bayangan5.addEventListener('keydown', function(gambar400) {
    if (gambar400.key === 'ArrowLeft') {
    gambar4.click();
    bayangan4.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });

  bayangan4.addEventListener('keydown', function(gambar300) {
    if (gambar300.key === 'ArrowLeft') {
    gambar3.click();
    bayangan3.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });

  bayangan3.addEventListener('keydown', function(gambar200) {
    if (gambar200.key === 'ArrowLeft') {
    gambar2.click();
    bayangan2.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });

  bayangan2.addEventListener('keydown', function(gambar1000) {
    if (gambar1000.key === 'ArrowLeft') {
    gambar1.click();
    bayangan1.focus();
    scroll.scrollBy({
    left: -150,
    behavior: 'smooth'
    });
    }
    });




</script>




    
</body>
</html>
