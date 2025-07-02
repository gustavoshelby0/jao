
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Dashboard Raiz</title>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet"/>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500;700&family=Roboto+Slab:wght@400;600&display=swap');

  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    font-family: 'Roboto Slab', serif;
    background: #f4f6f8;
    color: #333;
    min-height: 100vh;
  }
  a { color: inherit; text-decoration: none; }

  .sidebar {
    font-family: 'Segoe UI', sans-serif;
    position: fixed;
    top: 0; left: 0;
    width: 240px;
    height: 100vh;
    background-color: #2c3e50;
    color: white;
    display: flex;
    flex-direction: column;
    padding: 20px 0;
    user-select: none;
    z-index: 20;
  }
  .sidebar .logo {
    font-weight: bold;
    font-size: 1.8rem;
    text-align: center;
    margin-bottom: 30px;
  }
  .sidebar nav { flex-grow: 1; }
  .sidebar nav a {
    display: block;
    padding: 12px 30px;
    font-weight: 600;
    font-size: 1rem;
    color: #ecf0f1;
    border-left: 4px solid transparent;
    transition: background-color 0.2s ease, border-color 0.2s ease;
    cursor: pointer;
  }
  .sidebar nav a:hover,
  .sidebar nav a.active {
    background-color: #34495e;
    border-left: 4px solid #1abc9c;
  }
  .sidebar .user-info {
    padding: 15px 30px;
    border-top: 1px solid #34495e;
    font-size: 0.9rem;
    font-style: italic;
  }
  .sidebar .finance {
    padding: 10px 30px;
    font-weight: bold;
    font-size: 1.1rem;
    border-top: 1px solid #34495e;
    color: #1abc9c;
  }

  header {
    position: fixed;
    top: 0; left: 240px; right: 0;
    height: 60px;
    background: white;
    box-shadow: 0 1px 5px rgba(0,0,0,0.1);
    display: flex;
    align-items: center;
    padding: 0 40px;
    z-index: 15;
    user-select: none;
  }
  header h1 {
    font-family: 'Poppins', sans-serif;
    font-weight: 700;
    font-size: 1.6rem;
    color: #2c3e50;
    flex-grow: 1;
  }
  .filters {
    display: flex;
    gap: 15px;
  }
  .filters span {
    padding: 8px 16px;
    font-weight: 600;
    font-family: 'Poppins', sans-serif;
    font-size: 0.9rem;
    color: #7f8c8d;
    border: 1px solid #bdc3c7;
    border-radius: 12px;
    cursor: pointer;
    transition: background-color 0.2s ease, color 0.2s ease;
    white-space: nowrap;
  }
  .filters span.active,
  .filters span:hover {
    background-color: #1abc9c;
    color: white;
    border-color: #16a085;
  }

  main {
    margin-left: 240px;
    margin-top: 60px;
    padding: 30px 40px;
    min-height: calc(100vh - 60px);
    overflow-y: auto;
  }

  .cards {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
    gap: 20px;
    margin-bottom: 40px;
  }
  .card {
    background: white;
    padding: 20px 25px;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.12);
  }
  .card .title {
    font-size: 1rem;
    font-weight: 600;
    color: #7f8c8d;
    font-family: 'Roboto Slab', serif;
    margin-bottom: 8px;
  }
  .card .value {
    font-size: 1.9rem;
    font-weight: 700;
    font-family: 'Poppins', sans-serif;
    color: #2c3e50;
  }

  .sales-section {
    background: white;
    border-radius: 8px;
    padding: 25px 30px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  }
  .sales-section h2 {
    font-family: 'Poppins', sans-serif;
    font-weight: 700;
    font-size: 1.7rem;
    margin-bottom: 25px;
    color: #2c3e50;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    table-layout: fixed;
    word-wrap: break-word;
  }
  thead th {
    text-align: left;
    font-weight: 600;
    font-family: 'Roboto Slab', serif;
    font-size: 0.95rem;
    padding-bottom: 15px;
    border-bottom: 2px solid #ecf0f1;
    color: #7f8c8d;
  }
  tbody tr {
    background: #fdfdfd;
    border-bottom: 1px solid #ecf0f1;
    transition: background-color 0.15s ease;
  }
  tbody tr:hover {
    background-color: #ecf0f1;
  }
  tbody td {
    padding: 12px 15px;
    color: #34495e;
    font-weight: 600;
    font-family: 'Roboto Slab', serif;
    font-size: 0.95rem;
  }
  tbody td:first-child {
    font-weight: 700;
    color: #2c3e50;
  }
  .status-approved { color: #27ae60; font-weight: 700; }
  .status-pending { color: #f39c12; font-weight: 700; }
  .status-refunded { color: #c0392b; font-weight: 700; }

  @media (max-width: 600px) {
    .sidebar {
      position: relative;
      width: 100%;
      height: auto;
      flex-direction: row;
      padding: 10px 0;
      overflow-x: auto;
      z-index: 15;
    }
    .sidebar .logo {
      flex: 0 0 auto;
      margin: 0 15px;
      line-height: 40px;
    }
    .sidebar nav {
      display: flex;
      gap: 8px;
      overflow-x: auto;
      padding: 0 10px;
      flex-grow: 1;
    }
    .sidebar nav a {
      padding: 8px 12px;
      font-size: 0.9rem;
      border-left: none;
      white-space: nowrap;
      flex-shrink: 0;
    }
    .sidebar nav a.active,
    .sidebar nav a:hover {
      background-color: #16a085;
      color: white;
      border-left: none;
    }
    header {
      left: 0;
      width: 100%;
      padding: 0 20px;
    }
    main {
      margin-left: 0;
      margin-top: 60px;
      padding: 20px;
      min-height: calc(100vh - 60px);
    }
    .cards { grid-template-columns: 1fr; gap: 15px; }
    table { font-size: 0.85rem; }
    thead { display: none; }
    tbody tr {
      display: block;
      margin-bottom: 15px;
      border-bottom: 2px solid #ecf0f1;
    }
    tbody td {
      display: flex;
      justify-content: space-between;
      padding: 8px 10px;
      border: none;
      font-weight: 600;
    }
    tbody td:first-child {
      font-weight: 700;
      color: #2c3e50;
    }
  }
</style>
</head>
<body>

<!-- Restante do HTML permanece inalterado -->


<!-- Sidebar substituída pelo modelo salvo -->
<div class="sidebar">
  <div class="logo">WORKFLOW</div>
  <nav>
    <a href="#" data-url="https://segredosedutor.com/plataforma/dashboard" class="active"><i class="fas fa-home"></i> Dashboard</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/produtos"><i class="fas fa-box-open"></i> Produtos</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/areademembros"><i class="fas fa-users"></i> Área de Membros</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/marketplace"><i class="fas fa-store"></i> Marketplace</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/meusafiliados"><i class="fas fa-user-friends"></i> Meus Afiliados</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/vendas"><i class="fas fa-shopping-cart"></i> Vendas</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/assinaturas"><i class="fas fa-file-invoice-dollar"></i> Assinaturas</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/financeiro"><i class="fas fa-wallet"></i> Financeiro</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/relatorios"><i class="fas fa-chart-line"></i> Relatórios</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/colaboradores"><i class="fas fa-user-cog"></i> Colaboradores</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/apps"><i class="fas fa-th-large"></i> Apps</a>
    <a href="#" data-url="https://segredosedutor.com/plataforma/ajuda"><i class="fas fa-question-circle"></i> Ajuda</a>
  </nav>
  <div class="user-info"></div>
  <div class="finance"></div>
</div>

<!-- restante do código permanece o mesmo -->


<header>
  <h1>Dashboard</h1>
  <div class="filters">
    <span class="active">Hoje</span>
    <span>Todos os produtos</span>
    <span>Todas as moedas</span>
  </div>
</header>

<main>
  <section class="cards">
    <div class="card">
      <div class="title">Valor líquido</div>
      <div class="value">R$ 0,00</div>
    </div>
    <div class="card">
      <div class="title">Vendas</div>
      <div class="value">0</div>
    </div>
    <div class="card">
      <div class="title">Aprovação cartão</div>
      <div class="value">0 %</div>
    </div>
    <div class="card">
      <div class="title">Reembolso</div>
      <div class="value">0 %</div>
    </div>
    <div class="card">
      <div class="title">Chargeback</div>
      <div class="value">0 %</div>
    </div>
    <div class="card">
      <div class="title">Vendas 1-click da rede Kiwify</div>
      <div class="value">R$ 0,00</div>
    </div>
    <div class="card">
      <div class="title">Conversão boleto</div>
      <div class="value">0 %</div>
    </div>
    <div class="card">
      <div class="title">Boletos gerados</div>
      <div class="value">0</div>
    </div>
  </section>

  <section class="sales-section">
    <h2>Vendas Recentes</h2>
    <table>
      <thead>
        <tr>
          <th>Cliente</th>
          <th>Produto</th>
          <th>Data</th>
          <th>Status</th>
          <th>Valor</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>João Silva</td>
          <td>Curso Avançado</td>
          <td>22/06/2025</td>
          <td class="status-approved">Aprovado</td>
          <td>R$ 299,00</td>
        </tr>
        <tr>
          <td>Maria Souza</td>
          <td>Assinatura Mensal</td>
          <td>21/06/2025</td>
          <td class="status-pending">Pendente</td>
          <td>R$ 49,90</td>
        </tr>
        <tr>
          <td>Pedro Santos</td>
          <td>eBook Completo</td>
          <td>20/06/2025</td>
          <td class="status-refunded">Reembolsado</td>
          <td>R$ 19,90</td>
        </tr>
        <tr>
          <td>Ana Lima</td>
          <td>Curso Iniciante</td>
          <td>19/06/2025</td>
          <td class="status-approved">Aprovado</td>
          <td>R$ 199,00</td>
        </tr>
        <tr>
          <td>Carlos Alves</td>
          <td>Consultoria VIP</td>
          <td>18/06/2025</td>
          <td class="status-pending">Pendente</td>
          <td>R$ 999,00</td>
        </tr>
      </tbody>
    </table>
  </section>
</main>

<script type="e018a157e93da3e89f49bce3-text/javascript">
  // Redireciona ao clicar nos links da sidebar
  document.querySelectorAll('.sidebar nav a').forEach(link => {
    link.addEventListener('click', e => {
      e.preventDefault();
      const url = link.getAttribute('data-url');
      if (url) {
        window.location.href = url;
      }
    });
  });
</script>

<script src="/cdn-cgi/scripts/7d0fa10a/cloudflare-static/rocket-loader.min.js" data-cf-settings="e018a157e93da3e89f49bce3-|49" defer></script><script defer src="https://static.cloudflareinsights.com/beacon.min.js/vcd15cbe7772f49c399c6a5babf22c1241717689176015" integrity="sha512-ZpsOmlRQV6y907TI0dKBHq9Md29nnaEIPlkf84rnaERnq6zvWvPUqr2ft8M1aS28oN72PdrCzSjY4U6VaAw1EQ==" data-cf-beacon='{"rayId":"958a80eccc286445","version":"2025.6.2","r":1,"token":"c367ce9b55d746148957826b60c83547","serverTiming":{"name":{"cfExtPri":true,"cfEdge":true,"cfOrigin":true,"cfL4":true,"cfSpeedBrain":true,"cfCacheStatus":true}}}' crossorigin="anonymous"></script>
</body>
</html>
