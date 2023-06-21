# LP12DPBO2023C2

## Deskripsi Tugas
Mengubah arsitektur LP7 menjadi MVP atau MVVM

## Alasan:
Saya mengubah arsitekturnya menjadi MVP karena menurut saya dalam struktur penyusunan kodenya dapat dibagi menjadi model, view, dan presenter. Dalam MVP, logikanya disimpan pada presenter sehingga lebih mudah untuk melakukan pengujian dibandingkan MVVP yang menurut saya lebih kompleks dalam melakukan pengujian.

### Model
  - GameObject
  - Handler
#### View
  - Bonus
  - Display
  - Game
  - GameInterface
  - Player
### Presenter
  - Controller

## Update 21/06/23:

### Model
  - DB
  - ScoreModel
#### View
  - ScoreView
  - Display
  - Game
### Presenter
  - Controller
  - GameInterface
  - GameObject
  - Handler
  - Music
  - Objek
  - Player
  - ScorePresenter

## Keterangan Perubahan:
- Model
  Dalam model diubah menjadi Db dan ScoreModel yang berfungsi untuk mengelola data.
- Presenter
  Dalam presenter diubah menjadi bagian yang mengatasi:
  -  Pergerakan player
  -  Menerima input keyboard
  -  Perantara penghubung model dengan view
  -  Atribut yang dimiliki objek yang akan dipanggil di view.
- View
  Dalam view diubah menjadi bagian yang mengatasi apa yang akan ditampilkan.

Sebelum perubahan struktur MVP masih belum terpisah dengan baik, dibandingkan dengan struktur yang digunakan saat TMD.  
