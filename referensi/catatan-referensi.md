# CATATAN REFERENSI — TUGAS AKHIR

Navigasi Mobil Otonom: Integrasi Segmentasi Visual dan GPS untuk Manuver di Jalan Raya ITS

---

## Barfoot2017

- **Judul:** State Estimation for Robotics
- **Penulis:** Timothy D. Barfoot
- **Tahun:** 2017
- **Path PDF:** referensi/high/Timothy D. Barfoot - State Estimation for Robotics-Cambridge University Press (2017).pdf
- **Kategori:** Kalman Filter
- **Abstrak:** Buku teks estimasi keadaan untuk robotika; cakupan luas dari Kalman Filter hingga continuous-time estimation.
- **Metode Utama:** Formal matematik dengan aplikasi praktis pada robotika.
- **Hasil Kunci:** Joseph stabilized form; sifat simetris dan positive semi-definite dari matriks kovarians.
- **Dataset:** Tidak ada (buku teks).
- **Kontribusi ke TA:** Referensi utama — Joseph stabilized form untuk implementasi Kalman Filter, konsep inovasi/residual, dan sifat positive semi-definite.
- **Bab yang menggunakan:** 2
- **Gambar penting:** Diagram KF, notasi matriks.

---

## Becker2024KF

- **Judul:** Kalman Filter from the Ground Up (3rd ed.)
- **Penulis:** Alex Becker
- **Tahun:** 2024
- **Path PDF:** referensi/high/KF book sample.pdf
- **Kategori:** Kalman Filter
- **Abstrak:** Buku tutorial komprehensif Kalman Filter dari dasar hingga multivariate dan Unscented Kalman Filter.
- **Metode Utama:** Contoh numerik, ilustrasi visual langkah demi langkah.
- **Hasil Kunci:** Siklus prediksi-koreksi KF; gain Kalman yang adaptif terhadap perubahan kualitas data.
- **Dataset:** Tidak ada (buku teks).
- **Kontribusi ke TA:** Referensi utama rumus KF — derivasi prediksi, koreksi, dan perhitungan Kalman Gain.
- **Bab yang menggunakan:** 2
- **Gambar penting:** Siklus prediksi-koreksi Kalman Filter.

---

## Bloesch2012StateEstimation

- **Judul:** State Estimation for Legged Robots — Consistent Fusion of Leg Kinematics and IMU
- **Penulis:** Michael Bloesch et al.
- **Tahun:** 2012
- **Path PDF:** referensi/high/Bloesch-Siegwart_State__IMU_2012.pdf
- **Kategori:** Kalman Filter
- **Abstrak:** Observability Constrained EKF (OC-EKF) untuk fusi kinematika encoder dan IMU pada robot berkaki.
- **Metode Utama:** Observability Constrained Extended Kalman Filter.
- **Hasil Kunci:** Estimasi posisi footholds dan pose badan secara simultan.
- **Dataset:** Simulasi dan eksperimen robot quadrupedal.
- **Kontribusi ke TA:** Transformasi kerangka sensor ke kerangka dunia, rotasi data IMU ke koordinat global.
- **Bab yang menggunakan:** 3
- **Gambar penting:** Diagram framework fusi sensor.

---

## BouGhosn2024ITSC

- **Judul:** The Hybrid Extended Bicycle: A Simple Model for High Dynamic Vehicle Trajectory Planning
- **Penulis:** Agapius Bou Ghosn et al.
- **Tahun:** 2024
- **Path PDF:** referensi/high/The Hybrid Extended Bicycle - A Simple Model for High Dynamic Vehicle Trajectory Planning.pdf
- **Kategori:** Navigasi
- **Abstrak:** Model hybrid extended bicycle untuk perencanaan trajektori kendaraan berdinamika tinggi.
- **Metode Utama:** Kinematic bicycle model dengan perluasan hybrid.
- **Hasil Kunci:** Model valid untuk percepatan lateral **a_y < 0,5μg**; asumsi tanpa slip.
- **Dataset:** Simulasi.
- **Kontribusi ke TA:** Model kinematika bicycle sebagai dasar perencanaan trajektori; batas akurasi model kinematik.
- **Bab yang menggunakan:** 2, 3
- **Gambar penting:** Diagram model bicycle.

---

## Dahdah2025

- **Judul:** Discretization of Linear Systems using the Matrix Exponential
- **Penulis:** Steven Dahdah, James Richard Forbes
- **Tahun:** 2025
- **Path PDF:** referensi/high/Discretization of Linear Systems using the Matrix Exponential.pdf
- **Kategori:** Kalman Filter
- **Abstrak:** Diskritisasi sistem linier kontinu ke diskrit menggunakan matrix exponential.
- **Metode Utama:** Matrix exponential untuk diskritisasi.
- **Hasil Kunci:** Lebih akurat dibandingkan pendekatan Euler orde pertama.
- **Dataset:** Tidak ada (paper teori).
- **Kontribusi ke TA:** Diskritisasi sistem kontinu ke diskrit untuk implementasi Kalman Filter diskrit.
- **Bab yang menggunakan:** 2
- **Gambar penting:** —

---

## Dharma2025PerformanceEvaluation

- **Judul:** Performance Evaluation of DeepLabV3 Plus for Road Segmentation in iCar ITS
- **Penulis:** Krisna Pramudya Dharma, Rudy Dikairono, Djoko Purwanto
- **Tahun:** 2025
- **Path PDF:** referensi/past/Performance_Evaluation_of_DeeplabV3_Plus_for_Road_Segmentation_in_iCar_ITS.pdf
- **Kategori:** Segmentasi
- **Abstrak:** Evaluasi DeepLabV3 Plus dengan backbone ResNet-50, ResNet-101, dan MobileNetV3-Large untuk segmentasi jalan di lingkungan ITS malam hari.
- **Metode Utama:** Supervised learning pada Google Colab, inferensi pada laptop.
- **Hasil Kunci:** ResNet-50: mIoU 76,45%, PA 99,64%; MobileNetV3-Large: mIoU 74,96%, FPS 29,13.
- **Dataset:** Dataset lokal ITS (iCar), kondisi malam hari.
- **Kontribusi ke TA:** Baseline segmentasi jalan di ITS; perbandingan langsung dengan InternImage (mIoU 0,9574 vs 0,7645).
- **Bab yang menggunakan:** 1, 2, 4, 5
- **Gambar penting:** Tabel perbandingan backbone, hasil segmentasi visual.

---

## Jaikumar2022MaskRCNN

- **Judul:** Transfer Learning for Instance Segmentation of Waste Bottles using Mask R-CNN Algorithm
- **Penulis:** Punitha Jaikumar et al.
- **Tahun:** 2022
- **Path PDF:** FILE TIDAK DITEMUKAN
- **Kategori:** Segmentasi
- **Abstrak:** Transfer learning untuk instance segmentation botol limbah menggunakan Mask R-CNN.
- **Metode Utama:** Transfer learning, Mask R-CNN.
- **Hasil Kunci:** —
- **Dataset:** Dataset botol limbah.
- **Kontribusi ke TA:** Hanya untuk gambar perbandingan teknik computer vision di Bab 2 (semantik vs instance segmentation vs deteksi vs klasifikasi).
- **Bab yang menggunakan:** 2
- **Gambar penting:** Perbandingan segmentasi semantik, klasifikasi, deteksi objek, dan instance segmentation.

---

## Lee2022ResilientNavigation

- **Judul:** A Resilient Navigation and Path Planning System for High-speed Autonomous Race Cars
- **Penulis:** Daegyu Lee et al.
- **Tahun:** 2022
- **Path PDF:** referensi/medium/Hybrid_ResilientNavigation_Planning_IndyAutonomousChallenge.pdf
- **Kategori:** Lokalisasi / Navigasi
- **Abstrak:** Sistem navigasi resilien untuk Indy Autonomous Challenge; multi-sensor fusion Kalman Filter dengan wall-following navigation.
- **Metode Utama:** Multi-sensor fusion Kalman Filter + wall-following navigation.
- **Hasil Kunci:** Finish top 4 dari 9 tim; sistem mampu mencegah kegagalan lokalisasi saat GPS terdegradasi (multipath, drift).
- **Dataset:** Indianapolis Motor Speedway.
- **Kontribusi ke TA:** Studi kasus kegagalan GPS di lingkungan nyata (IAC); mekanisme fusi sensor meredam multipath/drift GPS.
- **Bab yang menggunakan:** 1, 5
- **Gambar penting:** Diagram sistem navigasi resilien.

---

## Li2013AdaptivePreview

- **Judul:** An Adaptive Preview Path Tracker for Off-Road Autonomous Driving
- **Penulis:** Xiaohui Li et al.
- **Tahun:** 2013
- **Path PDF:** referensi/high/Anadaptivepreviewpathtrackerforoff-roadautonomousdriving.pdf
- **Kategori:** Navigasi
- **Abstrak:** Algoritma path tracking dengan adaptive preview distance untuk kendaraan off-road.
- **Metode Utama:** Roadside sampling, adaptive preview, fungsi kurvatur, fungsi utilitas 3-suku.
- **Hasil Kunci:** Algoritma `Find_Feasible_Trajectories` untuk pemilihan trajektori optimal.
- **Dataset:** Simulasi 14-DOF.
- **Kontribusi ke TA:** Algoritma pemilihan trajektori; representasi jalan dalam body-frame kendaraan.
- **Bab yang menggunakan:** 2
- **Gambar penting:** Representasi body-frame, kurva feasible trajectories.

---

## Li2024GaussianPSM

- **Judul:** Obstacle Avoidance Trajectory Planning for Autonomous Vehicles on Urban Roads Based on Gaussian Pseudo-Spectral Method
- **Penulis:** Zhenfeng Li et al.
- **Tahun:** 2024
- **Path PDF:** referensi/medium/Local_TrajectoryOptimization_GaussPSM_LaneChange.pdf
- **Kategori:** Navigasi
- **Abstrak:** Model kontrol optimal untuk perencanaan jalur lokal menggunakan Gauss pseudo-spectral method.
- **Metode Utama:** Gaussian Pseudo-Spectral Method (GPM).
- **Hasil Kunci:** Lebih efisien dibandingkan Legendre PSM dan Shooting method.
- **Dataset:** Simulasi lane-changing.
- **Kontribusi ke TA:** Referensi gambar model kinematika kendaraan untuk Bab 2.
- **Bab yang menggunakan:** 2
- **Gambar penting:** Model kinematika kendaraan.

---

## MOU2025130770

- **Judul:** MV-Guided Deformable Convolution Network for Compressed Video Action Recognition with P-Frames
- **Penulis:** Yuting Mou et al.
- **Tahun:** 2025
- **Path PDF:** FILE TIDAK DITEMUKAN
- **Kategori:** Segmentasi
- **Abstrak:** Deformable convolution untuk video action recognition.
- **Metode Utama:** Deformable convolution.
- **Hasil Kunci:** —
- **Dataset:** Video action recognition.
- **Kontribusi ke TA:** Hanya untuk gambar perbandingan konvolusi tradisional vs deformable convolution di Bab 2.
- **Bab yang menggunakan:** 2
- **Gambar penting:** Perbandingan konvolusi tradisional dan Deformable Convolution.

---

## NIMA2000WGS84

- **Judul:** Department of Defense World Geodetic System 1984 (TR8350.2, 3rd ed.)
- **Penulis:** NIMA (National Imagery and Mapping Agency)
- **Tahun:** 2000
- **Path PDF:** referensi/high/NGA.STND.0036_1.0.0_WGS84.pdf
- **Kategori:** Standar
- **Abstrak:** Standar resmi WGS84 — definisi datum, ellipsoid, gravitasi, dan transformasi datum.
- **Metode Utama:** Standar teknis geodetik.
- **Hasil Kunci:** Definisi parameter ellipsoid WGS84 (semi-major axis, flattening, dll.).
- **Dataset:** Tidak ada.
- **Kontribusi ke TA:** Konversi latitude/longitude ke koordinat ENU (East-North-Up) menggunakan parameter ellipsoid WGS84.
- **Bab yang menggunakan:** 3
- **Gambar penting:** Tabel parameter ellipsoid WGS84.

---

## NVIDIATensorRT

- **Judul:** NVIDIA TensorRT Quick Start Guide v8.6.1
- **Penulis:** NVIDIA Corporation
- **Tahun:** 2024
- **Path PDF:** [online] archive.docs.nvidia.com
- **Kategori:** Optimasi
- **Abstrak:** Dokumentasi resmi pipeline optimasi TensorRT untuk inferensi deep learning.
- **Metode Utama:** PyTorch → ONNX → TensorRT engine.
- **Hasil Kunci:** Engine teroptimasi untuk inferensi pada GPU NVIDIA.
- **Dataset:** Tidak ada.
- **Kontribusi ke TA:** Pipeline konversi model PyTorch ke TensorRT engine untuk akselerasi inferensi.
- **Bab yang menggunakan:** 3
- **Gambar penting:** Alur konversi model.

---

## Ondrus2020AutonomousCarsWork

- **Judul:** How Do Autonomous Cars Work?
- **Penulis:** Ján Ondruš, Eduard Kolla, Peter Vertaľ, Željko Šarić
- **Tahun:** 2020
- **Path PDF:** referensi/low/Kontekstual_AutonomousCars_IndustryOverview_Europe.pdf
- **Kategori:** Lainnya (review paper)
- **Abstrak:** Tinjauan komprehensif tentang cara kerja mobil otonom — sensor, pemrosesan data, dan pengambilan keputusan.
- **Metode Utama:** Literature review.
- **Hasil Kunci:** Arsitektur umum mobil otonom (sensor → persepsi → perencanaan → kontrol).
- **Dataset:** Tidak ada.
- **Kontribusi ke TA:** Justifikasi bahwa navigasi adalah komponen kunci dalam arsitektur mobil otonom.
- **Bab yang menggunakan:** 1
- **Gambar penting:** Diagram arsitektur mobil otonom.

---

## Philion2020LSS

- **Judul:** Lift, Splat, Shoot: Encoding Images from Arbitrary Camera Rigs by Implicitly Unprojecting to 3D
- **Penulis:** Jonah Philion, Sanja Fidler
- **Tahun:** 2020
- **Path PDF:** referensi/high/Lift, Splat, Shoot.pdf
- **Kategori:** Segmentasi / Navigasi
- **Abstrak:** Arsitektur end-to-end untuk ekstraksi Bird's-Eye View (BEV) dari multi-kamera; pipeline lift-splat-shoot.
- **Metode Utama:** Lift-Splat-Shoot — unproyeksi 2D ke 3D BEV.
- **Hasil Kunci:** Outperforms baseline pada BEV segmentation.
- **Dataset:** Data mengemudi nyata, multi-kota.
- **Kontribusi ke TA:** Konsep trajectory sampling pada BEV dan shooting trajektori untuk perencanaan.
- **Bab yang menggunakan:** 2
- **Gambar penting:** Pipeline LSS, hasil BEV segmentation.

---

## Rahiman2013GPSNavigation

- **Judul:** An Overview of Development GPS Navigation for Autonomous Car
- **Penulis:** Wan Rahiman, Zafariq Zainal
- **Tahun:** 2013
- **Path PDF:** referensi/medium/Global_GPS_IMU_Compass_AutonomousNavigation.pdf
- **Kategori:** Lokalisasi
- **Abstrak:** Ulasan perkembangan navigasi GPS untuk mobil otonom.
- **Metode Utama:** Literature review.
- **Hasil Kunci:** GPS memiliki ketergantungan signifikan pada lingkungan dan jumlah satelit yang terlihat.
- **Dataset:** Tidak ada.
- **Kontribusi ke TA:** Menjelaskan keterbatasan akurasi GPS sebagai justifikasi perlunya fusi sensor.
- **Bab yang menggunakan:** 1
- **Gambar penting:** Diagram sistem GPS navigation.

---

## Scaramuzza2006ICVS

- **Judul:** A Flexible Technique for Accurate Omnidirectional Camera Calibration and Structure from Motion
- **Penulis:** Davide Scaramuzza, Agostino Martinelli, Roland Siegwart
- **Tahun:** 2006
- **Path PDF:** referensi/high/ICVS06_scaramuzza.pdf
- **Kategori:** Kalibrasi
- **Abstrak:** Teknik fleksibel untuk kalibrasi kamera omnidirectional dengan single viewpoint.
- **Metode Utama:** Taylor series expansion, two-stage least-squares.
- **Hasil Kunci:** Kalibrasi akurat untuk FOV > 200°.
- **Dataset:** Papan catur (planar calibration pattern).
- **Kontribusi ke TA:** Paper inti — kalibrasi kamera untuk transformasi Bird's-Eye View.
- **Bab yang menggunakan:** 2, 3
- **Gambar penting:** Pola kalibrasi, rekonstruksi 3D.

---

## wang2023internimage

- **Judul:** InternImage: Exploring Large-Scale Vision Foundation Models with Deformable Convolutions
- **Penulis:** Wenhai Wang et al.
- **Tahun:** 2023
- **Path PDF:** referensi/high/InternImage.pdf
- **Kategori:** Segmentasi
- **Abstrak:** InternImage, CNN berskala besar dengan DCNv3 (Deformable Convolution v3); mencapai 65,4 mAP di COCO dan 62,9 mIoU di ADE20K.
- **Metode Utama:** Deformable Convolution v3 (DCNv3) sebagai operator konvolusi inti.
- **Hasil Kunci:** InternImage-H: 65,4 mAP (COCO), 62,9 mIoU (ADE20K), state-of-the-art di Mapillary Vistas.
- **Dataset:** ImageNet, COCO, ADE20K, Mapillary Vistas.
- **Kontribusi ke TA:** **Paper inti** — backbone segmentasi TA; model di-fine-tuning pada dataset lokal ITS.
- **Bab yang menggunakan:** 1, 2, 3, 4, 5
- **Gambar penting:** Arsitektur InternImage, perbandingan DCNv3 vs konvolusi reguler.

---

## Zazuli2024SensorFusion

- **Judul:** Sensor Fusion System for Localization of Autonomous Car
- **Penulis:** Moh. Ismarintan Zazuli et al.
- **Tahun:** 2024
- **Path PDF:** referensi/past/Sensor_Fusion_System_for_Localization_of_Autonomous_Car.pdf
- **Kategori:** Lokalisasi
- **Abstrak:** Integrasi GNSS + Wheel Odometry + IMU dengan Extended Kalman Filter untuk lokalisasi mobil otonom.
- **Metode Utama:** Extended Kalman Filter (EKF).
- **Hasil Kunci:** Mean error 0,43 m pada frekuensi 50 Hz.
- **Dataset:** Data uji iCar ITS.
- **Kontribusi ke TA:** Baseline lokalisasi EKF di lingkungan ITS; perbandingan langsung dengan hasil TA (RMSE TA: 0,173 m).
- **Bab yang menggunakan:** 1, 2, 5
- **Gambar penting:** Diagram blok fusi sensor, grafik estimasi posisi.

---

## zhou2022exploring

- **Judul:** Exploring TensorRT to Improve Real-Time Inference for Deep Learning
- **Penulis:** Yuxiao Zhou, Kecheng Yang
- **Tahun:** 2022
- **Path PDF:** referensi/high/Exploring_TensorRT_to_Improve_Real-Time_Inference_for_Deep_Learning.pdf
- **Kategori:** Optimasi
- **Abstrak:** Eksplorasi TensorRT — layer fusion, optimalisasi memori, dan kuantisasi INT8.
- **Metode Utama:** Layer fusion, FP16/INT8 quantization.
- **Hasil Kunci:** Layer fusion meningkatkan kecepatan 1,6×–2×; INT8 hingga 3,7× tanpa penurunan akurasi signifikan.
- **Dataset:** Berbagai model DNN.
- **Kontribusi ke TA:** **Paper inti** — justifikasi dan metodologi konversi model PyTorch ke TensorRT engine.
- **Bab yang menggunakan:** 1, 2, 4, 5
- **Gambar penting:** Pipeline optimasi TensorRT.

---

## Ringkasan Kategori

| Kategori | Referensi |
|---|---|
| **Segmentasi** | Dharma2025PerformanceEvaluation, wang2023internimage, Philion2020LSS, Jaikumar2022MaskRCNN, MOU2025130770 |
| **Lokalisasi** | Rahiman2013GPSNavigation, Lee2022ResilientNavigation, Zazuli2024SensorFusion |
| **Navigasi** | Li2024GaussianPSM, BouGhosn2024ITSC, Li2013AdaptivePreview, Philion2020LSS |
| **Kalman Filter** | Becker2024KF, Barfoot2017, Dahdah2025, Bloesch2012StateEstimation |
| **Kalibrasi** | Scaramuzza2006ICVS |
| **Optimasi** | zhou2022exploring, NVIDIATensorRT |
| **Standar** | NIMA2000WGS84 |
| **Lainnya** | Ondrus2020AutonomousCarsWork |

> **Catatan:** Philion2020LSS muncul di dua kategori (Segmentasi dan Navigasi) karena kontribusinya mencakup BEV segmentation (segmentasi) dan trajectory sampling (navigasi).
