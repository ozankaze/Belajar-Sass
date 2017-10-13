# catatan
  
# Belajar SASS : Perkenalan dan cara Install

# Belajar SASS : Demo Dasar
. sass sass adalah kayak kita membuat variable 
. untuk ngecompare atau ngejalanin sendiri, kita ke coment line (terminal di folder yang sama)

. nama/folder/  sass -h 
= bisa ngapain ajah 
 
. nama/folder/  sass contoh.scss style.css 
= dari contoh.scss maukita transfer file ke style.css

. nama/folder/  sass --watch contoh.scss:style.css 
= ini adalah di bakal ngawasin file scss kita setiap kita ngelakuin perubahan dia bakal ngesave di file cssnya otomatis kaka

# Belajar SASS : Struktur File + import
kita  bwat folder kelas kita bwat file baru
= _variable bwat isi variable
= layout bwat isinya file css nya  


bwat menyambungkan file di atas wariable sama layout kita harus di command (terminal dulu)

. nama/folder/  sass --watch bahan/main.scss:style.css
= untuk menyambungkan kita menggunakan,
@import 'kelas/variable';
@import 'kelas/layout';
di file main.scss