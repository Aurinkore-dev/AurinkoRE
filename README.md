<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Aurinko Re – Global Specialty Reinsurance MGA</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    :root {
      --primary: #0b3c5d;
      --secondary: #f18f01;
      --bg: #f7f9fc;
      --text: #222;
      --muted: #666;
    }
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    }
    body {
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    header {
      background: linear-gradient(135deg, #0b3c5d, #102a43);
      color: #fff;
      padding: 60px 20px 40px;
    }
    header .container {
      max-width: 1100px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    header h1 {
      font-size: 2.4rem;
      letter-spacing: 0.03em;
    }
    header p {
      max-width: 650px;
      font-size: 1.05rem;
      color: #e0e7ff;
    }
    .tagline {
      font-weight: 600;
      color: var(--secondary);
      text-transform: uppercase;
      letter-spacing: 0.12em;
      font-size: 0.85rem;
    }
    nav {
      background: #fff;
      border-bottom: 1px solid #e1e4ea;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav .container {
      max-width: 1100px;
      margin: 0 auto;
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      padding: 10px 20px;
      justify-content: center;
    }
    nav a {
      text-decoration: none;
      color: var(--primary);
      font-size: 0.9rem;
      padding: 6px 10px;
      border-radius: 999px;
      border: 1px solid transparent;
    }
    nav a:hover {
      border-color: var(--secondary);
      color: var(--secondary);
    }
    section {
      padding: 50px 20px;
    }
    .section-inner {
      max-width: 1100px;
      margin: 0 auto;
    }
    h2 {
      font-size: 1.8rem;
      margin-bottom: 10px;
      color: var(--primary);
    }
    h3 {
      font-size: 1.2rem;
      margin: 20px 0 8px;
      color: var(--primary);
    }
    p {
      margin-bottom: 10px;
      color: var(--muted);
    }
    .grid-2 {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
      margin-top: 20px;
    }
    .card {
      background: #fff;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 6px 18px rgba(15, 23, 42, 0.06);
    }
    .pill {
      display: inline-block;
      padding: 3px 10px;
      border-radius: 999px;
      background: #e5effa;
      color: var(--primary);
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      margin-bottom: 8px;
    }
    ul {
      margin-left: 18px;
      margin-bottom: 10px;
      color: var(--muted);
    }
    li {
      margin-bottom: 4px;
    }
    .team-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .team-card h4 {
      margin-bottom: 4px;
      color: var(--primary);
    }
    .team-role {
      font-size: 0.9rem;
      color: var(--secondary);
      margin-bottom: 6px;
    }
    .kpi-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .kpi {
      background: #fff;
      border-radius: 10px;
      padding: 18px;
      text-align: center;
      box-shadow: 0 4px 14px rgba(15, 23, 42, 0.05);
    }
    .kpi span {
      display: block;
      font-size: 1.4rem;
      font-weight: 700;
      color: var(--primary);
    }
    .kpi small {
      font-size: 0.8rem;
      color: var(--muted);
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
      background: #fff;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 14px rgba(15, 23, 42, 0.05);
    }
    th, td {
      padding: 10px 12px;
      font-size: 0.9rem;
      text-align: left;
      border-bottom: 1px solid #e5e7eb;
    }
    th {
      background: #f1f5f9;
      color: var(--primary);
      font-weight: 600;
    }
    tr:last-child td {
      border-bottom: none;
    }
    tfoot td {
      font-weight: 600;
      background: #f9fafb;
    }
    .cta {
      text-align: center;
      padding: 60px 20px 80px;
      background: #0b3c5d;
      color: #fff;
    }
    .cta h2 {
      color: #fff;
      margin-bottom: 10px;
    }
    .cta p {
      color: #e0e7ff;
      margin-bottom: 20px;
    }
    .cta a {
      display: inline-block;
      padding: 10px 22px;
      border-radius: 999px;
      background: var(--secondary);
      color: #fff;
      text-decoration: none;
      font-size: 0.95rem;
      font-weight: 600;
    }
    .cta a:hover {
      opacity: 0.9;
    }
    footer {
      text-align: center;
      padding: 15px 10px 25px;
      font-size: 0.8rem;
      color: #94a3b8;
    }
  </style>
</head>
<body>

<header>
  <div class="container">
    <div class="tagline">Global Specialty Reinsurance MGA</div>
    <h1>Aurinko Re</h1>
    <p>
      Achieve success through our strategic partnership. Aurinko Re operates as a specialized
      Credit &amp; Surety reinsurance MGA, combining underwriting discipline, actuarial rigor and
      deep market relationships across Europe and Asia.
    </p>
  </div>
</header>

<nav>
  <div class="container">
    <a href="#overview">Executive Overview</a>
    <a href="#mission">Mission &amp; Vision</a>
    <a href="#value">Value Proposition</a>
    <a href="#team">MGA &amp; Team</a>
    <a href="#portfolio">Portfolio Management</a>
    <a href="#strategy">Reinsurance Strategy</a>
    <a href="#monitoring">Monitoring &amp; Positioning</a>
    <a href="#financials">Financial Outlook</a>
    <a href="#europe">Europe Surety Market</a>
  </div>
</nav>

<section id="overview">
  <div class="section-inner">
    <h2>Executive Overview</h2>
    <div class="grid-2">
      <div>
        <h3>Executive Summary</h3>
        <p><strong>Aurinko Re</strong> operates as a specialized Reinsurer‑MGA focused on
          <strong>Credit and Surety reinsurance treaties</strong>.</p>
        <p>
          We leverage deep expertise in underwriting, insurance, reinsurance, brokerage and
          actuarial science to identify and structure high‑value treaty opportunities across
          Europe and Asia, under a disciplined risk appetite.
        </p>
      </div>
      <div>
        <h3>Our Team &amp; Network</h3>
        <ul>
          <li>Reinsurance underwriting expertise</li>
          <li>Actuarial &amp; technical capabilities</li>
          <li>Market intelligence and benchmarking</li>
          <li>Long‑standing relationships with leading carriers, reinsurers and regulators</li>
        </ul>
        <p>
          This combination allows us to navigate complex markets, secure optimal capacity and
          deliver disciplined underwriting performance as a trusted partner for sustainable,
          profitable growth.
        </p>
      </div>
    </div>
  </div>
</section>

<section id="mission">
  <div class="section-inner">
    <h2>Mission &amp; Vision</h2>
    <div class="grid-2">
      <div class="card">
        <div class="pill">Mission</div>
        <p>
          To provide disciplined and structured Credit &amp; Surety reinsurance solutions in
          profitable portfolios which support your sustainable growth.
        </p>
      </div>
      <div class="card">
        <div class="pill">Vision</div>
        <p>
          To be a trusted reference in Credit &amp; Surety reinsurance, recognized for
          underwriting excellence and long‑term partnerships.
        </p>
      </div>
    </div>
    <p style="margin-top:20px;">
      <strong>Let’s build a resilient and profitable reinsurance portfolio of treaties together.</strong>
    </p>
  </div>
</section>

<section id="value">
  <div class="section-inner">
    <h2>Our Value Proposition</h2>
    <div class="grid-2">
      <div class="card">
        <h3>Underwriting Discipline</h3>
        <p>Data‑driven underwriting discipline with clear guidelines aligned to your growth strategy, tenors and profitability targets.</p>
      </div>
      <div class="card">
        <h3>Transparent Performance</h3>
        <p>Real‑time monitoring and data visibility via live dashboards, ensuring full alignment of interests.</p>
      </div>
      <div class="card">
        <h3>Reinsurance Strategies</h3>
        <p>Tailored reinsurance strategies designed to match your risk profile, capital needs and market positioning.</p>
      </div>
      <div class="card">
        <h3>Market Relationships</h3>
        <p>Strong relationships with leading insurers, reinsurers and brokers to secure competitive, sustainable capacity.</p>
      </div>
    </div>
  </div>
</section>

<section id="team">
  <div class="section-inner">
    <h2>MGA Review &amp; Team</h2>

    <h3>MGA Internal Review</h3>
    <div class="grid-2">
      <div class="card">
        <h4>Underwriting Guidelines</h4>
        <ul>
          <li>Alignment with your growth strategy</li>
          <li>Respect of tenors and target profitability</li>
        </ul>
        <h4>Capacity Needs</h4>
        <ul>
          <li>Capital adequacy for exposures</li>
        </ul>
        <h4>Profitability Forecast</h4>
        <ul>
          <li>Scenario modelling and stress tests</li>
        </ul>
      </div>
      <div class="card">
        <h4>Team Expertise</h4>
        <p>Multidisciplinary team combining underwriting, actuarial, data and claims capabilities.</p>
      </div>
    </div>

    <h3 style="margin-top:30px;">Leadership Team</h3>
    <div class="team-grid">
      <div class="card team-card">
        <h4>Yamilet Morote‑Jagut</h4>
        <div class="team-role">Chief Underwriting Officer – Co‑founder</div>
        <p>Mastère en Management financier international.</p>
        <p>30+ years international experience as Senior Reinsurance &amp; Insurance Underwriter in Surety, Credit, Mortgage &amp; Political Risk.</p>
        <p>Portfolio premium: EUR 13 million. Based in Paris, France.</p>
      </div>
      <div class="card team-card">
        <h4>Cristina Rivas</h4>
        <div class="team-role">Chief Executive Officer – Co‑founder</div>
        <p>Master of Science (MS) in Actuarial Science.</p>
        <p>25+ years of experience with senior roles at Swiss Re and Nacional de Reaseguros, managing portfolios over EUR 360 million.</p>
        <p>55M+ in intermediated premiums across all reinsurance lines. Based in Madrid, Spain.</p>
      </div>
    </div>

    <h3 style="margin-top:30px;">Extended Team</h3>
    <div class="team-grid">
      <div class="card team-card">
        <h4>Lucía González Rodríguez</h4>
        <div class="team-role">Senior Account Executive – Pricing &amp; Data Analyst</div>
      </div>
      <div class="card team-card">
        <h4>Antonio Rito Batalha</h4>
        <div class="team-role">Senior Account Executive – Claims Handling</div>
      </div>
      <div class="card team-card">
        <h4>Javier Quemada Fernández‑Mariña</h4>
        <div class="team-role">Junior Underwriter</div>
      </div>
    </div>
  </div>
</section>

<section id="portfolio">
  <div class="section-inner">
    <h2>Portfolio Assessment &amp; Management</h2>
    <div class="grid-2">
      <div class="card">
        <h3>Risk Evaluation of Cedants</h3>
        <ul>
          <li>Portfolio quality assessment</li>
          <li>Segmentation by product, geography, risk type, tenor and political risk</li>
        </ul>
      </div>
      <div class="card">
        <h3>Performance Analysis</h3>
        <ul>
          <li>Actuarial models</li>
          <li>Loss ratio, combined ratio, benchmarks</li>
        </ul>
      </div>
      <div class="card">
        <h3>Data Collection</h3>
        <ul>
          <li>Underwriting data, loss ratios, exposure</li>
          <li>Bordereaux management</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="strategy">
  <div class="section-inner">
    <h2>Reinsurance Strategy &amp; Placement</h2>

    <div class="grid-2">
      <div class="card">
        <h3>Structures</h3>
        <ul>
          <li><strong>Quota Share</strong>: proportional sharing of premiums and losses</li>
          <li><strong>Excess of Loss</strong>: protection against large individual losses</li>
          <li><strong>Stop Loss</strong>: aggregate protection for portfolio volatility</li>
        </ul>
      </div>
      <div class="card">
        <h3>Strategic Approach</h3>
        <ul>
          <li>Define objectives: balanced credit &amp; surety portfolio</li>
          <li>Structure selection: match risk profile to reinsurance appetite</li>
          <li>Retention optimization: balance retained vs. ceded risk</li>
        </ul>
      </div>
    </div>

    <h3 style="margin-top:30px;">Master Placement Approach</h3>
    <ol style="margin-left:18px; color:#666;">
      <li>A potential list of cedants at your disposal (Annex 1).</li>
      <li>Engage insurers for quotations.</li>
      <li>Prepare submission: portfolio summary, actuarial analysis, deal rationale.</li>
      <li>Negotiate terms, limits and pricing for your convenience.</li>
      <li>Finalize treaty and bind coverage with countersigned agreements.</li>
      <li>Monitor portfolio and bordereaux.</li>
    </ol>
  </div>
</section>

<section id="monitoring">
  <div class="section-inner">
    <h2>Monitoring, Reporting &amp; Competitive Positioning</h2>
    <div class="grid-2">
      <div class="card">
        <h3>Monitoring &amp; Reporting</h3>
        <ul>
          <li>Quarterly bordereaux to reinsurers</li>
          <li>Claims reporting</li>
          <li>Annual performance review and strategy adjustments</li>
        </ul>
      </div>
      <div class="card">
        <h3>Competitive Advantages</h3>
        <ul>
          <li>Advanced analytics and modelling</li>
          <li>Underwriting discipline and governance</li>
          <li>Transparent reporting and reinsurer trust</li>
        </ul>
      </div>
    </div>

    <h3 style="margin-top:30px;">Direct Reinsurer vs. MGA Partnership</h3>
    <p>
      Aurinko Re offers a flexible, partnership‑driven MGA model, combining the technical depth of a reinsurer
      with the agility, proximity and specialization of an MGA dedicated to Credit &amp; Surety.
    </p>
  </div>
</section>

<section id="financials">
  <div class="section-inner">
    <h2>Financial Outlook</h2>
    <p><strong>Target loss ratio &lt; 15%</strong> with sustainable profitability and capital efficiency.</p>

    <div class="kpi-grid">
      <div class="kpi">
        <span>&lt; 15%</span>
        <small>Target Loss Ratio</small>
      </div>
      <div class="kpi">
        <span>€8M → €20M</span>
        <small>Planned GWP (Year 1–3)</small>
      </div>
    </div>

    <table>
      <thead>
        <tr>
          <th></th>
          <th>Year 1</th>
          <th>Year 2</th>
          <th>Year 3</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Asia</td>
          <td>€5,307,720</td>
          <td>€8,400,000</td>
          <td>€10,000,000</td>
        </tr>
        <tr>
          <td>Europe</td>
          <td>€2,692,280</td>
          <td>€5,600,000</td>
          <td>€10,000,000</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <td>Total</td>
          <td>€8,000,000</td>
          <td>€14,000,000</td>
          <td>€20,000,000</td>
        </tr>
      </tfoot>
    </table>
  </div>
</section>

<section id="europe">
  <div class="section-inner">
    <h2>Competitive Surety Reinsurance Programs in Europe</h2>
    <table>
      <thead>
        <tr>
          <th>Country</th>
          <th>Estimated Share</th>
          <th>Estimated EPI 2024 (USD bn)</th>
          <th>Notes</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Germany</td>
          <td>22–25%</td>
          <td>0.95–1.10</td>
          <td>Largest construction market in EU</td>
        </tr>
        <tr>
          <td>France</td>
          <td>18–20%</td>
          <td>0.78–0.88</td>
          <td>Strong public works + mandatory bonds in some sectors</td>
        </tr>
        <tr>
          <td>Italy</td>
          <td>15–17%</td>
          <td>0.65–0.75</td>
          <td>High penetration of surety in public procurement</td>
        </tr>
        <tr>
          <td>Spain</td>
          <td>10–12%</td>
          <td>0.45–0.52</td>
          <td>Green bonds and contractor bonds</td>
        </tr>
        <tr>
          <td>UK</td>
          <td>10–12%</td>
          <td>0.45–0.52</td>
          <td>Large construction + commercial surety</td>
        </tr>
        <tr>
          <td>Benelux</td>
          <td>5–6%</td>
          <td>0.22–0.26</td>
          <td>High credit quality, stable</td>
        </tr>
        <tr>
          <td>Nordics</td>
          <td>4–5%</td>
          <td>0.17–0.22</td>
          <td>Low penetration but growing</td>
        </tr>
        <tr>
          <td>CEE</td>
          <td>4–5%</td>
          <td>0.17–0.22</td>
          <td>Infrastructure‑driven EU</td>
        </tr>
      </tbody>
    </table>

    <h3 style="margin-top:25px;">Asia – Competitive Reinsurance Programs (China 2026)</h3>
    <p>
      Annexes can detail competitive reinsurance programs in China 2026 and a list of potential cedants in
      Credit &amp; Surety with ratings, to support targeted business development.
    </p>
  </div>
</section>

<div class="cta">
  <h2>Let’s build your next Credit &amp; Surety reinsurance program</h2>
  <p>
    Aurinko Re is ready to partner with you to structure disciplined, profitable and sustainable
    Credit &amp; Surety reinsurance solutions across Europe and Asia.
  </p>
  <a href="mailto:info@aurinkore.com">Contact Aurinko Re</a>
</div>

<footer>
  Thank you for your trust – Aurinko Re, Global Specialty Reinsurance MGA.
</footer>

</body>
</html>
