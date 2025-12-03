<div style="font-family: Arial, Helvetica, sans-serif; line-height: 1.6; color:#222;">

<!-- TÍTULO PRINCIPAL -->
<h1 style="font-size:32px; font-weight:700; margin-bottom:0;">
Análise Estratégica de Mercado Internacional – Online Retail
</h1>
<p style="font-size:16px; margin-top:5px; color:#444;">
Projeto de Data Analytics para suporte a decisões de Branding, Marketing e Expansão Internacional.
</p>

<hr style="border:0; border-top:1px solid #ccc; margin:30px 0;">


<!-- SECÇÃO -->
<h2 style="font-size:24px; font-weight:700; margin-bottom:10px;">1. Descrição Geral</h2>

<p>
Este repositório apresenta uma análise estratégica do dataset <strong>Online Retail</strong>, com foco na compreensão do desempenho por país, comportamento de clientes, sazonalidade e impacto dos produtos na receita. 
O objetivo é transformar indicadores comerciais em diretrizes práticas e acionáveis para Branding, Marketing e expansão de mercados.
</p>


<hr style="border:0; border-top:1px solid #e5e5e5; margin:25px 0;">


<!-- SECÇÃO -->
<h2 style="font-size:24px; font-weight:700; margin-bottom:10px;">2. Estrutura da Análise</h2>

<h3 style="font-size:18px; font-weight:600;">2.1 Preparação dos Dados</h3>
<ul>
  <li>Correção de colunas e remoção de registos inválidos</li>
  <li>Conversão rigorosa de datas</li>
  <li>Construção da métrica <code>Revenue</code></li>
  <li>Filtragem de transações não comerciais</li>
</ul>

<h3 style="font-size:18px; font-weight:600;">2.2 Análise de Mercados</h3>
<p>Avaliação de Receita Total e Ticket Médio (AOV), classificando cada país em posições estratégicas.</p>

<table style="border-collapse: collapse; width: 100%; margin: 10px 0;">
  <thead>
    <tr style="background:#f2f2f2; text-align:left;">
      <th style="padding:8px; border:1px solid #ddd;">Posição</th>
      <th style="padding:8px; border:1px solid #ddd;">Países</th>
      <th style="padding:8px; border:1px solid #ddd;">Interpretação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding:8px; border:1px solid #ddd;">Domínio do Volume</td>
      <td style="padding:8px; border:1px solid #ddd;">Reino Unido</td>
      <td style="padding:8px; border:1px solid #ddd;">Maior receita total e dependência elevada</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ddd;">Domínio do Valor</td>
      <td style="padding:8px; border:1px solid #ddd;">EIRE, Países Baixos</td>
      <td style="padding:8px; border:1px solid #ddd;">Alta margem e clientes premium</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ddd;">Potencial Inexplorado</td>
      <td style="padding:8px; border:1px solid #ddd;">Alemanha, França</td>
      <td style="padding:8px; border:1px solid #ddd;">Baixa penetração, oportunidade de crescimento</td>
    </tr>
  </tbody>
</table>

<h3 style="font-size:18px; font-weight:600;">2.3 Segmentação RFM</h3>
<ul>
  <li>Recência média elevada → baixa atividade recente</li>
  <li>Frequência mediana de 2 compras → oportunidade de recorrência</li>
  <li>Receita concentrada em clientes de alto valor</li>
</ul>

<h3 style="font-size:18px; font-weight:600;">2.4 Sazonalidade</h3>
<ul>
  <li>Picos consistentes em Outubro e Novembro</li>
  <li>Início do ano com foco em retenção</li>
</ul>

<h3 style="font-size:18px; font-weight:600;">2.5 Análise de Produtos</h3>
<ul>
  <li><strong>White Hanging Heart T-Light Holder</strong></li>
  <li><strong>Jumbo Bag Red Retrospot</strong></li>
</ul>

<hr style="border:0; border-top:1px solid #e5e5e5; margin:25px 0;">


<!-- SECÇÃO -->
<h2 style="font-size:24px; font-weight:700; margin-bottom:10px;">3. Principais Resultados</h2>

<h3 style="font-size:18px; font-weight:600;">3.1 Mercado</h3>
<ul>
  <li>Dependência elevada do Reino Unido</li>
  <li>Mercados premium identificados: EIRE e Países Baixos</li>
  <li>Alemanha com espaço claro de crescimento</li>
</ul>

<h3 style="font-size:18px; font-weight:600;">3.2 Clientes</h3>
<ul>
  <li>Elevada proporção de clientes inativos</li>
  <li>Segmentos premium concentrados em mercados de alto valor</li>
</ul>

<h3 style="font-size:18px; font-weight:600;">3.3 Produtos</h3>
<ul>
  <li>Dois produtos concentram volume e receita</li>
  <li>Essenciais para campanhas e comunicação</li>
</ul>

<hr style="border:0; border-top:1px solid #e5e5e5; margin:25px 0;">


<!-- SECÇÃO -->
<h2 style="font-size:24px; font-weight:700; margin-bottom:10px;">4. Stack Tecnológica</h2>

<ul>
  <li>Python</li>
  <li>Pandas, NumPy</li>
  <li>Plotly, Matplotlib, Seaborn</li>
  <li>Jupyter Notebook</li>
</ul>

<hr style="border:0; border-top:1px solid #e5e5e5; margin:25px 0;">


<!-- SECÇÃO -->
<h2 style="font-size:24px; font-weight:700; margin-bottom:10px;">5. Estrutura do Repositório</h2>

<pre style="background:#f7f7f7; padding:12px; border:1px solid #ddd; border-radius:4px;">
/notebooks
    analise_online_retail.ipynb
/figures
    (gráficos exportados)
README.md
</pre>

<hr style="border:0; border-top:1px solid #ccc; margin:30px 0;">


<!-- AUTOR -->
<h2 style="font-size:24px; font-weight:700; margin-bottom:10px;">6. Autor</h2>

<p><strong>Daniel Amorim</strong><br>
Analista de Dados • Branding e Marketing Analytics<br>
Email: dsamorim686@gmail.com<br>
LinkedIn: https://linkedin.com/in/danieloamorim
</p>

</div>
