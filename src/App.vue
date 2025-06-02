<template>
  <div id="app">
    <div id="main-container" class="container">
      <div id="topicos-container" class="topicos-anuncios">
        <div id="topico-principal" class="ultimo-topico">
          <div id="topico-header" class="header-topico">
            <div id="author-info" class="flex" style="display: flex; gap: 15px;">
              <div id="author-avatar" class="skin-logo"></div>
              <div id="author-details" class="header-postado">
                <p>Postado por yBlokzin</p>
                <div id="post-date" class="header-data">
                  <p>02 de Jun. de 2025</p>
                </div>
              </div>
            </div>
          </div>
          <div id="topico-banner" class="header-faixa">
            <div id="banner-content" class="header-faixa-badge">
              <p style="text-transform: uppercase;">Sugestão</p>
              <div id="banner-title" class="header-faixa-title">
                <p>Reconexão em partidas</p>
              </div>
            </div>
          </div>
          <div id="topico-content" class="conteudo-topico">
    
            <span id="intro-text" style="color: #2b2b2b;"><strong>A reconexão em partidas auxiliam em situações adversas que acabam desconectando o jogador do servidor</strong> e permitem que o jogador, ao desconectar de alguma partida pertencente em andamento, ele consiga ao logar novamente no servidor, retornar a partida em andamento. Com o sistema, não é necessário nenhum uso de comandos, basta retornar ao servidor que ele levará a partida em formato de respawn no Bed Wars e na última posição no Sky Wars.</span>
        <div  class="image"></div>
          <br>
        <span style="color: #2b2b2b;">
 Além disso, o sistema identifica automaticamente a partida anterior, evitando frustrações e reduzindo o tempo fora do jogo. Essa funcionalidade reforça o compromisso com a estabilidade e a continuidade da jogabilidade, especialmente em modos competitivos e ranqueados.
</span>

        <div class="btn btn-primary botao-reconexao">Reconexão a partida de modo rápido</div>

          <br>
        <span style="color: #2b2b2b;">
 Em cenário real: o jogador yBlokzin está com a internet instável e acaba desconectando de uma partida de Bed Wars. Ao reconectar ao servidor, ele é automaticamente levado de volta à partida em andamento, permitindo que continue jogando sem interrupções. Isso melhora a experiência do usuário e mantém a competitividade do jogo.
</span>

<div class="reconnection-ui-container" style="margin-top: 30px;">
    <div class="reconnection-header">
        <div class="icon-container">
            <svg class="reconnect-icon" viewBox="0 0 24 24">
                <path d="M12,9C10.34,9 9,10.34 9,12C9,13.66 10.34,15 12,15C13.66,15 15,13.66 15,12C15,10.34 13.66,9 12,9M12,17.5C8.69,17.5 6,14.81 6,11.5C6,8.19 8.69,5.5 12,5.5C15.31,5.5 18,8.19 18,11.5C18,14.81 15.31,17.5 12,17.5M12,4A8,8 0 0,0 4,12A8,8 0 0,0 12,20A8,8 0 0,0 20,12A8,8 0 0,0 12,4Z" />
                <path class="animated-path" d="M12,9C10.34,9 9,10.34 9,12C9,13.66 10.34,15 12,15C13.66,15 15,13.66 15,12C15,10.34 13.66,9 12,9M12,17.5C8.69,17.5 6,14.81 6,11.5C6,8.19 8.69,5.5 12,5.5C15.31,5.5 18,8.19 18,11.5C18,14.81 15.31,17.5 12,17.5M12,4A8,8 0 0,0 4,12A8,8 0 0,0 12,20A8,8 0 0,0 20,12A8,8 0 0,0 12,4Z" />
            </svg>
            <div class="pulse-effect"></div>
        </div>
        <h2 class="reconnection-title">Reconexão de Partidas</h2>
    </div>

    <div class="reconnection-content">
        <p class="reconnection-text highlighted">
            <span class="feature-icon"></span>
            A reconexão em partidas é um diferencial exclusivo que permite ao jogador, após desconectar de uma partida em andamento, retornar automaticamente ao jogo ao se reconectar ao servidor.
        </p>

        <div class="game-modes">
            <div class="game-mode">
                <div class="mode-icon">🛏️</div>
                <h4>Bed Wars</h4>
                <p>Reconexão com respawn automático</p>
            </div>
            <div class="game-mode">
                <div class="mode-icon">☁️</div>
                <h4>Sky Wars</h4>
                <p>Retorno à última posição registrada</p>
            </div>
        </div>


        <div class="benefits-box">
            <h4>Vantagens:</h4>
            <ul>
                <li>Zero comandos necessários - tudo acontece automaticamente</li>
                <li>Mantém sua posição em partidas ranqueadas</li>
                <li>Reduz frustrações por desconexões acidentais</li>
                <li>Garante continuidade na jogabilidade competitiva</li>
            </ul>
        </div>
        

    </div>
    
</div>
<br>
           <span style="color: #2b2b2b;">
 O sistema de reconexão, auxilia tanto na forma de não perder o progresso da partida, quanto na forma de ainda tentar voltar a mesma devido a alguma instabilidade ou desconexão de forma não proposital.
</span>
<br>
<br>
           <span style="color: #2b2b2b;">
 Tópico hospedado - será descontinuado em alguns dias.<br>Sugestão para o servidor Lugin - Servidor de Minecraft
</span>


          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.reconnection-ui-container {
    max-width: 800px;
    margin: 0 auto;
    background: linear-gradient(135deg, #f8f9fa 0%, #ffffff 100%);
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    overflow: hidden;
    border: 1px solid #e0e0e0;
}

.reconnection-header {
    background: linear-gradient(135deg, #3498db 0%, #001fff 100%);
    color: white;
    
    padding: 25px;
    text-align: center;
    position: relative;
}

.reconnection-title {
    margin: 15px 0 0;
    font-size: 28px;
    font-weight: 700;
}

.icon-container {
    position: relative;
    width: 80px;
    height: 80px;
    margin: 0 auto;
}

.reconnect-icon {
    width: 100%;
    height: 100%;
    fill: white;
    position: relative;
    z-index: 2;
}

.animated-path {
    animation: rotate 2s linear infinite;
    transform-origin: center;
    opacity: 0.7;
}

.pulse-effect {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255,255,255,0.2);
    border-radius: 50%;
    animation: pulse 2s infinite;
    z-index: 1;
}

.reconnection-content {
    padding: 25px;
}

.reconnection-text {
    font-size: 16px;
    line-height: 1.7;
    margin-bottom: 20px;
    position: relative;
    padding-left: 35px;
}

.reconnection-text.highlighted {
    background-color: #f0f8ff;
    padding: 15px 20px 15px 55px;
    border-radius: 8px;
    border-left: 4px solid #3498db;
}

.feature-icon {
    position: absolute;
    left: 0;
    top: 0;
    font-size: 24px;
}

.game-modes {
    display: flex;
    justify-content: space-between;
    margin: 25px 0;
    gap: 20px;
}

.game-mode {
    flex: 1;
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    text-align: center;
    transition: transform 0.3s;
}

.game-mode:hover {
    transform: translateY(-5px);
}

.mode-icon {
    font-size: 40px;
    margin-bottom: 10px;
}

.game-mode h4 {
    margin: 10px 0;
    color: #2c3e50;
}

.game-mode p {
    font-size: 14px;
    color: #7f8c8d;
    margin: 0;
}

.benefits-box {
    background: #f8f9fa;
    border-radius: 8px;
    padding: 20px;
    margin: 25px 0;
    border-left: 4px solid #2ecc71;
}

.benefits-box h4 {
    margin-top: 0;
    color: #2c3e50;
}

.benefits-box ul {
    padding-left: 20px;
    margin-bottom: 0;
}

.benefits-box li {
    margin-bottom: 8px;
}

.reconnection-cta {
    text-align: center;
    margin-top: 30px;
}

.reconnect-btn {
    background: linear-gradient(135deg, #2ecc71 0%, #27ae60 100%);
    color: white;
    border: none;
    padding: 15px 30px;
    font-size: 18px;
    border-radius: 50px;
    cursor: pointer;
    font-weight: 600;
    display: inline-flex;
    align-items: center;
    gap: 10px;
    box-shadow: 0 4px 15px rgba(46, 204, 113, 0.3);
    transition: all 0.3s;
    position: relative;
    overflow: hidden;
}

.reconnect-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 20px rgba(46, 204, 113, 0.4);
}

.reconnect-btn:active {
    transform: translateY(0);
}

.reconnect-btn.pulse {
    animation: pulse 2s infinite;
}

.btn-icon {
    font-size: 24px;
}

.badge {
    position: absolute;
    top: -10px;
    right: -10px;
    background: #e74c3c;
    color: white;
    border-radius: 20px;
    padding: 3px 8px;
    font-size: 12px;
    font-weight: bold;
}

.small-note {
    font-size: 12px;
    color: #95a5a6;
    margin-top: 10px;
}

@keyframes rotate {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
}

@keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.05); }
    100% { transform: scale(1); }
}

@media (max-width: 768px) {
    .game-modes {
        flex-direction: column;
    }
    
    .reconnection-text {
        padding-left: 30px;
    }
    
    .reconnection-text.highlighted {
        padding: 15px 15px 15px 45px;
    }
}

.reconnection-ui-container {
    max-width: 800px;
    margin: 0 auto;
    background: linear-gradient(135deg, #f8f9fa 0%, #ffffff 100%);
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    overflow: hidden;
    border: 1px solid #e0e0e0;
}

.reconnection-header {
    background: linear-gradient(135deg, #3498db 0%, #001fff 100%);
    color: white;
    padding: 25px;
    text-align: center;
    position: relative;
}

.reconnection-title {
    margin: 15px 0 0;
    font-size: 28px;
    font-weight: 700;
}

.icon-container {
    position: relative;
    width: 80px;
    height: 80px;
    margin: 0 auto;
}

.reconnect-icon {
    width: 100%;
    height: 100%;
    fill: white;
    position: relative;
    z-index: 2;
}

.animated-path {
    animation: rotate 2s linear infinite;
    transform-origin: center;
    opacity: 0.7;
}

.pulse-effect {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255,255,255,0.2);
    border-radius: 50%;
    animation: pulse 2s infinite;
    z-index: 1;
}

.reconnection-content {
    padding: 25px;
}

.reconnection-text {
    font-size: 16px;
    line-height: 1.7;
    margin-bottom: 20px;
    position: relative;
    padding-left: 35px;
}

.reconnection-text.highlighted {
    background-color: #f0f8ff;
    padding: 15px 20px 15px 55px;
    border-radius: 8px;
    border-left: 4px solid #3498db;
}

.feature-icon {
    position: absolute;
    left: 0;
    top: 0;
    font-size: 24px;
}

.game-modes {
    display: flex;
    justify-content: space-between;
    margin: 25px 0;
    gap: 20px;
}

.game-mode {
    flex: 1;
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    text-align: center;
    transition: transform 0.3s;
}

.game-mode:hover {
    transform: translateY(-5px);
}

.mode-icon {
    font-size: 40px;
    margin-bottom: 10px;
}

.game-mode h4 {
    margin: 10px 0;
    color: #2c3e50;
}

.game-mode p {
    font-size: 14px;
    color: #7f8c8d;
    margin: 0;
}

.benefits-box {
    background: #f8f9fa;
    border-radius: 8px;
    padding: 20px;
    margin: 25px 0;
    border-left: 4px solid #2ecc71;
}

.benefits-box h4 {
    margin-top: 0;
    color: #2c3e50;
}

.benefits-box ul {
    padding-left: 20px;
    margin-bottom: 0;
}

.benefits-box li {
    margin-bottom: 8px;
}

.reconnection-cta {
    text-align: center;
    margin-top: 30px;
}

.reconnect-btn {
    background: linear-gradient(135deg, #2ecc71 0%, #27ae60 100%);
    color: white;
    border: none;
    padding: 15px 30px;
    font-size: 18px;
    border-radius: 50px;
    cursor: pointer;
    font-weight: 600;
    display: inline-flex;
    align-items: center;
    gap: 10px;
    box-shadow: 0 4px 15px rgba(46, 204, 113, 0.3);
    transition: all 0.3s;
    position: relative;
    overflow: hidden;
}

.reconnect-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 20px rgba(46, 204, 113, 0.4);
}

.reconnect-btn:active {
    transform: translateY(0);
}

.reconnect-btn.pulse {
    animation: pulse 2s infinite;
}

.btn-icon {
    font-size: 24px;
}

.badge {
    position: absolute;
    top: -10px;
    right: -10px;
    background: #e74c3c;
    color: white;
    border-radius: 20px;
    padding: 3px 8px;
    font-size: 12px;
    font-weight: bold;
}

.small-note {
    font-size: 12px;
    color: #95a5a6;
    margin-top: 10px;
}

@keyframes rotate {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
}

@keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.05); }
    100% { transform: scale(1); }
}

@media (max-width: 768px) {
    .game-modes {
        flex-direction: column;
    }
    
    .reconnection-text {
        padding-left: 30px;
    }
    
    .reconnection-text.highlighted {
        padding: 15px 15px 15px 45px;
    }
}
.botao-reconexao {
  text-align: center;
  width: 300px;
  margin: 0 auto;
  margin-top:30px;
}
.image {
  background-image: url("https://i.imgur.com/2v939HS.png");
  height: 300px;
  width: 100%;
  margin-top: 20px;
  background-size: cover;
  background-position: center;
  border-radius: 5px;
}
.ultimas-novidades-list {
  padding: 1.5em;
  margin-top: -40px;
  line-height: 20.5px;
  color: white;
  font-size: 16px;
}
#highlight-image {
  width: 200px;
  max-width: 300px;
  height: auto;
  display: block;
  margin: 0 auto;
}

@media (min-width: 600px) {
  #highlight-image {
    max-width: 100%;
    width: auto;
    max-height: 300px;
  }
}
.ultimas-novidades-title {
  font-size: 22px;
  padding: 1em;
  font-weight: 500;
  color: white;
}
.continuar-lendo {
  margin-top: 30px;
  text-align: center;
}
.btn {
    padding: 15px;
    font-size: 16px;
    border-radius: 5px;
    line-height: 16px;
    background-color: #0095fd;
    margin-bottom: 12px;
}
.btn-primary {
    color: #fff;
    background-color: #0095fd;
}
.btn {
    border-radius: 5px;
    border: 0;
    text-decoration: none !important;
    font-weight: 300;
}
.conteudo-topico {
    font-size: 17px;
    line-height: 1.6;
    color: rgb(74, 74, 74);
    padding: 25px;
}
.header-faixa-title {
  font-size: 26px;
    font-weight: bold;
    color: #fff;
    margin-top:-10px;
}
.header-faixa-badge {
    font-size: 18px;
    font-weight: 300;
    color: white;
    padding: 0.1em 1em;
}
.header-faixa {
  margin-top: 10px;
  width: 100%;
  height: 70px;
  background-color: #2b2b2b;
}
.header-data {
  color: gray;
  margin-top: -10px;
}
.header-postado {
    font-size: 16px;
    margin-top: 10px;
    color: #2b2b2b;
    margin-top: -0px;
    font-weight: normal;
}
.header-topico {
  padding: 15px;
}
.skin-logo {
    border-radius: 5px;
    width: 70px;
    background-image: url('https://cravatar.eu/helmavatar/yBlokzin/190.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    height: 70px;
}
.topicos-anuncios {
  max-width: 815px;
}
.ultimo-topico {
  box-shadow: 0px 3px 12px -3px rgba(0, 0, 0, 0.5);
  background: #fff;
    border-radius: 5px;
    width: 100%;
    margin-bottom: 30px;
    margin-top: 20px;
    height: 100%;
}

.noticia-grande,
.noticia-menor {
  position: relative;
  border-radius: 5px;
  overflow: hidden;
  background-color: #000;
  box-shadow: rgba(0, 0, 0, 0.5) 0px 3px 12px -3px;
  display: flex;
  align-items: flex-end;
  color: white;
  cursor: pointer;
}
.noticia-grande::before,
.noticia-menor::before,
.promocao::before {
  content: "";
  position: absolute;
  inset: 0;
  background-size: cover;
  background-position: center;
  transition: transform 0.4s ease;
  z-index: 0;
}
.noticia-grande::before {
  background-image: linear-gradient(rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.65) 89%, rgba(0, 0, 0, 0.75) 100%),
    url("https://i.imgur.com/FdU5YNG.jpg");
}
.bedwars::before {
  background-image: linear-gradient(rgba(0, 0, 0, 0) 40%, rgba(0, 0, 0, 0.75) 100%),
    url("https://i.imgur.com/idG7Gr7.jpg");
}
.discord::before {
  background-image: linear-gradient(rgba(0, 0, 0, 0) 40%, rgba(0, 0, 0, 0.75) 100%),
    url("https://i.imgur.com/3G0EbXZ.jpg");
}
.noticia-grande:hover::before,
.noticia-menor:hover::before,
.promocao:hover::before {
  transform: scale(1.05);
}
.noticia-conteudo {
  position: relative;
  z-index: 1;
  padding: 1em;
  width: 100%;
}
.nosso-ip-subtitle-recomendacao {
  font-size: 16px;
  margin-top: 20px;
    display: block;
    color: rgb(75, 75, 75);
    font-weight: 300;
}
.nosso-ip-subtitle {
  font-size: 16px;
    display: block;
    color: gray;
    font-weight: 300;
}
.nosso-ip-title {
  font-size: 22px;
  font-weight: bold;
  margin-top: -10px;
  margin-bottom: 15px;
}
.nosso-ip-container {
  margin: 0 auto;
  padding: 50px;
  text-align: center;
}
.nosso-ip {
  width: 385px;
    height: 300px;
    background: white;
    border-radius: 3px;
    margin-top: 20px;
    box-shadow: 0px 3px 12px -3px rgba(0, 0, 0, 0.5);
}
.noticia-grande {
  width: 402px;
  height: 460px;
}
.noticia-menor {
  width: 400px;
  height: 225px;
}
.coluna-menores {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
.categoria {
  font-size: 22px;
  font-weight: 300;
}
.titulo {
  text-transform: uppercase;
  font-size: 26px;
  font-weight: bold;
  margin-top: -20px;
}
.topicos-recentes {
    padding: 20px;
    margin-bottom: -30px;
    padding-bottom: 5px;
    background: #fff;
    color: #2b2b2b;
    border: none;
    font-size: 22px;
    font-weight: 100;
}
.container {
  max-width: 1015px;
  margin: 0 auto;
  justify-content: center;
  align-items: center;
  display: flex;
  flex-direction: column;
}
html, body {
  font-family: 'Ubuntu', sans-serif;
  font-weight: 400;
  height: 100%;
  margin: 0;
  padding: 0;
  background-color: #ECECEC;
  box-sizing: border-box;
}
#app, .app-container {
  min-height: 100vh;
  background-color: #ECECEC;
  margin: 0;
  font-family: 'Ubuntu', sans-serif;
  padding: 0;
}

/* Estilos responsivos por ID */
#app {
  width: 100%;
  overflow-x: hidden;
}

#main-container {
  width: 100%;
  padding: 0 15px;
  box-sizing: border-box;
}

#topicos-container {
  width: 100%;
  max-width: 815px;
}

#topico-principal {
  width: 100%;
  box-sizing: border-box;
}

#topico-header {
  padding: 15px;
}

#author-info {
  flex-direction: column;
  align-items: flex-start;
  gap: 10px !important;
}

#author-avatar {
  width: 50px;
  height: 50px;
}

#topico-banner {
  height: auto;
}

#banner-title p {
  font-size: 22px;
  margin-top: 5px;
}

#topico-content {
  padding: 15px;
  font-size: 16px;
}

#benefits-grid {
  grid-template-columns: 1fr !important;
}

#highlight-content {
  flex-direction: column;
}

#highlight-image {
  max-width: 100% !important;
  margin-bottom: 15px;
}

#stats-grid {
  grid-template-columns: 1fr !important;
}

#ecosystem-list {
  columns: 1 !important;
}

/* Media Queries para ajustes específicos */
@media (min-width: 480px) {
  #author-info {
    flex-direction: row;
    align-items: center;
  }
  
  #banner-title p {
    font-size: 24px;
  }
  
  #stats-grid {
    grid-template-columns: repeat(3, 1fr) !important;
  }
}

@media (min-width: 600px) {
  #benefits-grid {
    grid-template-columns: repeat(2, 1fr) !important;
  }
  
  #highlight-content {
    flex-direction: row;
  }
  
  #ecosystem-list {
    columns: 2 !important;
  }
}

@media (min-width: 768px) {
  #author-avatar {
    width: 70px;
    height: 70px;
  }
  
  #banner-title p {
    font-size: 26px;
  }
  
  #topico-content {
    font-size: 17px;
    padding: 25px;
  }
}

@media (min-width: 992px) {
  #main-container {
    padding: 0;
  }
}
</style>

<script>
export default {
  data() {
    return {
    };
  },
  mounted() {  },
  methods: {

  },
  beforeUnmount() {
  },
};
</script>