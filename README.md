# Tugas Pertemuan 1

Nama    : Nur Azis Gimnastiar
NIM     : 1124160173
Kelas   : TI SE 24 Shift
Matkul  : Aplikasi Mobile

```dart
void main() {
  print ("Bursa Transfer");
  
  String playerName = ("Bradley Barcola");
  String previousClub = ("PSG");
  String newClub = ("Liverpool");
  int age = 24;
  double price = 123.0; // juta euro
  bool isOfficial = true;
  
  // Nilai dapat di ubah
  price = 125.5; // Harga bisa berubah kapan saja
  
  print ('Pemain: $playerName, Asal: $previousClub, Tujuan: $newClub');
  print ('Usia: $age Tahun, Harga Transfer: €$price jt, Resmi: $isOfficial');
  
  
  String? bonus; // Boleh berisi String atau null
  bonus = ("Bonus €10 Jt jika menjadi Top Score");
  bonus = null;
  
  String ketentuan = bonus ?? "Tidak ada Ketentuan Tambahan Tentang      Bonus";
  
  print (ketentuan!.toUpperCase());
}