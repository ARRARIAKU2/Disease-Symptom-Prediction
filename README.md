# Ensemble-Disease-Symptom-Prediction

Model dibuat berdasarkan arsitektur awal MLP yang telah didesain sebelumnya. Kemudian beberapa model baru dibuat dengan sedikit modifikasi dari model awal. 
Terdapat tiga model baru yang kemudian digabungkan membentuk model baru dengan averaging layer. Adapun skema yang dilakukan ialah seperti berikut

<p align="center">
  <img src="https://github.com/ARRARIAKU2/Disease-Symptom-Prediction/blob/josua/Documentations/Ensemble/MLP%20ENSEMBLE%20(1).png?raw=true" alt="Sublime's custom image"/>
</p>

Percobaan berulang dengan model yang sama kadang memberikan hasil evaluasi yang berbeda-beda. Tiga model yang dibuat memberikan hasil yang beragam dan apabila dicoba ulang hasilnya akan berbeda pula.
Dengan penerapan enemble nilai yang berbeda antar model dapat diaverage yang menutupi kelemahan dari satu model dengan model lainnya sehingga memberikan hasil yang lebih baik ketika dibuat model baru. 

| Model | Precision | Accuracy | Recall | F1-Score |
| :---: | :---: | :---: | :---: | :---: |
| MLP | 97.0528 | 97.0528 |  97.0528 |  96.2129 |
| MLP2 | 85.8739 | 85.8739 |  85.8739 |  84.0146 |
| MLP3 | 97.3577 | 97.3577 |  97.3577 |  97.3433|
| Ensemble | 99.3902 | 99.3902 |  99.3902 |  99.3971 |






