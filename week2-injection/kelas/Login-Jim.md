# Soal Login Jim

**Description:** Log in with Jim's user account.

**Resource:** https://demo.owasp-juice.shop/#/score-board?categories=Injection&showDisabledChallenges=false

## Langkah Pengerjaan:
1. Mencari tahu email Jim dari email leak di User Reviews
2. Menemukan email `jim@juice-sh.op` pada user review produk Green Smoothie
3. Mencoba login dengan password random
4. Menggunakan upaya SQLi dengan menambahkan `'--` pada kolom email setelah email jim

![alt text](assets/image2.png)

Soal ini berhasil diselesaikan dikarenakan adanya tutorial yang membantu dalam menyelesaikan step-by-step