
<!-- LINKS
Ensino:
  http://dalelane.co.uk/blog/?p=3513
  https://machinelearningforkids.co.uk/#!/about
  https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471
  https://medium.com/machine-learning-for-humans/neural-networks-deep-learning-cdad8aeae49b
  http://fortune.com/ai-artificial-intelligence-deep-machine-learning/

Aplicações FUN:
  Videogames https://www.leozqin.me/teaching-a-computer-to-play-video-games/

  https://www.forbes.com/sites/bernardmarr/2017/10/24/how-ai-and-machine-learning-are-used-to-transform-the-insurance-industry/#3534a12113a1

  https://www.forbes.com/sites/bernardmarr/2017/05/04/what-is-machine-learning-a-complete-beginners-guide-in-2017/#2bb481fc578f

  Carros http://readwrite.com/2016/12/20/ai-driving-future-autonomous-cars-tl4/

  Reinforcement Learning https://www.youtube.com/watch?v=hx_bgoTF7bs&feature=youtu.be

Praticas:
  Google Teachable Machine https://teachablemachine.withgoogle.com/
  Draw Completer https://magenta.tensorflow.org/assets/sketch_rnn_demo/index.html
  Draw Identifier https://www.autodraw.com/

FUTURO
  GAN https://github.com/junyanz/CycleGAN
-->

<!-- ESTRUTURA
 - Quem sou eu
    Alysson
    Ciencia da Computacao
    Mestrado Engenharia de Producao
    CSP Scrum
  Dono de Empresa de Desenvolvimento de Software (Facta mapa visitem)
 - O que é Machine Learning
    programacao tradicional
    aprendizagem por exemplos
 - Como funciona?
    Anti-SPAM Tradicional
      regras Nigeria
      regras Nigeria e Dinheiro
      regras Nigeria Dinheiro e Heranca
    Anti-SPAM ML
      emails spam
      emails não-spam
 - Algumas Aplicações
     Sugestoes (Netflix, Spotify)
     Predição (Manutenção Veículos, Seguros)
     Fraudes (Padroes no sistema financeiro, gastos publicos)
     Medicina (Cancer)
     Busca
     Processamento de linguagem (Moto-X, Alexa)
     Processamento de Imagens (Reconhecimento de Faces, Segurança)
     Carros Autonomos (Waymo, Uber, Tesla, Acidentes)
 - !Ao Vivo!
    Google Translate
    Gatos
    Beattles
    Sentimentos
 - O que vem por aí
    Veiculos Autonomos
    Criatividade (GAN, CycleGAN)
    Reinforcement Learning ()
 - Obrigado
 - Bonus
    Dilemas Morais
================
 - Dificuldades
    Quantidade de dados
      Google (fotos)
    Recursos Computacionais
      ingles frances = 2 semanas
      google x academia (500 gpus por 1 mes)
-->
# Machine Learning 101
por Alysson Mendonça



## 0. Motivação
  <video autoplay controls>
    <source data-src="media/0_car_tesla.mp4" type="video/mp4" />
  </video>



## 1. Quem sou eu?


  ### Eu gosto de...
  ![teste](media/1_tecnologia.jpg)


  ### Eu gosto de...
  ![teste](media/1_viajar_1.jpg)


  ### Eu gosto de...
  ![teste](media/1_viajar_2.jpg)



  ## O que eu gosto
  [1_gatos.jpg] <!-- .element: class="fragment" data-fragment-index="1" -->
  [1_piano.jpg] <!-- .element: class="fragment" data-fragment-index="2" -->
  [1_gatos_tocando_piano.jpg] <!-- .element: class="fragment" data-fragment-index="3" -->


  ## Formação Acadêmica
  Ciência da Computação <!-- .element: class="fragment" data-fragment-index="1" -->
  Engenharia de Produção <!-- .element: class="fragment" data-fragment-index="2" -->


  ## Formação Profissional
  Accenture <!-- .element: class="fragment" data-fragment-index="1" -->
  Scrum <!-- .element: class="fragment" data-fragment-index="2" -->
  [1_scrum_facta]

  Note: Accenture tem +300mil funcionários, faturamento anual de mais de 100 bilhões


  ## Facta
  Visitem ;)
  [1_mapa_facta.png]



# 2. O que é Machine Learning?


  ## De onde saiu?
  [2_de_onde_saiu_1.mp4]
  [2_de_onde_saiu_2.png]


  ## Programação Tradicional
  [2_receita.jpg] <!-- .element: class="fragment" data-fragment-index="1" -->
  [2_tradicional.png] <!-- .element: class="fragment" data-fragment-index="2" -->


  ## Machine Learning
  Aprendizagem por Exemplos <!-- .element: class="fragment" data-fragment-index="1" -->
  [2_aprendizagem_exemplo] <!-- .element: class="fragment" data-fragment-index="2" -->



# 3. Como Funciona?


  ## Exemplo Prático
  Quem gosta de SPAM?


    ## Exemplo Prático - Nigerian SCAM
    [3_spam_1.gif]


    ### Exemplo Prático - Nigerian SCAM
    [3_spam_2a.jpg]
    [3_spam_2b.jpg]


    ### Exemplo Prático - Nigerian SCAM
    [3_spam_3.jpg]


  ## Anti-SPAM Tradicional


    ### Tentativa 1 - País
      * Bloqueia emails da Nigéria
      * Bloqueia emails da Nigéria! <!-- .element: class="fragment" data-fragment-index="1" -->


    ### Tentativa 2 - Conteúdo
      * Bloqueia emails com Nigéria e Dinheiro
      * Bloqueia email de bancos <!-- .element: class="fragment" data-fragment-index="1" -->
      * Cancela email de cobranças <!-- .element: class="fragment" data-fragment-index="1" -->


    ### Tentativa 3 - Assunto
      * Bloqueia emails com Nigéria, Dinheiro e Herança
      * Funciona! <!-- .element: class="fragment" data-fragment-index="1" -->
      * Até que... <!-- .element: class="fragment" data-fragment-index="1" -->


    ### Tentativa 4 - E agora?
    [3_spam_4.jpg]


  ## Anti-SPAM Machine Learning
  Aprendendo com exemplos


    ### 1 - Pegue MUITOS Exemplos
    [3_ml_1.png]


    ### 2 - Categorize cada Exemplo
    [3_ml_2.png]


    ### 3 - Separe as Categorias
    [3_ml_3.png]


    ### 4 - Treine um modelo de ML
    [3_ml_4.png]



# 4. Aplicações de ML


  ## Reconhecimento de Sons
    [4_reconhecimento_sons.png]


  ## Reconhecimento de Imagens
    [4_reconhecimento_imagens.png]


  ## Processamento de Linguagem Natural
    [4_processamento_linguagem.png]


  ## Medicina
    * Diagnóstico
    * Prescrição
    * Prognóstico


  ## Medicina - Exemplo
    * Retinopatia Diabética
    [4_medicina_1.png]


  ## Medicina - Outro Exemplo
    * Câncer de Mama
    [4_medicina_2.gif]


  ## Recomendações
    * Netflix, Spotify, Amazon...
    [4_recomendacao_netflix.jpg]


  ## Predição
    * Manutenção de Veículos e Máquinas
    [4_predictive_maintenance.jpg]


  ## Identificação de Fraudes
    * Compras em Cartão de Crédito, Gastos Públicos
    [4_fraudes.png]


  ## Logística
    [4_logistica_truck.mp4]


  ## Maquinaria Pesada
    [4_maquinaria_pesada.mp4]



# 5. ML ao Vivo!


  ## Sketcher
  https://magenta.tensorflow.org/assets/sketch_rnn_demo/index.html


  ## Teachable Machine
  https://teachablemachine.withgoogle.com/


# 6. O que vem por aí


  ## "Criatividade" (GAN)
  [6_van_gogh__starry_night__stanford.png]


  ## Reinforcement Learning
  [6_rl_humanoid.mp4]
  [6_rl_injured_robots.mp4]
  [6_openai_dota.mp4]


# 7. Bonus - Dilemas Morais
    [7_car_waymo.mp4]
    [7_car_dillema.mp4]



# Obrigado!
  * Alysson Mendonça
  * @alymenbr
  * alymenbr@gmail.com
  [8_obrigado.jpg]




