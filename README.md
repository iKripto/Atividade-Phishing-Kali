<h1> Criação de um Phishing com o Zphisher</h1>
<p>O Zphisher é uma ferramenta de código aberto usada para fins educacionais e de teste de engenharia social, especialmente para demonstrar phishing (ataques de clonagem de páginas de login). Ela cria páginas falsas de login (como Facebook, Instagram, etc.) e simula ataques para você estudar como esses ataques funcionam.</p>

<h3>⚠️ Atenção:</h3>
<p>O uso do Zphisher em pessoas reais sem consentimento é crime, podendo levar a prisão e multas. Ele deve ser usado somente em ambientes de teste ou com autorização formal.</p>

<h1></h1>
<h3>Instalação:</h3>
<p>No terminal, digitamos:</p>
<p>sudo su</p>
<p>git clone https://github.com/htr-tech/zphisher.git</p>
<p>cd zphisher</p>
<p>bash zphisher.sh</p>

<h3>Execução:</h3>
<p>Ao iniciar o Zphisher, ele abrirá um menu com várias opções de sites que podemos utilizar.</p>
<p>1.Escolhemos o facebook.</p>
<p>2.Escolhemos a opção "Traditional login page".</p>
<p>3.Escolhemos a opção "Localhost".</p>
<p>4.Acessando o link pelo navegador, temos uma página do facebook para preencher informações.</p>
<p>6.Selecione a segunda opção: Website Attack Vectors</p>
<p>7.Selecione a terceira opção: Credential Harvester Attack Method</p>
<p>8.Selecione a opção: Site Cloner.</p>

<h1></h1>
<h3>Funcionamento:</h3>
<p>Ao acessar o site, teremos algo muito similar ao site original.</p>
<p>Ao preencher as informações e clicar no botão, as credenciais de acesso serão exibidas no terminal do Kali.</p>
<img src="https://github.com/user-attachments/assets/7b2be828-69a8-4567-b8fe-f97ed3d53c01">
<img src="https://github.com/user-attachments/assets/c51e06fe-847b-4341-9ecf-5d11885891b3">



