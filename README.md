<!DOCTYPE html><html lang="pt-MZ">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mozal - Produção de Alumínio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header {
      background: #b30000;
      color: white;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
      font-size: 2.5em;
    }
    h2 {
      color: #b30000;
    }
    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
      background: white;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 10px;
      margin-top: 20px;
    }
    label {
      display: block;
      margin-top: 10px;
      font-weight: bold;
    }
    input, select, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background: #b30000;
      color: white;
      border: none;
      padding: 15px;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 20px;
    }
    button:hover {
      background: #800000;
    }
    .vaga {
      border: 1px solid #ddd;
      padding: 15px;
      border-radius: 5px;
      margin-top: 10px;
    }
    .aviso {
      color: red;
      font-weight: bold;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mozal</h1>
    <p>Forjando o futuro de Moçambique através do alumínio!</p>
  </header>  <div class="container">
    <h2>Cadastro de Candidatos</h2>
    <form action="#">
      <label>Nome Completo</label>
      <input type="text" required><label>Número do Bilhete de Identidade</label>
  <input type="text" required>

  <label>Idade (menor de 60 anos)</label>
  <input type="number" max="59" required>

  <label>Naturalidade (nativo de Moçambique)</label>
  <input type="text" required>

  <label>Nível de Escolaridade</label>
  <select required>
    <option value="">Selecione</option>
    <option>Ensino Médio</option>
    <option>Superior Completo</option>
  </select>

  <label>Experiência Prévia (opcional)</label>
  <textarea rows="3"></textarea>

  <label>Anexar Currículo (PDF ou Word)</label>
  <input type="file" accept=".pdf,.doc,.docx" required>

  <label>Contato Telefônico</label>
  <input type="tel" required>

  <button type="submit" onclick="event.preventDefault(); document.getElementById('pagamento').style.display='block';">Continuar</button>
</form>

  </div>  <div class="container" id="pagamento" style="display:none;">
    <h2>Pagamento de Processamento</h2>
    <p>Envie <strong>120 MT</strong> via <strong>M-PESA</strong> para <strong>858218274</strong> para validar sua candidatura.</p>
    <p class="aviso">Candidaturas não pagas serão automaticamente descartadas.</p><label>E-mail (para notificações futuras)</label>
<input type="email" required>

<label>Comprovativo de Pagamento (screenshot M-PESA)</label>
<input type="file" accept="image/*" required>

<button type="submit">Concluir Cadastro</button>

  </div>  <div class="container">
    <h2>Vagas Disponíveis</h2>
    <div class="vaga">
      <strong>Operador de Máquinas Industriais</strong><br>
      Vagas: 30<br>
      Salário: 15.000 MT/mês<br>
      Requisitos: Ensino Médio, treinamento em segurança industrial.
    </div>
    <div class="vaga">
      <strong>Técnico de Manutenção Elétrica</strong><br>
      Vagas: 12<br>
      Salário: 25.000 MT/mês<br>
      Requisitos: Curso técnico em eletrotécnica.
    </div>
    <div class="vaga">
      <strong>Supervisor de Produção</strong><br>
      Vagas: 5<br>
      Salário: 35.000 MT/mês<br>
      Requisitos: Superior em Engenharia Industrial ou 5 anos de experiência.
    </div>
    <div class="vaga">
      <strong>Auxiliar de Armazém</strong><br>
      Vagas: 20<br>
      Salário: 10.500 MT/mês<br>
      Requisitos: Ensino Médio, capacidade para levantar pesos.
    </div>
    <div class="vaga">
      <strong>Analista de Controle de Qualidade</strong><br>
      Vagas: 8<br>
      Salário: 28.000 MT/mês<br>
      Requisitos: Superior em Química/Engenharia de Materiais.
    </div>
    <div class="vaga">
      <strong>Segurança do Trabalho</strong><br>
      Vagas: 7<br>
      Salário: 22.000 MT/mês<br>
      Requisitos: Certificação em NR-12 ou equivalente.
    </div>
  </div>
</body>
</html>