# MinPro-1-PBW

## Penjelasan Section/Fitur

### Home

<img width="1296" height="644" alt="image" src="https://github.com/user-attachments/assets/eb366123-9ba1-4515-823e-6b0c6f4b95e1" />

Pada bagian Home terdapat tampilan:
- 2 foto saya, yang di mana 1 foto saya sebagai background dan 1 foto saya sebagai foto profil
- Nama lengkap
- Deskripsi singkat tentang saya

### About Me

<img width="1316" height="648" alt="image" src="https://github.com/user-attachments/assets/3fd6aaa3-c307-4d8d-9d4b-26406b26c301" />

Pada bagian About Me ini berisikan tentang diri saya dan skill yang saya miliki:
- Penjelasan singkat tentang latar belakang saya
- Skill progress bar

### Certificates

<img width="1296" height="648" alt="image" src="https://github.com/user-attachments/assets/d093a7f9-e66c-4c73-9614-a324f6e07c3e" />

Selanjutnya pada bagian Certificates merupakan tampilan sertifikat yang pernah saya dapatkan

## Penjelasan Code Setiap Section/Fitur
### Navbar 
Disini saya menggunakan class .navbar guna mengatur warna background, shadow, dan efek hover pada menu.
### Hero Section 
.hero {
    height: 100vh; // 
    background: linear-gradient(...), url("aku.jpeg");
}
Pada code ini guna untuk memenuhi 1 layar dan memberikan efek transparan pada background, lalu saya memasukkan foto saya sebagai background dari Home dengan format "aku.jpeg"
### Skill Progress Bar
<div class="skill-bar">
    <div class="skill-fill corel"></div>
</div>
Saya menggunakan gradient agar terlihat lebih modern
### Certificates
.polaroid {
    transform: rotate(-2deg);
    transition: 0.3s ease;
}
Pada certificates saya menggunakan frame agar terlihat lebih menarik, kemudian polaroid dengan rotasi -2
## Teknologi yang Digunakan
- HTML --> Struktur dasar website
- CSS --> Tempat styling dan animasi website
- Google Fonts --> Mengambil font Poppins
- Font Custom --> Daughter of Fortune (font nama)
- Bootsstrap --> Layout dan komponen tambahan
