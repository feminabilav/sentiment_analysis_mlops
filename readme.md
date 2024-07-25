# Restaurant Review Sentiment Analysis Deployment

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [❤️ vs 😡: Sentiment Analysis 📝](https://www.kaggle.com/datasets/mohidabdulrehman/vs-sentiment-analysis?resource=download) |
| Masalah | Bagaimana cara mengetahui kalimat review untuk sebuah restoran merupakan review yang baik atau buruk? |
| Solusi machine learning | Digunakan analisis sentimen menggunakan NLP untuk melakukan klasifikasi review baik atau buruk |
| Metode pengolahan | Pengolahan data digunakan dengan membuat seluruh kalimat menjadi lower case |
| Arsitektur model | Arsitektur model yang diguanakan adalah dengen Embedding dan GlobalAveragePooling1D |
| Metrik evaluasi | Metrik yang digunakan untuk mengevaluasi performa model adalah dengan Area Under Curve (AUC), False Positive, True Positive, False Negative, True Negative, dan Accuracy |
| Performa model | Didapat AUC 82%, Accuracy 73%, False Positive sebanyak 16, True Positive sebanyak 63, False Negative sebanyak 34, dan True Negative sebanyak 71  |
| Opsi deployment | Digunakan railway sebagai opsi deployment model |
| Web app | [cc-model](https://lovehatedetection-production.up.railway.app/v1/models/cc-model/metadata)|
| Monitoring | Metrik durasi scraping pada target berada antara ~0.2s sampai ~5s. Sementara metrik scrape_samples_post_metric_relabeling, scrape_samples_scraped, scrape_series_added, dan up stagnan pada nilai 0  |
