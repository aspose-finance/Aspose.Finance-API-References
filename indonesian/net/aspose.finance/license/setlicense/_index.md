---
title: License.SetLicense
second_title: Aspose.Finance untuk Referensi .NET API
description: License metode. Lisensi komponen.
type: docs
weight: 20
url: /id/net/aspose.finance/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Lisensi komponen.

```csharp
public void SetLicense(string licenseName)
```

### Perkataan

Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.

2. Folder yang berisi rakitan komponen Aspose.

3. Folder yang berisi rakitan panggilan klien.

4. Folder yang berisi rakitan entri (startup).

5. Sumber daya tertanam dalam perakitan panggilan klien.

**Catatan:**Di .NET Compact Framework, mencoba menemukan lisensi hanya di lokasi berikut:

1. Jalur eksplisit.

2. Sumber daya tertanam dalam perakitan panggilan klien.

2. Direktori kerja aplikasi java saat ini.

3. Folder yang berisi file JAR komponen Aspose.

4. Folder yang berisi file JAR panggilan klien.

### Contoh

Dalam contoh ini, upaya akan dilakukan untuk menemukan file lisensi bernama MyLicense.lic di folder yang berisi  komponen, di folder yang berisi rakitan pemanggil, di folder rakitan entri, lalu di sumber daya tertanam rakitan pemanggil.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

file jar komponen:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

Bisa berupa nama file lengkap atau pendek atau nama sumber daya tertanam. Gunakan string kosong untuk beralih ke mode evaluasi.

### Lihat juga

* class [License](../)
* ruang nama [Aspose.Finance](../../license/)
* perakitan [Aspose.Finance](../../../)

---

## SetLicense(Stream) {#setlicense}

Lisensi komponen.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran yang berisi lisensi. |

### Perkataan

Gunakan metode ini untuk memuat lisensi dari aliran.

### Contoh

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)

License license = new License();
license.setLicense(myStream);
```

### Lihat juga

* class [License](../)
* ruang nama [Aspose.Finance](../../license/)
* perakitan [Aspose.Finance](../../../)


