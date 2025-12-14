# ayaz_yemisler_ai_spark_hackthon

<table>
  <tr>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/b4d0acff-feb7-4046-92d1-bc45f216b60d" alt="Ekran Görüntüsü 1" width="100%">
    </td>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/f028cbf1-9423-4917-a584-16795f0541b6" alt="Ekran Görüntüsü 2" width="100%">
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/e36f1711-828f-4469-849d-40353cf98e57" alt="Ekran Görüntüsü 3" width="100%">
    </td>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/c80e1b3f-5ba6-4d52-90f8-9ad15acc5048" alt="Ekran Görüntüsü 4" width="100%">
    </td>
  </tr>
    <tr>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/39cb1be4-535e-42b3-a439-83a75d71a6ab" alt="Ekran Görüntüsü 5" width="100%">
    </td>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/2e832ecb-ddf8-436f-9408-9ac344949c58" alt="Ekran Görüntüsü 6" width="100%">
    </td>
  </tr>
</table>

### Model Performans Sonuçları

```text
==================================================
🚀 MODEL RESULTS (VERY STRICT FILTERING <5M)
RMSE: 167,378
R2 Score: 0.89770
==================================================

Error Distribution:
Mean Absolute Error: 85,248 TL
Median Absolute Error: 42,637 TL
Mean Percentage Error: 14.27%

Top 5 Worst Predictions:
       Actual     Predicted         Error     Abs_Error  Pct_Error
3549   4850000.0  2.923444e+06  1.926556e+06  1.926556e+06  39.722811
12895  3900000.0  2.029185e+06  1.870815e+06  1.870815e+06  47.969626
21273  4500000.0  2.734007e+06  1.765993e+06  1.765993e+06  39.244282
27272  3980000.0  2.431350e+06  1.548650e+06  1.548650e+06  38.910812
14116  3900000.0  2.395819e+06  1.504181e+06  1.504181e+06  38.568748
```

---

Model ve dosyalar çok büyük olduğu için GitHub'a yükleyemedik, Drive linkini iletiyorum:

[Google Drive - Proje Dosyaları](https://drive.google.com/file/d/1YTz2rLcUWV34WvWBE5bXKBUFE8MTiYoF/view?usp=sharing)

Ayrıca Gemma 4b fine-tune modelini boyut yüksek olduğu için koyamadık. Normalde 12b üzerinde çalışıyorduk ancak belki sizin donanımınızda 12b çalışmayabilir diye 4b'ye çevirdik. Kullanmanız için fine-tune script'ini çalıştırmanız gerekmektedir.

Ek olarak, ngrok ile bir tünel açtım ve kendi lokalimde 24 saat açık tutacağım. Test için aşağıdaki bağlantıdan erişebilirsiniz. İlk açılışta proxy sunucusu olduğu için site yavaş olabilir, lütfen birkaç dakika bekleyin.

[Canlı Test Ortamı (Ngrok Linki)](https://44be786d4e9c.ngrok-free.app/)

Ayrıca bir demo videosu çektim:

[Google Drive - Demo Videosu](https://drive.google.com/file/d/1x3sQlaMhfoDqyKhpiJXjdTn8whLfutZc/view?usp=sharing)

Bu değerli etkinlik için organizatörlere tekrardan teşekkür ederiz.

<p align="center">
  <img src="https://i.pinimg.com/originals/8f/68/cc/8f68ccb9df25696c03b5eff9f61e5efb.gif" alt="The End GIF" width="300">
</p>
