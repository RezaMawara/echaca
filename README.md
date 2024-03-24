# -TIK2032-Project
Repositori project TIK2032 - Reza Michelly Cantika Mawara 220211060300

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>chaxiee</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #2c525e, #272630); 
            color: #fff; 
        }
        header, footer {
            background-color: #21222a;
            text-align: center;
            padding: 20px 0;
        }
        nav {
            background-color: #21222a;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        section {
            padding: 20px;
            display: none; 
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
        }
        .gallery img {
            width: 200px; /* Menetapkan lebar gambar */
            height: 200px; /* Menetapkan tinggi gambar */
            object-fit: cover; 
        }
        .blog-post {
            margin-bottom: 20px;
            border-bottom: 1px solid #ccc;
            padding-bottom: 20px;
        }
        .contact-form {
            max-width: 400px;
            margin: 0 auto;
        }
        .contact-form p {
            margin: 0;
        }
        .contact-form p span {
            font-weight: bold;
        }
    </style>
</head>
<body>

<header>
    <h1>chaxiee</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#gallery">Gallery</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h2>Halaman Utama (Home)</h2>
    <h2>Hai, Nama saya Reza biasa disapa echa.</h2>
</section>

<section id="gallery">
    <h2>Galeri (Gallery)</h2>
    <div class="gallery">
        <!-- Kumpulan foto-foto -->
        <img src="AF1.jpg" alt="Foto 1">
        <img src="AF2.jpg" alt="Foto 2">
        <img src="FT3.jpg" alt="Foto 3">
        <img src="GJ1.jpg" alt="Foto 4">
        <img src="IY2.jpg" alt="Foto 5">
        <img src="L3.jpg" alt="Foto 6">
    </div>
</section>

<section id="blog">
    <h2>Blog</h2>
    <!-- Artikel-artikel-->
    <div class="blog-post">
        <h3>Manfaat olahraga untuk kesehatan</h3>
        <p>Olahraga memiliki beragam manfaat untuk kesehatan. Ini termasuk meningkatkan kesehatan jantung, 
            mengendalikan berat badan, memperbaiki kesehatan mental, meningkatkan kekuatan dan fleksibilitas tubuh, meningkatkan sistem kekebalan tubuh, 
            dan memperpanjang umur. Dengan melakukan olahraga secara teratur, Anda dapat meningkatkan kualitas hidup secara keseluruhan.</p>
    </div>
    <div class="blog-post">
        <h3>Menyelami Kekuatan Cerita dalam Seni Visual</h3>
        <p>Seni visual adalah medium yang memungkinkan seniman untuk menyampaikan cerita, emosi, dan pesan melalui gambar, lukisan, atau fotografi. 
            Dengan menggunakan elemen-elemen seperti komposisi, warna, dan pencahayaan, seniman menciptakan karya yang mengundang pemirsa untuk merenungkan makna di baliknya. 
            Melalui seni visual, kita dapat memahami berbagai aspek kehidupan, merenungkan isu-isu sosial atau politik, dan merasakan keindahan serta kompleksitas dunia di sekitar kita.</p>
    </div>
    <div class="blog-post">
        <h3>Musik dan Pengaruhnya terhadap Mood dan Emosi</h3>
        <p>Musik memiliki kemampuan unik untuk mengubah suasana hati dan emosi seseorang secara instan. 
            Ketika kita mendengarkan musik yang kita sukai, otak kita melepaskan hormon-hormon yang memicu perasaan senang atau tenang. 
            Musik yang ceria dapat meningkatkan mood positif, sementara musik yang lebih santai dapat menenangkan jiwa dan meredakan stres. 
            Fenomena ini menjadikan musik sebagai alat yang ampuh untuk mengatur suasana hati kita sehari-hari.</p>
    </div>
</section>

<section id="contact">
    <h2>Kontak (Contact)</h2>
    <!-- Formulir kontak -->
    <form class="contact-form" action="#" method="post">
        <p><span>Nama:</span> Reza Michelly Cantika Mawara</p>
        <p><span>Email:</span> michellymawara@gmail.com</p>
        <p><span>No Telepon:</span> 085240216328</p>
    </form>
</section>

<footer>
    <p>Hak Cipta &copy; 2024 </p>
</footer>

<script>
    
    document.querySelectorAll('nav a').forEach(anchor => {
        anchor.addEventListener('click', function(e) {
            e.preventDefault();
           
            document.querySelectorAll('section').forEach(section => {
                section.style.display = 'none';
            });
            
            document.querySelector(this.getAttribute('href')).style.display = 'block';
        });
    });
</script>

</body>
</html>

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/-TIK2032-Project (main)
$ git clone https://github.com/RezaMawara/echaca.github.io
Cloning into 'echaca.github.io'...
remote: Repository not found.
fatal: repository 'https://github.com/RezaMawara/echaca.github.io/' not found

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/-TIK2032-Project (main)
$ git clone https://github.com/RezaMawara/echaca.github.io
Cloning into 'echaca.github.io'...
warning: You appear to have cloned an empty repository.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/-TIK2032-Project (main)
$ cd RezaMawara.github.io
bash: cd: RezaMawara.github.io: No such file or directory

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/-TIK2032-Project (main)
$ cd echaca.github.io

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/-TIK2032-Project/echaca.github.io (main)
$ echo "Hello World" > index.html

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/-TIK2032-Project/echaca.github.io (main)
$ git add --all
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/-TIK2032-Project/echaca.github.io (main)
$ git commit -m "Initial commit"
[main (root-commit) 2fb2719] Initial commit
 1 file changed, 1 insertion(+)
 create mode 100644 index.html

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/-TIK2032-Project/echaca.github.io (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 233 bytes | 233.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/RezaMawara/echaca.github.io
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/-TIK2032-Project/echaca.github.io (main)
$
