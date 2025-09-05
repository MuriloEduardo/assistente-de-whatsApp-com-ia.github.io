<!-- Bootstrap 5 -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">

<!-- Estilo profissional e responsivo -->
<style>
  :root{--brand-1:#0d6efd;--accent:#ffb703;--muted:#6c757d}
  body{font-family:'Inter',system-ui,Segoe UI,Roboto,Arial;background:#f7f9fb;color:#212529;margin:0}
  .site-header{background:#fff;border-bottom:1px solid #e9eef3}
  .container-narrow{max-width:1100px;margin:0 auto}
  .hero{background:linear-gradient(135deg,#4facfe 0%,#00f2fe 100%);color:#fff;padding:5rem 1rem;border-radius:0 0 36% 36% / 6%;text-align:center}
  .hero h1{font-size:2.1rem;font-weight:800;margin-bottom:.25rem}
  .hero p.lead{font-size:1.1rem;opacity:.95}
  .btn-cta{font-weight:600;border-radius:40px;padding:.75rem 1.6rem}
  .features .card{border-radius:14px;box-shadow:0 6px 18px rgba(17,24,39,.06);border:0}
  .section{padding:3.5rem 1rem}
  .section-title{font-size:1.6rem;font-weight:700;text-align:center;margin-bottom:1.5rem}
  /* Testimonial: light card with strong contrast for readability */
  .testimonial{
    font-style:italic;
    background:#e9fbff; /* soft, readable card */
    color:#032b3a; /* dark teal for high contrast */
    padding:1.25rem 1.5rem;
    border-radius:10px;
    display:inline-block;
    max-width:880px;
    margin:0 auto;
    box-shadow:0 6px 18px rgba(2,12,20,0.06);
    line-height:1.6;
  }
  .testimonial .blockquote-footer{
    display:block;
    margin-top:1rem;
    background:rgba(3,43,58,0.04);
    color:#05414f;
    padding:.5rem .9rem;
    border-radius:6px;
    font-weight:600;
  }
  .testimonial cite{color:#035463}
  footer{background:#0b1720;color:#e6eef6;padding:2rem 1rem}
  .muted{color:var(--muted)}
  @media(min-width:768px){.hero h1{font-size:2.6rem}}
  /* form styles */
  .form-outline{background:#fff;padding:1rem;border-radius:12px;box-shadow:0 6px 18px rgba(17,24,39,.04)}
</style>

<!-- Header -->
<header class="site-header">
  <div class="container container-narrow d-flex align-items-center justify-content-between py-3">
    <a href="#" class="h5 mb-0 text-decoration-none text-dark fw-bold">Assistente de WhatsApp com IA</a>
    <nav class="d-none d-md-flex gap-2 align-items-center">
      <a class="btn btn-outline-primary btn-sm" href="#planos">Planos</a>
      <a class="btn btn-warning btn-sm text-dark" href="#lead-form">Testar grátis</a>
    </nav>
  </div>
</header>

<!-- Hero -->
<section class="hero" aria-labelledby="hero-title">
  <div class="container container-narrow">
    <h1 id="hero-title">🏨 Transforme seu WhatsApp em um atendente 24/7 com IA</h1>
    <p class="lead">Mais reservas, hóspedes satisfeitos e menos tempo perdido respondendo perguntas repetitivas.</p>
    <div class="mt-3">
      <a href="#lead-form" class="btn btn-warning btn-cta me-2">📲 Quero testar grátis</a>
      <a href="#planos" class="btn btn-outline-light btn-cta">Ver planos</a>
    </div>
  </div>
</section>

<!-- Problema -->
<section class="section">
  <div class="container container-narrow">
    <h2 class="section-title">O problema</h2>
    <div class="row text-center g-3">
      <div class="col-6 col-md-3 muted">📩 Mensagens sem resposta durante a noite</div>
      <div class="col-6 col-md-3 muted">🔁 Perguntas repetitivas todos os dias</div>
      <div class="col-6 col-md-3 muted">⏱️ Perda de reservas pela demora</div>
      <div class="col-6 col-md-3 muted">⭐ Avaliações negativas pela falta de agilidade</div>
    </div>
  </div>
</section>

<!-- Solução -->
<section class="section bg-white">
  <div class="container container-narrow">
    <h2 id="solucao" class="section-title">Nossa solução</h2>
    <div class="row g-4 features">
      <div class="col-md-3">
        <div class="card p-3 text-center">
          <div class="h3">🤖</div>
          <h5 class="mt-2">Assistente Virtual</h5>
          <p class="muted small">Respostas instantâneas 24/7</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card p-3 text-center">
          <div class="h3">📅</div>
          <h5 class="mt-2">Reservas diretas</h5>
          <p class="muted small">Sem perder clientes</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card p-3 text-center">
          <div class="h3">🌍</div>
          <h5 class="mt-2">Múltiplos idiomas</h5>
          <p class="muted small">Ideal para turistas</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card p-3 text-center">
          <div class="h3">📊</div>
          <h5 class="mt-2">Relatórios</h5>
          <p class="muted small">Insights de hóspedes</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Prova Social -->
<section class="section">
  <div class="container container-narrow text-center">
    <h2 class="section-title">O que dizem nossos clientes</h2>
    <blockquote class="blockquote testimonial">
      “Desde que ativamos o assistente, 80% das dúvidas são respondidas automaticamente e aumentamos em 25% nossas reservas diretas.”
      <footer class="blockquote-footer mt-3">Hotel Cliente — <cite>Pousada Exemplo</cite></footer>
    </blockquote>
  </div>
</section>

<!-- Planos -->
<section id="planos" class="section bg-light">
  <div class="container container-narrow">
    <h2 class="section-title">Escolha seu plano</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card p-4 text-center">
          <h4 class="fw-bold">🔹 Básico</h4>
          <p class="muted">WhatsApp automatizado 24h</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card p-4 text-center">
          <h4 class="fw-bold">🔸 Avançado</h4>
          <p class="muted">+ Reservas diretas + relatórios</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card p-4 text-center">
          <h4 class="fw-bold">🌟 Premium</h4>
          <p class="muted">+ Upsell automático + IA customizada</p>
        </div>
      </div>
    </div>
    <div class="text-center mt-4">
      <a href="#lead-form" class="btn btn-success btn-lg btn-cta">👉 Quero começar agora</a>
    </div>
  </div>
</section>

<!-- Captura de Leads -->
<section id="lead-form" class="section">
  <div class="container container-narrow">
    <h2 class="section-title">Receba sua demonstração grátis</h2>
    <form class="row g-3 justify-content-center form-outline" method="post" action="#">
      <div class="col-12 col-md-4">
        <label class="form-label visually-hidden" for="name">Seu Nome</label>
        <input id="name" name="name" type="text" class="form-control" placeholder="Seu Nome" required>
      </div>
      <div class="col-12 col-md-4">
        <label class="form-label visually-hidden" for="email">Seu E-mail</label>
        <input id="email" name="email" type="email" class="form-control" placeholder="Seu E-mail" required>
      </div>
      <div class="col-12 col-md-4">
        <label class="form-label visually-hidden" for="whatsapp">WhatsApp</label>
        <input id="whatsapp" name="whatsapp" type="tel" class="form-control" placeholder="WhatsApp" required>
      </div>
      <div class="col-12 col-md-4">
        <label class="form-label visually-hidden" for="type">Tipo de negócio</label>
        <select id="type" name="type" class="form-select" aria-label="Tipo de negócio">
          <option value="">Tipo de negócio</option>
          <option>Hotel</option>
          <option>Pousada</option>
          <option>Airbnb</option>
        </select>
      </div>
      <div class="col-12 col-md-4 d-grid">
        <button type="submit" class="btn btn-primary btn-lg">Receber demonstração grátis</button>
      </div>
    </form>
  </div>
</section>

<!-- Rodapé -->
<footer>
  <div class="container container-narrow text-center">
    <h4 class="mb-1">⚡ Não perca mais reservas por falta de atendimento</h4>
    <p class="muted mb-2">Tenha um número exclusivo no WhatsApp com IA em até 48h.</p>
    <a href="#lead-form" class="btn btn-warning btn-cta">📲 Quero meu assistente agora</a>
  </div>
</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
