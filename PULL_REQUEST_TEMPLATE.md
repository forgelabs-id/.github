# type(scope): ringkasan perubahan

## Summary

<!-- Satu paragraf: apa yang berubah dan masalah apa yang diselesaikan. Sebutkan bila
     ada bagian yang sengaja tidak disentuh. -->

Closes #

## Scope

<!-- Angka nyata: jumlah file dan baris. Tabel dipakai kalau membantu. -->

## Behaviour yang perlu diperhatikan reviewer

<!-- Hal yang tidak terlihat dari diff: default yang berubah, kegagalan yang disengaja,
     urutan yang harus dijaga, nilai yang digenerate saat render. -->

-
## Verifikasi

<!-- Perintah yang benar-benar dijalankan beserta hasilnya. Tabel kosong berarti belum diuji.

     | Perintah | Hasil |
     | --- | --- | -->

| Perintah | Hasil |
| --- | --- |
|  |  |

## Cara deploy setelah merge

<!-- Hapus bagian ini kalau tidak ada langkah manual. Urutkan perintahnya. -->

## Follow-up di luar MR ini

<!-- Pekerjaan yang sengaja ditunda, beserta alasannya. -->

-
## Checklist

- [ ] Commit testable sendiri, tanpa squash
- [ ] Tidak ada kredensial, token, atau key yang ikut ter-commit
- [ ] Variabel konfigurasi baru terdokumentasi di tempat ia dibaca
- [ ] Test gagal sebelum perubahan dan lulus sesudahnya
- [ ] Urutan rollout disebut kalau menyentuh lebih dari satu service
- [ ] Review read-only terhadap dokumen desain, bila dokumennya sudah beku
