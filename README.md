# <img src="https://ikplayer.ikweb.org/1.0.9/logo.png" alt="IK Player Logo" />

IK Player web üzerinde videolar oynatabilen bir javascript eklentisidir.

## Kurulum

Bir html dosyasına ikplayer.js dosyası çağrılır. Bir ID'ye sahip HTML DIV etiketi oluşturulur. IKPlayer fonksiyonu ile div etiketi tanımlanır. Setup fonksiyonu ile özellikler tanımlanıp kurulum işlemi tamamlanır.

## Örnek

````html
<script src="ikplayer.js"></script>
<div id="ikplayer"></div>
<script>
ikplayer('ikplayer').setup({
	file: "file.mp4",
	image: "image.jpg",
	about: {
		text: "IK Player",
		link: "https://ikplayer.ikweb.org"
	},
	logo: {
		file: "logo.png",
		link: "https://ikplayer.ikweb.org",
		position: "top-right",
		hide: false
	},
	autoplay: true,
	controls: false,
	repeat: true,
	muted: true,
	starttime: 5,
	width: "100%",
	height: "100%"
})
</script>
````

## Parametreler

#### file:
Oynatıcı video dosyası bağlantısı
#### image:
Oynatıcı görüntü dosyası bağlantısı
#### width:
Oynatıcı genişliği. Varsayılan: 100%
#### height:
Oynatıcı genişliği. Varsayılan: 100%
#### autoplay:
Oynatıcı çalıştığında video'yu otomatik oynatır. Varsayılan: false
#### controls:
Oynatıcı cotrolleri aktif eder. Varsayılan: true
#### repeat:
Oynatıcı video'yu sürekli tekrar ettirir. Varsayılan: false
#### muted:
Oynatıcı video'nun sesini kapatır. Varsayılan: false
#### starttime:
Oynatıcı videonun başlangıç süresini belirler. Varsayılan: 0
#### logo.file:
Oynatıcı logo dosyası bağlantısı. Varsayılan: IK Player Logosu
#### logo.link:
Oynatıcı logo link'i. Varsayılan: https://ikplayer.ikweb.org/1.0.9/ikplayer.html
#### logo.position:
Oynatıcı logo konumunu belirler. Varsayılan: top-right
#### logo.hide:
Oynatıcı logo gizliliğini belirler. Varsayılan: false
#### about.text:
Oynatıcı hakkında metin tanımlar. Varsayılan: IK Player
#### about.link:
Oynatıcı hakkında link'i tanımlar. Varsayılan: https://ikplayer.ikweb.org
