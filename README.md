# css-style
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>`substitute(Filename('', 'Page Title'), '^.', '\u&', '')`</title>
    <style type="text/css" media="all">
     h1,h4{
          text-align: center;
          background-color: lightblue;
          box-shadow: 2px 2px 2px 2px;
          font-family: Times New Roman;
          border-radius: 20px;
     }
     img {
          width: 100%;
          box-shadow: 2px 2px 2px 2px;
          height: 150%;
          border-radius: 20px;
     }
     table{
       border-collapse: collapse;
       border: 1px solid black;
       width: 100%;
       box-shadow: 4px 3px 4px 4px;
       text-align: center;
     }
    
     .1{font-family: Arial;}
     .2{font-size: medium;}
     .3{font-size: Large;}
     
     .4{font-size: 12px;}
     .u{text-decoration: underline;}
     .a{text-decoration: Overline;}
     .t{text-decoration: line-through;}
     .B{text-transform: uppercase;
       font-weight: normal;
     }
    </style>
  </head>
  <body>
    <img src="Gambar/Css.jpg" alt="" />
    <h1>Properti-properti yang digunakan pada CSS</h1>
    <p>Properti - properti yang digunakan pada css beserta dengan fungsi nya, jika ada yang kurang / kurang lengkap nanti akan ditambahkan.</p> 

     <p>Di post sebelum nya kita sudah membahas mengenai cara menggunakan css dengan penjelasan dan cara menggunakan nya. Jika belum membaca, silahkan baca disini</p>
     
     <p>Langsung praktekkan saja sob!</p>
     
     <h4>Contoh property dan value pada background</h4>
     <table border="1px">
       <tr>
         <th>Property</th>
         <th>Value</th>
         <th>Keterangan</th>
       </tr>
       <tr>
         <td>Background-image</td>
         <td>Url</td>
         <td>Alamat gambar yang sudah di Aploud</td>

       </tr>
       <tr>
         <td rowspan="4">Background-repeat</td>
         <td>Repeat</td>
         <td>Gambar di ulang dalam halaman</td>

       </tr>
       <tr>
         <td>Repeat-y</td>
         <td>Gambar diulang dalam sumbu y</td>
       </tr>
       <tr>    
         <td>Repeat-x</td>
         <td>Gambar diulang dalam sumbu x</td>
       </tr>
       <tr>
         <td>no-Repeat</td>
         <td>Gambar tidak diulang hanya muncul 1 gambar</td>
       </tr>
     </table>
  <h4>Contoh property dan value pada font</h4>
  <table border="1px">
       <tr>
         <th>Property</th>
         <th>Value</th>
         <th>Keterangan</th>
       </tr>
       <tr>
         <td>Font-family</td>
         <td>Arial</td>
         <td>Jenis font adalah <b class="1">Arial</td></b>
       </tr>
       <tr>
         <td rowspan="4">Font-size</td>
         <td>small</td>
         <td>Menampilkan ukuran huruf <small>Kecil</small></td>

       </tr>
       <tr>
         <td>Menengah</td>
         <td>Menampilkan ukuran huruf <b class="2">Menengah</b></td>
       </tr>
       <tr>    
         <td>Large</td>
         <td>Menampilkan ukuran huruf <b class="3">Besar</b></td>
       </tr>
       <tr>
         <td>12px</td>
         <td>Menampilkan huruf dengan ukuran <b class="4">12</b></td>
       </tr>
       <tr>
         <td rowspan="2">Font-style</td>
         <td>Normal</td>
         <td>Font normal</td>
         
       </tr>
       <tr>
         <td>Italic</td>
         <td>Font <i>miring</i></td>
         
       </tr>
       <tr>
         <td rowspan="3">Font-weight</td>
         <td>Normal</td>
         <td>Ketebalan font normal</td>
         
       </tr>
       <tr>
         <td>Bold</td>
         <td>Ketebalan font <b>Tebal</b></td>
         
       </tr>
       <tr>
         <td>100-900</td>
         <td>Ketebalan font dengan nilai dari 100-900</td>
         
       </tr>
     </table>
     <h4>Contoh property dan value pada text</h4>
     <table border="1px">
       <tr>
         <th>Property</th>
         <th>Value</th>
         <th>Keterangan</th>
       </tr>
       <tr>
         <td rowspan="5">Text-decoration</td>
         <td>none</td>
         <td>Menampilkan text asli</td></b>
       </tr>
       <tr>
         <td>Underline</td>
         <td>Menampilkan text bergaris <b class="u">Bawah</b></td>

       </tr>
       <tr>
         <td>Overline</td>
       <td>Menampilkan huruf bergaris <b class="a">Atas</b></td>
       </tr>
       <tr>    
         <td>Line-through</td>
         <td>Menampilkan huruf <b class="t">tercoret</b></td>
       </tr>
       <tr>
         <td>blink</td>
         <td>Menampilkan text <blink>berkedip</blink></td>
       </tr>
       <tr>
         <td>Text-transform</td>
         <td>uppercase</td>
         <td>Menampilkan text huruf <b class="B">Besar</b></td>
         
       </tr>
       <tr>
         <td rowspan="4">text-align</td>
         <td>left</td>
         <td>Font <i>miring</i></td>
         
       </tr>
       <tr>
         <td>Normal</td>
         <td>Ketebalan font normal</td>
         
       </tr>
       <tr>
         <td>Bold</td>
         <td>Ketebalan font <b>Tebal</b></td>
         
       </tr>
       <tr>
         <td>100-900</td>
         <td>Ketebalan font dengan nilai dari 100-900</td>
         
       </tr>
     </table>
     
  </body>
  
</html>