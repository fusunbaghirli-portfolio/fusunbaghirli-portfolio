
aha etdim
Əla, Füsun! ❤️ İndi saytımızın faylını yaradacağıq ki, Render onu göstərə bilsin.

Növbəti addım — index.html yaratmaq
1. GitHub hesabına keç: github.com

2. fusun-portfolio repository-sini aç.

3. Repository daxilində:

Add file düyməsinə bas.

Create new file seç.

Faylın adını index.html yaz.

4. Açılan böyük mətn sahəsinə hələlik heç nə yazma. Mən sənə növbəti mesajda saytın kodunu verəcəyəm.

İndi mənə de: index.html faylını yaratmaq üçün mətn sahəsi açıldı? 😊

etdim
Əla, Füsun! ❤️ İndi saytının ilk versiyasını yerləşdirək.

Növbəti addım — Saytın kodunu əlavə et
GitHub-da açdığın index.html faylının böyük mətn sahəsinə aşağıdakı kodu tam şəkildə kopyala.


<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Füsun Bağırlı | Portfolio</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f7f5ef;
      color: #25392e;
      line-height: 1.7;
    }
    header {
      padding: 24px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ddd9ce;
    }
    nav a {
      margin-left: 18px;
      color: #25392e;
      text-decoration: none;
    }
    .hero {
      padding: 110px 10%;
      min-height: 65vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .eyebrow {
      color: #967b4f;
      letter-spacing: 3px;
      font-size: 12px;
    }
    h1 {
      font: normal clamp(44px, 7vw, 76px)/1.1 Georgia, serif;
      max-width: 800px;
      margin: 20px 0;
    }
    p { max-width: 650px; }
    .button {
      display: inline-block;
      background: #25392e;
      color: white;
      padding: 12px 24px;
      text-decoration: none;
      margin-top: 16px;
      width: fit-content;
    }
    section { padding: 65px 10%; }
    h2 { font: normal 36px Georgia, serif; }
    .about { background: #eae8df; }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 18px;
    }
    .card {
      background: #fffefa;
      padding: 24px;
      border: 1px solid #e3e0d6;
    }
    .contact { background: #25392e; color: white; }
    .contact a { color: white; }
    footer { padding: 24px 10%; font-size: 13px; }
    @media(max-width:600px) {
      header { flex-direction: column; gap: 12px; }
      nav a { margin: 0 8px; font-size: 13px; }
      .hero { padding: 75px 8%; }
      section { padding: 50px 8%; }
    }
  </style>
</head>
<body>
  <header>
    <strong>FÜSUN BAĞIRLI</strong>
    <nav>
      <a href="#about">Haqqımda</a>
      <a href="#work">Fəaliyyət</a>
      <a href="#contact">Əlaqə</a>
    </nav>
  </header>

  <main>
    <div class="hero">
      <div class="eyebrow">HR · LEARNING & DEVELOPMENT · PEOPLE</div>
      <h1>İnsan potensialını inkişafla birləşdirirəm.</h1>
      <p>Füsun Bağırlı — insan resursları üzrə ekspert, təlimçi, mentor və spiker. İnsanların və komandaların inkişafına töhfə verən layihələr üzərində çalışıram.</p>
      <a class="button" href="#about">Mənimlə tanış ol</a>
    </div>

    <section class="about" id="about">
      <h2>Haqqımda</h2>
      <p>İnsan resursları, istedadların cəlbi, təlim və inkişaf, eləcə də gənclərin karyera inkişafı sahələrində təcrübəyə sahibəm. Fəaliyyətimdə insan yönümlü yanaşmaya və davamlı öyrənməyə üstünlük verirəm.</p>
    </section>

    <section id="work">
      <h2>Fəaliyyət istiqamətlərim</h2>
      <div class="cards">
        <div class="card">
          <h3>İnsan resursları</h3>
          <p>İşə qəbul, istedadların idarə edilməsi və əməkdaşların inkişafı.</p>
        </div>
        <div class="card">
          <h3>Təlim və inkişaf</h3>
          <p>Təlim proqramları, komanda inkişafı və fasilitasiya.</p>
        </div>
        <div class="card">
          <h3>Mentorluq</h3>
          <p>Karyera planlaması, şəxsi brendinq və gənclərin inkişafı.</p>
        </div>
        <div class="card">
          <h3>Spikerlik</h3>
          <p>İctimai çıxışlar, tədbirlər və bilik mübadiləsi.</p>
        </div>
      </div>
    </section>

    <section class="about">
      <h2>Layihələr</h2>
      <div class="cards">
        <div class="card">
          <h3>DNT HUB</h3>
          <p>Təlim, inkişaf və ekspert əməkdaşlığı təşəbbüsləri.</p>
        </div>
        <div class="card">
          <h3>TEDx çıxışı</h3>
          <p>“Düşdüyün Yerdən Yox, Düşündüyün Yerdən Başla.”</p>
        </div>
        <div class="card">
          <h3>Gənclərin inkişafı</h3>
          <p>Mentorluq, təlimlər və karyera yönümlü layihələr.</p>
        </div>
      </div>
    </section>

    <section class="contact" id="contact">
      <h2>Əməkdaşlıq edək</h2>
      <p>Təlim, mentorluq və peşəkar əməkdaşlıq üçün mənimlə əlaqə saxla.</p>
      <p><a href="https://www.linkedin.com/in/fusun-baghirli/" target="_blank" rel="noopener noreferrer">LinkedIn profilim</a></p>
    </section>
  </main>

  <footer>© 2026 Füsun Bağırlı. Bütün hüquqlar qorunur.</footer>
</body>
</html>

Sonra nə etməlisən?
Kodu index.html mətn sahəsinə yerləşdir.

Səhifənin aşağısındakı Commit changes düyməsinə bas.

Açılan pəncərədə yenə Commit changes ilə təsdiqlə.

Bunu etdikdən sonra mənə “Hazırdır” yaz. Sonra Render-ə qayıdıb saytını yayımlayacağıq. 😊

kodu hara əlavə edim anlamadım
Füsun, narahat olma ❤️ İndi sənə dəqiq göstərəcəyəm. Birlikdə edəcəyik.

İndi GitHub-da bu addımları et
1. Bu linki aç: GitHub — fusun-portfolio

2. fusun-portfolio adlı repository-nə daxil ol.

3. Faylların arasında index.html faylını tap və üzərinə kliklə.

4. Açılan səhifədə qələmlə göstərilən Edit (✏️) düyməsini tapıb bas.

5. İndi kodun yazılacağı böyük, ağ mətn sahəsi görünəcək. Mənim göndərdiyim kodu məhz ora yerləşdirməlisən.

Faylı aç → qələm işarəsi → ağ mətn sahəsi

Əgər mətn sahəsində əvvəlcədən kod varsa, onu seçib sil, sonra mənim göndərdiyim kodu yerləşdir.

6. Yuxarıda və ya aşağıda görünən Commit changes düyməsinə bas.

İndi bir şeyi edək: GitHub-da fusun-portfolio səhifəsini aç və mənə ekran görüntüsünü göndər. Mən sənə növbəti klikləyəcəyin düyməni dəqiq göstərəcəyəm. 😊

kodu bir də yaz yazısız şəkildə sadəcə kodu yaz

<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Füsun Bağırlı | Portfolio</title>
  <meta name="description" content="Füsun Bağırlının HR, təlim, mentorluq və spikerlik üzrə şəxsi portfolio saytı.">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      font-family: Arial, sans-serif;
      color: #25392e;
      background: #f7f5ef;
      line-height: 1.7;
    }
    header {
      padding: 24px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ddd9ce;
    }
    .logo { font-weight: bold; letter-spacing: 2px; }
    nav a {
      margin-left: 18px;
      color: #25392e;
      text-decoration: none;
      font-size: 14px;
    }
    .hero {
      padding: 100px 10%;
      min-height: 75vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: flex-start;
    }
    .eyebrow {
      color: #967b4f;
      letter-spacing: 3px;
      font-size: 12px;
      text-transform: uppercase;
    }
    h1 {
      font: normal clamp(44px, 7vw, 78px)/1.1 Georgia, serif;
      max-width: 850px;
      margin: 22px 0;
    }
    .hero p, .section-text { max-width: 680px; color: #65685f; }
    .button {
      display: inline-block;
      background: #25392e;
      color: white;
      padding: 13px 25px;
      text-decoration: none;
      margin-top: 24px;
    }
    section { padding: 75px 10%; }
    h2 {
      font: normal 38px Georgia, serif;
      margin-bottom: 24px;
    }
    .about, .projects { background: #eae8df; }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      padding: 26px;
      border: 1px solid #dedbd1;
      background: #fffefa;
    }
    .card h3 { margin-bottom: 12px; }
    .card p { color: #65685f; font-size: 15px; }
    .contact { background: #25392e; color: white; }
    .contact p { margin-bottom: 14px; }
    .contact a { color: white; }
    footer { padding: 24px 10%; color: #65685f; font-size: 13px; }
    @media (max-width: 600px) {
      header { flex-direction: column; align-items: flex-start; gap: 14px; }
      nav a { margin: 0 12px 0 0; }
      .hero { padding: 75px 8%; min-height: 65vh; }
      section { padding: 55px 8%; }
      h2 { font-size: 32px; }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">FÜSUN BAĞIRLI</div>
    <nav>
      <a href="#about">Haqqımda</a>
      <a href="#expertise">İxtisaslaşma</a>
      <a href="#projects">Layihələr</a>
      <a href="#contact">Əlaqə</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div class="eyebrow">HR · Learning & Development · People</div>
      <h1>İnsan potensialını inkişafla birləşdirirəm.</h1>
      <p>
        Mən Füsun Bağırlıyam — insan resursları üzrə mütəxəssis,
        təlimçi, mentor və spiker. İnsanların və komandaların
        inkişafına töhfə verən layihələr üzərində çalışıram.
      </p>
      <a class="button" href="#about">Mənimlə tanış ol</a>
    </section>

    <section class="about" id="about">
      <h2>Haqqımda</h2>
      <p class="section-text">
        Bakı Slavyan Universitetində fransız dili müəllimliyi üzrə
        təhsil almışam, İstanbul Universitetində MBA proqramını
        bitirmişəm və hazırda Xəzər Universitetində İnsan Resurslarının
        İdarə Edilməsi üzrə magistr təhsili alıram. Peşəkar fəaliyyətim
        insan resursları, istedadların cəlbi, təlim və inkişaf
        istiqamətlərini əhatə edir.
      </p>
    </section>

    <section id="expertise">
      <h2>Fəaliyyət istiqamətlərim</h2>
      <div class="cards">
        <div class="card">
          <h3>İnsan resursları</h3>
          <p>İşə qəbul, istedadların idarə edilməsi, adaptasiya və performansın qiymətləndirilməsi.</p>
        </div>
        <div class="card">
          <h3>Təlim və inkişaf</h3>
          <p>Təlim proqramlarının hazırlanması, ehtiyacların təhlili və komanda inkişafı.</p>
        </div>
        <div class="card">
          <h3>Mentorluq</h3>
          <p>Karyera planlaması, şəxsi brendinq və gənclərin peşəkar inkişafı.</p>
        </div>
        <div class="card">
          <h3>Spikerlik</h3>
          <p>İctimai çıxışlar, konfranslar, tədbirlər və bilik mübadiləsi.</p>
        </div>
      </div>
    </section>

    <section class="projects" id="projects">
      <h2>Layihələr və nailiyyətlər</h2>
      <div class="cards">
        <div class="card">
          <h3>DNT HUB</h3>
          <p>Təlim, inkişaf və ekspert əməkdaşlığı istiqamətində təşəbbüslər.</p>
        </div>
        <div class="card">
          <h3>TEDx çıxışı</h3>
          <p>“Düşdüyün Yerdən Yox, Düşündüyün Yerdən Başla.”</p>
        </div>
        <div class="card">
          <h3>Mentorluq və gənclər</h3>
          <p>Gənclərin inkişafı, karyera yönümlü təlimlər və mentorluq layihələri.</p>
        </div>
      </div>
    </section>

    <section class="contact" id="contact">
      <h2>Əməkdaşlıq edək</h2>
      <p>Təlim, mentorluq, spikerlik və peşəkar əməkdaşlıq üçün mənimlə əlaqə saxla.</p>
      <p>
        <a href="https://www.linkedin.com/in/fusun-baghirli/" target="_blank" rel="noopener noreferrer">LinkedIn profilim</a>
      </p>
    </section>
  </main>

  <footer>© 2026 Füsun Bağırlı. Bütün hüquqlar qorunur.</footer>
</body>
</html>




