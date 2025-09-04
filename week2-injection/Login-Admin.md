# Soal Login Admin

**Description:** Log in with the administrator's user account.

**Resource:** https://demo.owasp-juice.shop/#/score-board?categories=Injection&showDisabledChallenges=false

## Langkah Pengerjaan:
1. Pergi ke Login Page via Account Button
2. Mencoba memasukkan `'` ke kolom email dan input apapun di kolom password
3. Setelah menekan `Login` muncul error `[object Object]`
4. Memeriksa network tab dan menemukan error ` message: 'SQLITE_ERROR: unrecognized token: "7815696ecbf1c96e6894b779456d330e"'`
5. Mencoba lagi dengan `' OR true` di kolom email
6. Mendapat error lagi, dengan penjelasan ` message: `SQLITE_ERROR: near "' AND password = '": syntax error``
7. Mencoba upaya lain dengan `' OR true--   `
8. Berhasil Login dengan akun `admin@juice-sh.op

![alt text](image1.png)

Soal ini berhasil diselesaikan dikarenakan adanya tutorial yang membantu dalam menyelesaikan step-by-step
