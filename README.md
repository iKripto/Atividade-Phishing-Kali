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
<p>3.1.No meu caso, utilizei a opção "Cloudflared", pois o localhost não estava funcionando.</p>
<p>4.Acessando o link pelo navegador, temos uma página do facebook para preencher informações.</p>
<p>6.Selecione a segunda opção: Website Attack Vectors</p>
<p>7.Selecione a terceira opção: Credential Harvester Attack Method</p>
<p>8.Selecione a opção: Site Cloner.</p>

<h1></h1>
<h3>Funcionamento</h3>
