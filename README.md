# Fetal-health-prediction-using-machine-learning

##1) Mengumpulkan dataset
Data yang digunakan merupakan data tentang fetal health  yang berisi kumpulan data CTG yang digunakan untuk menilai kesehatan janin yang digunakan profesional kesehatan untuk mengambil tindakan untuk mencegah kematian anak dan ibu.  Data ini berjumlah 2126 yang terdiri dari 22 kolom dengan 21 fature dan 1 target. Data ini sendiri bersumber dari https://drive.google.com/file/d/1tNtzZ25FPpZ1-ooy9LNsgzNg8FCVdQ6Z/view

 Features :
 1. 'baseline value' FHR baseline (beats per minute)
 2. 'accelerations' Number of accelerations per second
 3. 'fetal_movement' Number of fetal movements per second
 4. 'uterine_contractions' Number of uterine contractions per second
 5. 'light_decelerations' Number of light decelerations per second
 6. 'severe_decelerations' Number of severe decelerations per second
 7. 'prolongued_decelerations' Number of prolonged decelerations per second
 8. 'abnormal_short_term_variability' Percentage of time with abnormal short
 term variability
 9. 'mean_value_of_short_term_variability' Mean value of short term variability
 10. 'percentage_of_time_with_abnormal_long_term_variability' Percentage of
 time with abnormal long term variability
 11. 'mean_value_of_long_term_variability' Mean value of long term variability
 12. 'histogram_width' Width of FHR histogram
 13. 'histogram_min' Minimum (low frequency) of FHR histogram
 14. 'histogram_max' Maximum (high frequency) of FHR histogram
 15. 'histogram_number_of_peaks' Number of histogram peaks
 16. 'histogram_number_of_zeroes' Number of histogram zeros
 17. 'histogram_mode' Histogram mode
 18. 'histogram_mean' Histogram mean
 19. 'histogram_median' Histogram median
 20. 'histogram_variance' Histogram variance
 21. 'histogram_tendency' Histogram tendency

 Target :
 1. 'fetal_health' Tagged as 1 (Normal), 2 (Suspect) and 3 (Pathological)
