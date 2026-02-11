<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BAM | Corruption Research Project</title>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;700;800&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Montserrat', sans-serif;
    scroll-behavior:smooth;
}

body{
    background: linear-gradient(135deg, #f8fbff, #fff7f1);
    color:#2a2a2a;
    line-height:1.8;
}

header{
    position:fixed;
    width:100%;
    top:0;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:18px 8%;
    background:rgba(255,255,255,0.88);
    box-shadow:0 10px 30px rgba(0,0,0,0.06);
    z-index:1000;
}

.logo{
    font-size:26px;
    font-weight:800;
    letter-spacing:2px;
    color:#2a2a2a;
}

.nav-right{
    display:flex;
    align-items:center;
}

nav a{
    color:#2a2a2a;
    text-decoration:none;
    margin-left:18px;
    font-weight:600;
    transition:0.3s;
}

nav a:hover{
    color:#7aa7a1;
}

.names{
    margin-left:20px;
    font-size:14px;
    color:#7aa7a1;
    font-weight:600;
}

section{
    padding:120px 8% 80px;
}

.hero{
    height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    text-align:center;
}

.hero h1{
    font-size:52px;
    font-weight:800;
    margin-bottom:18px;
    color:#2a2a2a;
}

.hero p{
    max-width:900px;
    margin:auto;
    font-size:20px;
    opacity:0.85;
}

h2{
    font-size:34px;
    margin-bottom:20px;
    text-align:center;
    color:#2a2a2a;
}

h3{
    font-size:22px;
    margin-top:28px;
    color:#7aa7a1;
}

.content{
    max-width:1000px;
    margin:auto;
}

.card{
    background: linear-gradient(180deg, #ffffff, #f8fbfb);
    padding:30px;
    border-radius:18px;
    box-shadow:0 12px 30px rgba(0,0,0,0.06);
    transition:0.4s;
    margin-bottom:30px;
    border:1px solid rgba(122,167,161,0.25);
}

.card:hover{
    transform:translateY(-6px);
    box-shadow:0 18px 40px rgba(0,0,0,0.08);
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:30px;
}

ul{
    margin-left:20px;
}

.table-wrap{
    margin-top:20px;
}

table{
    width:100%;
    border-collapse:collapse;
    margin-top:30px;
    border-radius:16px;
    overflow:hidden;
    background:white;
    box-shadow:0 15px 35px rgba(0,0,0,0.06);
}

th{
    padding:16px;
    background: linear-gradient(90deg, #7aa7a1, #bca0ff);
    color:white;
    font-weight:700;
    text-transform:uppercase;
    letter-spacing:1px;
    font-size:14px;
}

td{
    padding:14px;
    text-align:center;
    color:#2a2a2a;
    border-bottom:1px solid rgba(0,0,0,0.06);
    font-size:15px;
}

tr:nth-child(even){
    background:#f3fbfa;
}

tr:hover{
    background:#e7f6f4;
    transition:0.3s;
}

tr:last-child td{
    border-bottom:none;
}

.fade{
    opacity:0;
    transform:translateY(40px);
    transition:1s;
}

.fade.show{
    opacity:1;
    transform:translateY(0);
}

footer{
    text-align:center;
    padding:40px;
    background:#ffffff;
    border-top:1px solid rgba(0,0,0,0.06);
    color:#7aa7a1;
}

.banner{
    background: linear-gradient(135deg, #ffdfd1, #f3fbfa);
    border:1px solid rgba(255, 157, 123, 0.35);
    padding:20px 25px;
    border-radius:18px;
    margin:25px 0;
    color:#2a2a2a;
    box-shadow:0 12px 25px rgba(0,0,0,0.05);
}

.banner strong{
    color:#7aa7a1;
}

@media(max-width:768px){
    .hero h1{font-size:40px;}
    .names{display:none;}
}
</style>
</head>

<body>

<header>
    <div class="logo">BAM</div>
    <div class="nav-right">
        <nav>
            <a href="#about">About</a>
            <a href="#mechanisms">Mechanisms</a>
            <a href="#types">Types</a>
            <a href="#causes">Causes</a>
            <a href="#effects">Effects</a>
            <a href="#global">Global</a>
            <a href="#conclusion">Conclusion</a>
        </nav>
        <div class="names">Beisembay Aliya • Malikova Aida • Allakhverdiyev Elnur</div>
    </div>
</header>

<section class="hero">
    <h1>Corruption as a Systemic Global Problem</h1>
    <p>
        Our goal is to comprehensively explore corruption, analyze its causes and mechanisms,
        examine its consequences for society and the state, and study effective international anti-corruption strategies.
    </p>
</section>

<section id="about" class="fade">
<h2>What is Corruption?</h2>
<div class="content">
  <div class="card">
    <p>
      Corruption (Latin: Corruption — bribery) is a socio-economic and political-legal criminal activity,
      which consists in the misuse of official authority for personal expenses and enrichment.
      It may appear as direct bribery, abuse of power, commercial bribery, or hidden influence.
    </p>

    <p>
      For a person thinking about corruption, the choice is to use resources for personal gain.
      Self-interest can be pursued not only for oneself but also for third parties, relatives, or affiliated companies.
      Corruption is a general term describing the selfish use of one’s position for personal purposes.
    </p>

    <p>
      The political essence of corruption is bribery and sell-out of government officials at various levels,
      causing harm to the entire country based only on their interests.
      Corruption is systemic and affects many spheres of life: economy, politics, education, healthcare and law enforcement.
      It is also interpreted as a long-term game, especially when the goal is access to power or its preservation.
    </p>
  </div>

  <div class="banner">
    <strong>Note:</strong> Corruption remains one of the most urgent global problems despite fines and laws.
    It spreads into digitalization and globalization, making the problem even more complex.
  </div>

  <div class="card">
    <h3>Corruption in the Modern World</h3>
    <p>
      Digitalization (moving government and business processes online) and globalization (integration of countries)
      create new opportunities for corruption.
    </p>

    <p>
      In addition, corruption remains relevant due to social and economic factors: uneven income distribution,
      low transparency of government decisions, and societal tolerance of “solving problems” through connections or bribes.
      These conditions create an environment in which corrupt practices become profitable and stable.
    </p>
  </div>

  <div class="card">
    <h3>Our Goal</h3>
    <p>
      Our goal is to comprehensively reveal the problem of corruption, show its causes and mechanisms,
      analyze consequences for the economy, society and the state, and consider effective ways to fight this phenomenon.
    </p>

    <p>
      The article aims to help you understand why corruption remains relevant, how it affects daily life and development of the country,
      and to realize the role of every citizen in combating corruption.
    </p>
  </div>
</div>
</section>

<section id="mechanisms" class="fade">
<h2>Mechanisms of Corruption</h2>
<div class="content">
  <div class="card">
    <p>
      Corruption can occur through direct bribery (giving or receiving money) or hidden abuse of power.
      It often involves unfair distribution of resources, influence, and access to services.
    </p>

    <p>
      The mechanism may include misuse of official authority, manipulation of contracts, or providing preferential treatment to certain companies or people.
      The main feature is that the official acts for personal or group benefit rather than for the public good.
    </p>

    <p>
      In a corrupt system, officials may make decisions based on personal interests, not on law or social needs.
      Corruption becomes a long-term strategy to gain access to power, maintain influence, or secure economic advantages.
    </p>
  </div>
</div>
</section>

<section id="types" class="fade">
<h2>Types of Corruption</h2>
<div class="content">
  <div class="card">
    <h3>Everyday (Petty) Corruption</h3>
    <p>
      Everyday corruption occurs in interactions between ordinary citizens and public officials.
      It includes gifts, services or benefits in exchange for public services.
      Nepotism (promotion of relatives) also falls under this type.
    </p>
  </div>

  <div class="card">
    <h3>Business Corruption</h3>
    <p>
      Business corruption arises from illegal cooperation between authorities and business structures.
      It often occurs in public procurement and contracts, where decisions are made in the interest of private companies rather than society.
      Kickbacks are a typical example.
    </p>
  </div>

  <div class="card">
    <h3>Political Corruption</h3>
    <p>
      Political corruption involves high-level leaders and judicial authorities.
      It affects the entire political system and undermines trust in institutions.
    </p>
  </div>
</div>
</section>

<section id="causes" class="fade">
<h2>Causes of Corruption</h2>
<div class="content">
  <div class="card">
    <h3>Low Legal Culture</h3>
    <p>
      Legal culture is the level of knowledge about the law, respect for the law, and the habit of acting within legal norms.
      Low legal culture encourages corruption because people poorly understand laws and treat bribery as normal.
    </p>

    <p>
      Citizens rarely defend their rights legally, while officials feel impunity.
      As a result, corruption becomes a habitual practice.
    </p>
  </div>

  <div class="card">
    <h3>Weak State Control</h3>
    <p>
      Weak control increases corruption because it reduces the risk of detection and punishment.
      When checks are rare or formal, officials have more freedom to act in their interests.
      The benefit of corruption becomes greater than possible losses.
    </p>
  </div>

  <div class="card">
    <h3>Economic Factors</h3>
    <ul>
      <li>Low income levels of citizens and officials</li>
      <li>High income inequality</li>
      <li>Economic instability and crises</li>
      <li>Large role of the state in the economy</li>
      <li>Shortage of goods and services</li>
      <li>Monopolies and weak competition</li>
    </ul>
  </div>

  <div class="card">
    <h3>Social Inequality</h3>
    <p>
      Social inequality encourages corruption because money and connections become the main way to access resources.
      The poor pay bribes for basic services, while the rich use influence for benefits.
      Corruption creates a cycle of inequality.
    </p>
  </div>

  <div class="card">
    <h3>Impunity</h3>
    <p>
      Impunity increases corruption because without real punishment, abuse of power becomes profitable and normal.
      When laws don’t apply equally, trust in the state collapses, and corruption becomes perceived as normal.
    </p>
  </div>
</div>
</section>

<section id="effects" class="fade">
<h2>Consequences of Corruption</h2>
<div class="content">
  <div class="card">
    <h3>Economic Damage</h3>
    <p>
      Corruption damages the economy: public procurement and tenders are won by those who can pay.
      Public funds are spent inefficiently, and investment attractiveness decreases.
      Businesses often go underground to avoid inspections and extortion.
    </p>
  </div>

  <div class="card">
    <h3>Loss of Trust</h3>
    <p>
      Corruption reduces trust in authorities.
      Citizens see laws applied selectively and officials benefiting at the expense of the population.
      This destroys the sense of justice and undermines legitimacy.
    </p>
  </div>

  <div class="card">
    <h3>Violation of Rights</h3>
    <p>
      Corruption violates citizens’ rights because access to healthcare, education, and legal protection depends on money and connections.
    </p>
  </div>
</div>
</section>

<section id="global" class="fade">
<h2>International Experience</h2>
<div class="content">
  <div class="card">
    <h3>China</h3>
    <p>
      China has one of the strictest anti-corruption systems — bribery can be punished by death.
      The campaign “Hunting Tigers and Flies” targets both high-level and low-level officials.
    </p>
    <p>
      Key directions:
      <ul>
        <li>Large-scale purges at all levels of power</li>
        <li>Institutional changes: supervision committee and disciplinary commission</li>
        <li>“Hunting foxes” and “Heavenly Net”: returning fugitives and combating capital flight</li>
      </ul>
    </p>

    <table>
      <thead>
        <tr>
          <th>Bribe Amount</th>
          <th>Equivalent USD</th>
          <th>Typical Punishment</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Up to 30,000 yuan</td>
          <td>Up to $4,200</td>
          <td>Fine or up to 3 years</td>
        </tr>
        <tr>
          <td>30,000–200,000 yuan</td>
          <td>$4,200–$28,000</td>
          <td>3–10 years imprisonment</td>
        </tr>
        <tr>
          <td>200,000–3M yuan</td>
          <td>$28,000–$420,000</td>
          <td>10 years–life</td>
        </tr>
        <tr>
          <td>Over 3M yuan</td>
          <td>$420,000+</td>
          <td>Life imprisonment or death penalty</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="card">
    <h3>Singapore</h3>
    <p>
      Singapore ranks high in corruption perception index (around 83–84).
      Key methods:
      <ul>
        <li>Principle “Prove the origin of money”</li>
        <li>Independent CPIB bureau</li>
        <li>Strict laws: fines, prison, confiscation of property</li>
      </ul>
    </p>
  </div>

  <div class="card">
    <h3>Contrast: Yemen</h3>
    <p>
      Yemen has low effectiveness in fighting corruption due to weak institutions, tribal culture, and economic instability.
      Corruption is used to distribute resources and humanitarian aid.
    </p>
  </div>

  <div class="card">
    <h3>Examples of Successful Reforms</h3>
    <p>
      <b>Georgia (2004–2012)</b> — “shock therapy”: police reform, transparency, simplified procedures.
      <br>
      <b>Denmark</b> — culture of trust and accountability: public declarations, open income reporting, strict gift restrictions.
    </p>
  </div>
</div>
</section>

<section id="conclusion" class="fade">
<h2>Conclusion</h2>
<div class="content">
  <div class="card">
    <p>
      Corruption is a symptom of systemic problems of the state and society, not an independent disease.
      Effective fight requires institutional reforms, transparency, accountability, political will,
      free media and active civil society.
    </p>

    <p>
      Every citizen plays a role in combating corruption. Without active public participation and free journalism,
      it is almost impossible to eliminate corruption.
    </p>
  </div>
</div>
</section>

<footer>
<p><strong>BAM Research Project 2026</strong></p>
<p>Beisembay Aliya • Malikova Aida • Allakhverdiyev Elnur</p>
</footer>

<script>
const sections = document.querySelectorAll('.fade');
window.addEventListener('scroll', () => {
  sections.forEach(sec => {
    if (sec.getBoundingClientRect().top < window.innerHeight - 100) {
      sec.classList.add('show');
    }
  });
});
</script>

</body>
</html>
