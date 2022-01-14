# Selenium-BS4-Web-Scraping-SecondHandCars

Data collection script for price estimation model of second-hand vehicles via Selenium

<font size="2" face="Courier New" >
<table style='font-family:"Courier New", Courier, monospace; font-size:20%'>
  <thead>
    <tr style="text-align: right;font-size:10px">
      <th></th>
      <th>İlan No</th>
      <th>Plaka</th>
      <th>Motor No</th>
      <th>Şase No</th>
      <th>Model</th>
      <th>Model Yılı</th>
      <th>Kilometre</th>
      <th>Yakıt</th>
      <th>Kullanım Şekli</th>
      <th>Vites</th>
      <th>Kasa Tipi</th>
      <th>Motor Hacmi</th>
      <th>Motor Gücü</th>
      <th>Renk</th>
      <th>Tavan</th>
      <th>Kaput</th>
      <th>Sol Ön Çamurluk</th>
      <th>Sağ Ön Çamurluk</th>
      <th>Sol Ön Kapı</th>
      <th>Sağ Ön Kapı</th>
      <th>Sol Arka Kapı</th>
      <th>Sağ Arka Kapı</th>
      <th>Sol Arka Çamurluk</th>
      <th>Sağ Arka Çamurluk</th>
      <th>Bagaj</th>
      <th>Ön Tampon</th>
      <th>Arka Tampon</th>
      <th>Fiyat</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2.254140e+13</td>
      <td>54 AFY 347</td>
      <td>******</td>
      <td>NM0MXXTACMM******</td>
      <td>Ford Tourneo Courier 1.5 TDCI Titanium 100 Ps Kombi</td>
      <td>2021</td>
      <td>350.000</td>
      <td>Dizel</td>
      <td>Hafif Ticari</td>
      <td>Düz</td>
      <td>Kamyonet/2</td>
      <td>1.498 cc</td>
      <td>99 hp 73 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>350.00</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2.154140e+13</td>
      <td>54 YU 654</td>
      <td>******</td>
      <td>NM435600006******</td>
      <td>Fiat Egea 1.4 Fire Easy 95 Ps Sedan</td>
      <td>2019</td>
      <td>52.000</td>
      <td>Benzinli/LPG</td>
      <td>Binek</td>
      <td>Düz</td>
      <td>Sedan</td>
      <td>1.368 cc</td>
      <td>94 hp 70 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Değişmiş</td>
      <td>Değişmiş</td>
      <td>210.00</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2.154140e+13</td>
      <td>54 SC 170</td>
      <td>******</td>
      <td>NM426300006******</td>
      <td>Fiat Doblo 1.6 MultiJet Premio Plus Gri-Black 105 Ps Combi</td>
      <td>2017</td>
      <td>97.000</td>
      <td>Dizel</td>
      <td>Hafif Ticari</td>
      <td>Düz</td>
      <td>Kamyonet/2</td>
      <td>1.598 cc</td>
      <td>103 hp 77 kw</td>
      <td>Gri</td>
      <td>İyi</td>
      <td>Boyalı</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Boyalı</td>
      <td>Boyalı</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>200.00</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2.154140e+13</td>
      <td>41 V 0390</td>
      <td>******</td>
      <td>NM426300006******</td>
      <td>Fiat Doblo 1.3 MultiJet Maxi Plus ESP 90 Ps Cargo</td>
      <td>2017</td>
      <td>106.000</td>
      <td>Dizel</td>
      <td>Hafif Ticari</td>
      <td>Düz</td>
      <td>Kamyonet/2</td>
      <td>1.248 cc</td>
      <td>89 hp 66 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>165.00</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2.259140e+13</td>
      <td>34 BPP 562</td>
      <td>******</td>
      <td>NM435600006******</td>
      <td>Fiat Egea 1.3 MultiJet Easy 95 Ps Sedan</td>
      <td>2018</td>
      <td>148.000</td>
      <td>Dizel</td>
      <td>Binek</td>
      <td>Düz</td>
      <td>Sedan</td>
      <td>1.248 cc</td>
      <td>94 hp 70 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Değişmiş</td>
      <td>İyi</td>
      <td>Değişmiş</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Değişmiş</td>
      <td>Yarım Boyalı</td>
      <td>Değişmiş</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>205.00</td>
    </tr>
    <tr>
      <th>5</th>
      <td>2.254140e+13</td>
      <td>54 AGH 771</td>
      <td>******</td>
      <td>ZFA35600006******</td>
      <td>Fiat Egea Egea 1.4 Fire Easy Sedan</td>
      <td>2021</td>
      <td>250.000</td>
      <td>Benzinli</td>
      <td>Binek</td>
      <td>Düz</td>
      <td>Sedan</td>
      <td>cc</td>
      <td>hp kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>265.00</td>
    </tr>
    <tr>
      <th>6</th>
      <td>2.259140e+13</td>
      <td>59 AFA 167</td>
      <td>******</td>
      <td>NM000000000******</td>
      <td>Opel Insignia 1.6 CDTI EcoTEC Enjoy Otomatik 136 Ps Grand Sport</td>
      <td>2019</td>
      <td>59.000</td>
      <td>Dizel</td>
      <td>Binek</td>
      <td>Otomatik</td>
      <td>Sedan</td>
      <td>1.598 cc</td>
      <td>134 hp 100 kw</td>
      <td>Gri</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>519.00</td>
    </tr>
    <tr>
      <th>7</th>
      <td>2.235100e+13</td>
      <td>35 PDR 67</td>
      <td>******</td>
      <td>UU10SDMJG63******</td>
      <td>Dacia Dokker Dokker Kombi 1.5 DCI Stepway</td>
      <td>2019</td>
      <td>13.916</td>
      <td>Dizel</td>
      <td>Hafif Ticari</td>
      <td>Düz</td>
      <td>Kamyonet/2</td>
      <td>1.461 cc</td>
      <td>90 hp 66 kw</td>
      <td>Gri</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Değişmiş</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>247.00</td>
    </tr>
    <tr>
      <th>8</th>
      <td>2.222100e+13</td>
      <td>39 EP 744</td>
      <td>******</td>
      <td>VF1LBN00545******</td>
      <td>Renault Symbol Symbol Collection1.2 16V SL Collection</td>
      <td>2012</td>
      <td>189.000</td>
      <td>Benzinli</td>
      <td>Binek</td>
      <td>Düz</td>
      <td>Sedan</td>
      <td>1.149 cc</td>
      <td>75 hp 55 kw</td>
      <td>Gri</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Çizik</td>
      <td>Boyalı</td>
      <td>İyi</td>
      <td>Boyalı</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Çizik</td>
      <td>İyi</td>
      <td>Çizik</td>
      <td>İyi</td>
      <td>125.00</td>
    </tr>
    <tr>
      <th>9</th>
      <td>2.261110e+13</td>
      <td>61 JD 669</td>
      <td>******</td>
      <td>VF1KW98C557******</td>
      <td>Renault Kangoo Kangoo Multix 1.5 dCi Joy</td>
      <td>2017</td>
      <td>93.500</td>
      <td>Dizel</td>
      <td>Binek</td>
      <td>Düz</td>
      <td>Sedan</td>
      <td>1.461 cc</td>
      <td>90 hp 66 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>220.00</td>
    </tr>
    <tr>
      <th>10</th>
      <td>2.138140e+13</td>
      <td>34 DED 806</td>
      <td>******</td>
      <td>NM0MXXTACML******</td>
      <td>Ford Tourneo Courier Tourneo Courier 1.5 TDCi Delux</td>
      <td>2020</td>
      <td>5.077</td>
      <td>Dizel</td>
      <td>Ticari</td>
      <td>Düz</td>
      <td>Kamyonet/2</td>
      <td>1.498 cc</td>
      <td>75 hp 55 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>311.95</td>
    </tr>
    <tr>
      <th>11</th>
      <td>2.259140e+13</td>
      <td>39 BD 615</td>
      <td>******</td>
      <td>VF3ABFHZ0G8******</td>
      <td>Peugeot Bipper Bipper Tepee 1.3 HDi Comfort</td>
      <td>2016</td>
      <td>186.610</td>
      <td>Dizel</td>
      <td>Binek</td>
      <td>Düz</td>
      <td>SUV</td>
      <td>1.248 cc</td>
      <td>75 hp 55 kw</td>
      <td>Gri</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>143.00</td>
    </tr>
    <tr>
      <th>12</th>
      <td>2.210100e+13</td>
      <td>10 AK 420</td>
      <td>******</td>
      <td>WFOHXXWPDH9******</td>
      <td>Ford Focus Focus 1.6 Titanium</td>
      <td>2009</td>
      <td>212.000</td>
      <td>Benzinli/LPG</td>
      <td>Binek</td>
      <td>Düz</td>
      <td>Sedan</td>
      <td>1.596 cc</td>
      <td>100 hp 74 kw</td>
      <td>Gri</td>
      <td>İyi</td>
      <td>Değişmiş</td>
      <td>Boyalı</td>
      <td>İyi</td>
      <td>Boyalı</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Değişmiş</td>
      <td>İyi</td>
      <td>182.00</td>
    </tr>
    <tr>
      <th>13</th>
      <td>2.231100e+13</td>
      <td>31 KIU 61</td>
      <td>******</td>
      <td>NM422500006******</td>
      <td>Fiat Fiorino Fiorino Cargo 1.3 Multijet</td>
      <td>2017</td>
      <td>266.500</td>
      <td>Dizel</td>
      <td>Hafif Ticari</td>
      <td>Düz</td>
      <td>Panelvan</td>
      <td>1.248 cc</td>
      <td>75 hp 56 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>Yarım Boyalı</td>
      <td>Ezik</td>
      <td>Boyalı</td>
      <td>Ezik</td>
      <td>Boyalı</td>
      <td>135.00</td>
    </tr>
    <tr>
      <th>14</th>
      <td>2.231100e+13</td>
      <td>31 KIU 63</td>
      <td>******</td>
      <td>NM422500006******</td>
      <td>Fiat Fiorino Fiorino Cargo 1.3 Multijet</td>
      <td>2017</td>
      <td>273.000</td>
      <td>Dizel</td>
      <td>Hafif Ticari</td>
      <td>Düz</td>
      <td>Panelvan</td>
      <td>1.248 cc</td>
      <td>75 hp 56 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Ezik</td>
      <td>İyi</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>Ezik</td>
      <td>135.00</td>
    </tr>
    <tr>
      <th>15</th>
      <td>2.234140e+13</td>
      <td>34 AGK 493</td>
      <td>******</td>
      <td>NM426300006******</td>
      <td>Fiat Doblo 1.3 MultiJet Easy ESP 90 Ps Combi</td>
      <td>2017</td>
      <td>138.045</td>
      <td>Dizel</td>
      <td>Ticari</td>
      <td>Düz</td>
      <td>Kamyonet/2</td>
      <td>1.248 cc</td>
      <td>89 hp 66 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>258.00</td>
    </tr>
    <tr>
      <th>16</th>
      <td>2.234140e+13</td>
      <td>34 AGK 499</td>
      <td>******</td>
      <td>NM426300006******</td>
      <td>Fiat Doblo 1.3 MultiJet Easy ESP 90 Ps Combi</td>
      <td>2017</td>
      <td>111.538</td>
      <td>Dizel</td>
      <td>Ticari</td>
      <td>Düz</td>
      <td>Kamyonet/2</td>
      <td>1.248 cc</td>
      <td>89 hp 66 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Ezik</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Boyalı</td>
      <td>Boyalı</td>
      <td>İyi</td>
      <td>Ezik</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>260.00</td>
    </tr>
    <tr>
      <th>17</th>
      <td>2.234140e+13</td>
      <td>34 AGK 491</td>
      <td>******</td>
      <td>NM426300006******</td>
      <td>Fiat Doblo 1.3 MultiJet Easy ESP 90 Ps Combi</td>
      <td>2017</td>
      <td>175.263</td>
      <td>Dizel</td>
      <td>Ticari</td>
      <td>Düz</td>
      <td>Kamyonet/2</td>
      <td>1.248 cc</td>
      <td>89 hp 66 kw</td>
      <td>Beyaz</td>
      <td>İyi</td>
      <td>Değişmiş</td>
      <td>İyi</td>
      <td>Boyalı</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>Boyalı</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>İyi</td>
      <td>243.00</td>
    </tr>
  </tbody>
</table>
</font>
