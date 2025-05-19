const players = [];
let current = 0;
let roles = [];

const celebrities = [
  "Orhan Gencebay", "Sezen Aksu", "Tarkan", "İbrahim Tatlıses", "Candan Erçetin",
  "Sertab Erener", "Kenan Doğulu", "Hadise", "Demet Akalın", "Haluk Levent",
  "Barış Manço", "Nazan Öncel", "Oğuz Atay", "Şener Şen", "Nuri Bilge Ceylan",
  "Fatih Akın", "Türkan Şoray", "Kadir İnanır", "Beren Saat", "Haluk Bilginer",
  "Cem Yılmaz", "Mahsun Kırmızıgül", "Tuba Büyüküstün", "Orhan Pamuk", "Elif Şafak",
  "Cemal Süreya", "Attila İlhan", "Ahmet Hamdi Tanpınar", "Nazım Hikmet", "Murathan Mungan",
  "Arda Turan", "Naim Süleymanoğlu", "Rüştü Reçber", "İbrahim Üzülmez", "Rahmi Koç",
  "Ferit Şahenk", "İbrahim Tatlıses", "Murat Ülker", "Ümit Boyner", "Aydın Doğan",
  "Güler Sabancı", "Aziz Sancar", "Fuat Sezgin", "Canan Dağdeviren", "Mete Atatüre",
  "Uğur Şahin", "Özlem Türeci", "İhsan Doğramacı", "Mustafa Kemal Atatürk", "Recep Tayyip Erdoğan",
  "Tansu Çiller", "Süleyman Demirel", "Bülent Ecevit", "Kemal Kılıçdaroğlu", "Acun Ilıcalı",
  "Hülya Avşar", "Okan Bayülgen", "Nazlı Çelik", "Uğur Dündar", "Ece Erken",
  "Sıla", "Burak Özçivit", "Hande Erçel", "Serenay Sarıkaya", "Kıvanç Tatlıtuğ",
  "Elçin Sangu", "Hazal Kaya", "Murat Boz", "Emre Altuğ", "Gülşen", "Aslı Enver", "Kerem Bürsin"
];

function startGame(playerCount) {
  current = 0;
  roles = [];
  document.getElementById('result').innerText = "";
  let selectedCelebrity = celebrities[Math.floor(Math.random() * celebrities.length)];
  let imposterIndex = Math.floor(Math.random() * playerCount);
  for (let i = 0; i < playerCount; i++) {
    roles.push(i === imposterIndex ? "İmposter" : selectedCelebrity);
  }
  document.getElementById('nextBtn').style.display = "inline-block";
  document.getElementById('revealBtn').style.display = "inline-block";
}

function reveal() {
  document.getElementById('result').innerText = roles[current];
  document.getElementById('revealBtn').style.display = "none";
}

function nextPlayer() {
  current++;
  if (current >= roles.length) {
    document.getElementById('nextBtn').style.display = "none";
    document.getElementById('result').innerText = "Tüm oyuncular baktı!";
  } else {
    document.getElementById('result').innerText = "";
    document.getElementById('revealBtn').style.display = "inline-block";
  }
}
