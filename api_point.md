
<!--  Tabel Users -->

GET: /users

data: [
{
"id": "1",
"nama": " Muhammad Daffa Nazhirul Haq",
"ig_url": "https://www.instagram.com/daffa_nzhrl/?igshid=YmMyMTA2M2Y%3D",
"github_url": "https://github.com/DaffaNazhirul/Tugastekweb2022"
}
]

POST: /users

data:{
"nama": " Muhammad Daffa Nazhirul Haq",
"ig_url": "https://www.instagram.com/daffa_nzhrl/?igshid=YmMyMTA2M2Y%3D",
"github_url": "https://github.com/DaffaNazhirul/Tugastekweb2022"
}

PUT: /users/[2]

data:{
"nama": " Muhammad Daffa",
"ig_url": "https://www.instagram.com/daffa_nzhrl/?igshid=YmMyMTA2M2Y%3D",
"github_url": "https://github.com/DaffaNazhirul/Tugastekweb2022"
}



<!--  Tabel Portofolio -->

GET: /portofolio

data:[
   {
"id": "1",
"deskripsi": "About Me\r\nseorang manusia dari pulau lombok yang merantau ke jogja untuk menimba ilmu sebagi mahasiswa di universitas ahmad dahlan jurusan sistem informasi, hanya berharap bisa menjadi seseorang yang sukses dunia akhirat"
}

]

GET: /portofolio/[1]

data:{
"id": "1",
"deskripsi": "About Me\r\nseorang manusia dari pulau lombok yang merantau ke jogja untuk menimba ilmu sebagi mahasiswa di universitas ahmad dahlan jurusan sistem informasi, hanya berharap bisa menjadi seseorang yang sukses dunia akhirat"
}


POST: /portofolio

data:{
"deskripsi": "About Me\r\nseorang manusia dari pulau lombok yang merantau ke jogja untuk menimba ilmu sebagi mahasiswa di universitas ahmad dahlan jurusan sistem informasi, hanya berharap bisa menjadi seseorang yang sukses dunia akhirat"
}


PUT: /portofolio/[2]

data:{
"deskripsi": "About Me\r\nseorang manusia yang merantau ke jogja untuk menimba ilmu sebagi mahasiswa di universitas ahmad dahlan jurusan sistem informasi, hanya berharap bisa menjadi seseorang yang sukses dunia akhirat"
}


<!--  Tabel Article -->

GET: /article

data:[
{
"id": "1",
"gambar": "https://ksr.untirta.ac.id/wp-content/uploads/2020/11/cropped-logo-pmi-samping-utuh-2.png",
"deskripsi": "PMR MAN 2 Mataram.\r\nPMR MAN 2 Mataram adalah salah satu PMR terbaik di NTB."
},
{
"id": "2",
"gambar": "https://ksr.untirta.ac.id/wp-content/uploads/2020/11/cropped-logo-pmi-samping-utuh-2.png",
"deskripsi": "PMR MAN 2 Mataram.\r\nPMR MAN 2 adalah salah satu PMR terbaik di NTB."
},
{
"id": "3",
"gambar": "https://rovers.id/image/cache/Gambar%20Untuk%20Produk/Pengertian%20Hiking%20dan%20Manfaatnya%20-%20Rovers%20Adventure%20Indonesia-800x800.jpg",
"deskripsi": "Hiking\r\nAlasan Hiking Banyak di Gemari"
},
{
"id": "4",
"gambar": "https://ksr.untirta.ac.id/wp-content/uploads/2020/11/cropped-logo-pmi-samping-utuh-2.png",
"deskripsi": "PMR MAN 2 Mataram.\r\nPMR MAN 2 Mataram adalah salah satu PMR terbaik di NTB."
}
]


GET: /article/[2]

data:{
"id": "1",
"gambar": "https://ksr.untirta.ac.id/wp-content/uploads/2020/11/cropped-logo-pmi-samping-utuh-2.png",
"deskripsi": "PMR MAN 2 Mataram.\r\nPMR MAN 2 Mataram adalah salah satu PMR terbaik di NTB."
}


POST: /article

data:{
"gambar": "https://ksr.untirta.ac.id/wp-content/uploads/2020/11/cropped-logo-pmi-samping-utuh-2.png",
"deskripsi": "PMR MAN 2 Mataram.\r\nPMR MAN 2 Mataram adalah salah satu PMR terbaik di NTB."
}


PUT: /article/[2]

data:{
"gambar": "https://ksr.untirta.ac.id/wp-content/uploads/2020/11/cropped-logo-pmi-samping-utuh-2.png",
"deskripsi": "PMR MAN 2 Mataram.\r\nPMR MAN 2 adalah salah satu PMR terbaik di NTB."
}
