# REDSHIFT-EDUCATION---GAME
REDSHIFT EDUCATION - GAME -  EDUCATIVO LABORATÓRIO DE FÍSICA , MATEMÁTICA E QUÍMICA   https://teoremampaz.pythonanywhere.com/static/espelho_mpaz.html  Desenvolvimento Software : Alan Aparecido da Silva Paz - Pesquisa teoria da fisica - computacional - matematica algebra linear - estudo geometria não-Euclidiana   MANUAL DO JOGO 



REDSHIFT EDUCATION - GAME -  EDUCATIVO LABORATÓRIO DE FÍSICA , MATEMÁTICA E QUÍMICA 

https://teoremampaz.pythonanywhere.com/static/espelho_mpaz.html

Desenvolvimento Software : Alan Aparecido da Silva Paz - Pesquisa teoria da fisica - computacional - matematica algebra linear - estudo geometria não-Euclidiana 

MANUAL DO JOGO 

<img width="1086" height="857" alt="image" src="https://github.com/user-attachments/assets/6b14e3d3-b8ad-4dce-95ae-d3ae59d40da2" />


TÉCNICA DE JOGADAS POSSÍVEIS REFERENTE ESTA ANÁLISE TEÓRICA DA FÍSICA 

<img width="785" height="790" alt="image" src="https://github.com/user-attachments/assets/ffbf95cf-328e-472c-b284-0833fe7785a0" />
<img width="783" height="773" alt="image" src="https://github.com/user-attachments/assets/18ca052d-7e67-464c-9560-d541a6ae0ef1" />
<img width="987" height="778" alt="image" src="https://github.com/user-attachments/assets/484fa113-359a-42a8-b8a4-3c41d0929341" />
<img width="983" height="845" alt="image" src="https://github.com/user-attachments/assets/3014a057-b16c-44dc-a937-660d291a24a5" />
<img width="988" height="782" alt="image" src="https://github.com/user-attachments/assets/58d11674-12ed-4edd-a063-82f922dcc903" />
<img width="990" height="462" alt="image" src="https://github.com/user-attachments/assets/47e7b0f5-985d-4c59-9069-a4c57355e41b" />


O Holospectrum 3D (Xadrez Espaço-Tempo & Redshift) é uma obra de engenharia conceitual que traduz conceitos de fronteira da ciência para uma interface interativa. A física e a matemática aplicadas no sistema conectam a Álgebra Linear, a Geometria Não-Euclidiana, a Relatividade Especial e a Acústica Matemática.Abaixo está o detalhamento rigoroso de como cada camada matemática e física opera no simulador:1. Geometria Espacial e Matrizes Helicoidais Assimétricas (Matemática)Diferente de um xadrez convencional baseado em um plano cartesiano bidimensional estático, o tabuleiro do Holospectrum é estruturado sobre matrizes helicoidais assimétricas.Mapeamento Cilíndrico-Espiral: As células e peças do tabuleiro são dispostas no espaço tridimensional seguindo equações paramétricas de uma hélice. Em coordenadas cartesianas, a posição de cada nó $n$ é calculada por:$$x(n) = R \cos(\theta_n)$$$$y(n) = R \operatorname{sen}(\theta_n)$$$$z(n) = k \cdot n$$Assimetria Diatônica: Os incrementos de ângulo ($\theta$) não são uniformes. Eles refletem os intervalos matemáticos irregulares dos sistemas diatônicos musicais (proporções de frequências tonais e semitonais), criando uma malha de espaço-tempo não-euclidiana onde as distâncias métricas entre as casas obedecem a uma lógica harmônica.2. A Física do Efeito Doppler Relativístico: Redshift e BlueshiftA mecânica central de interação (o espelho positivo e negativo) é regida diretamente pela astrofísica relativística através do Efeito Doppler para ondas.O Vetor Doppler ($\beta$): O jogo define um vetor de velocidade normalizada $\beta = \frac{v}{c}$, onde $v$ é a velocidade relativa da fonte de fótons/ondas e $c$ é a velocidade da luz.A Equação do Desvio Espectral ($z$): O fator de Redshift ou Blueshift ($z$) que altera o estado do cubo é computado pela equação da Relatividade Especial:$$z = \sqrt{\frac{1 + \beta}{1 - \beta}} - 1$$Comportamento Dinâmico:Espelho Positivo ($\beta < 0$ / Blueshift): A fonte se aproxima. Ocorre a compressão das cristas de onda, gerando um valor de $z$ negativo que eleva a frequência percebida.Espelho Negativo ($\beta > 0$ / Redshift): A fonte se afasta. Ocorre o alongamento do comprimento de onda, gerando um $z$ positivo que desvia o espectro para frequências mais baixas.3. Álgebra Linear e Transformações Gráficas (Computação Gráfica)Para renderizar e manipular o tabuleiro em tempo real via WebGL (Three.js), o motor aplica operações profundas de Álgebra Linear:Matrizes de Transformação Homogênea ($4 \times 4$): Cada clique para girar o espelho multiplica as coordenadas vetoriais dos vértices dos cubos por matrizes de rotação e reflexão.Espelhamento Algébrico: A inversão do espelho opera como uma matriz de reflexão espacial que inverte o sinal de uma das dimensões do vetor de estado, recalculando instantaneamente as normais das faces do objeto 3D e atualizando o "Banco de Fótons Quânticos" na interface.4. Acústica Matemática e Síntese de FrequênciasA física ondulatória se conecta à teoria musical por meio de progressões exponenciais precisas processadas pela Web Audio API.Escala de Frequências: Cada índice espectral $n$ associado a uma nota (como C3 ou Sibemol) é traduzido em Hertz ($Hz$) usando a fórmula de temperamento igual:$$f_n = f_0 \cdot 2^{\frac{n}{12}}$$Onde $f_0$ é a frequência de referência.Modulação Doppler Acústica: Quando o vetor Doppler altera o estado do espelho, a frequência real da nota sonora ($f_{obs}$) é redimensionada em tempo real pela fórmula de percepção de frequência sob movimento:$$f_{obs} = f_n \cdot \sqrt{\frac{1 - \beta}{1 + \beta}}$$Isso faz com que o som emitido ao clicar no cubo suba ou desça de tom matematicamente em perfeita harmonia com o fenômeno astrofísico simulado.Em suma, o jogo funciona como um computador de analogias físicas, onde equações de relatividade, geometria espiralada e acústica convergem para uma experiência interativa unificada.
















