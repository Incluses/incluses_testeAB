# <center>**Matemática Aplicada a Dados**<center>

# **Introdução ao Teste 🅰🅱️**

Realizamos um teste AB para avaliar o desempenho de duas interfaces distintas, A e B, em um aplicativo voltado ao público-alvo de menores aprendizes e efetuados, com faixa etária entre 15 e 35 anos. Para isso, distribuímos a experiência entre duas amostras, com 28 pessoas usando a interface A e 26 pessoas usando a interface B.

## **Objetivos**
O objetivo é entender qual interface promove uma experiência mais intuitiva e satisfatória para o público jovem e em início de carreira, explorando fluxos importantes de uso no aplicativo. Também queremos entender se a performace da interface B é melhor que a interface A por motivos de mudanças na interface ou motivos externos. O teste AB permitirá avaliar como essas mudanças impactam a performance, facilidade de uso e satisfação dos usuários em relação aos fluxos principais do aplicativo, fornecendo dados concretos para entender qual das interfaces oferece a melhor experiência para o público-alvo.

--- 

### **Hipóteses**

H0 = Bμ >= Aμ

H1 = Bμ < Aμ

--- 

## **Fluxos Avaliados**
Os fluxos críticos avaliados para verificar o impacto das mudanças entre as interfaces foram:

- Cadastro
- Login
- Inscrição em Vagas
- Logout
- Criação de Cursos

--- 

## **Mudanças entre as Interfaces**

#### 1. Fluxo de Cadastro e Login
**Interface A:** Botão de cadastro com borda posicionado embaixo e botão de login em cima.

**Interface B:** Botão de cadastro sem borda posicionado em cima e botão de login embaixo.

**Motivo da Mudança:** Esta modificação foi realizada para investigar se a posição e estilo dos botões influenciam a facilidade de uso ao logar ou se cadastrar. A escolha da Interface B é baseada em estudos de usabilidade de outros aplicativos, onde o botão de login costuma ter destaque, já que é mais utilizado.

#### 2. Fluxo de Inscrição em Vagas
**Interface A:** Informações da vaga apresentadas sem rótulos e botão de inscrição posicionado mais abaixo.

**Interface B:** Informações da vaga apresentadas com rótulos e botão de inscrição posicionado no centro.

**Motivo da Mudança:** Observamos que as informações da vaga não estavam suficientemente claras. Na Interface B, adicionamos rótulos às informações e alteramos a posição do botão de inscrição para avaliar se isso facilita o entendimento e melhora a performance do usuário.

#### 3. Fluxo de Logout
**Interface A:** Botão de logout acessível na barra de configurações do perfil do usuário.

**Interface B:** Botão de logout colocado diretamente no perfil do usuário.

**Motivo da Mudança:** Acreditamos que o botão de logout estava de difícil acesso. Alteramos a posição na Interface B para um local mais direto, visando melhorar a experiência de navegação ao facilitar o acesso ao logout.

#### 4. Fluxo de Criação de Curso
**Interface A:** Ícone de curso na barra de navegação representado por uma lâmpada. O botão de acesso aos cursos do usuário e criação é chamado de "Criar". As etapas de criação do curso parecem botões, mas não são interativas.

**Interface B:** Ícone de curso na barra de navegação representado por um livro. O botão de acesso aos cursos e criação é chamado de "Seus Cursos". As etapas de criação do curso não se assemelham a botões, melhorando a clareza.

**Motivo da Mudança:** Percebemos que o fluxo de criação de curso poderia ser mais intuitivo. A Interface B oferece uma navegação mais clara, com ícones e botões mais descritivos e o layout das etapas de criação menos confuso para evitar cliques incorretos.

# **Conclusão do Teste AB entre as Interfaces A e B**
Após a realização do teste AB entre as interfaces A e B, os resultados obtidos nos permitem fazer as seguintes considerações:

#### **Hipóteses**:
Testamos a hipótese nula (H0), que postula que a performance da interface A é igual ou superior à da interface B. A hipótese alternativa (H1) sugere que a performance da interface A é significativamente menor que a da interface B.

#### **Valores Críticos**:
Com um t-crítico conservador de -1.697 (graus de liberdade arredondados para baixo) e um t-crítico arriscado de -1.684 (graus de liberdade arredondados para cima), tanto os testes conservador quanto arriscado resultaram em uma aceitação da hipótese nula, já que o t-calculado de -1.510 está acima de ambos os valores críticos.
P-valor: O p-valor obtido foi de 0.0697, que está acima do nível de significância usual de 0.05. Isso indica que não há evidência estatística suficiente para rejeitar a hipótese nula.

#### **Grau de Liberdade**: 
Com um grau de liberdade calculado em aproximadamente 37.19, indicamos que as variâncias entre as amostras A e B são diferentes.

#### **Interpretação**:
Diante dos resultados, aceitamos a hipótese nula (H0). Isso significa que não encontramos evidências suficientes para afirmar que a performance da interface A é significativamente inferior à da interface B. Portanto, podemos concluir que, em termos de tempo de interação, a interface B não se destacou a ponto de comprovar que a interface A apresenta uma performance menor.

É importante ressaltar que a média menor de tempo na interface B pode ser atribuída a fatores externos e não necessariamente a melhorias nas mudanças feitas na interface. A ausência de diferença significativa entre as duas interfaces sugere que outras variáveis externas podem ter influenciado o desempenho dos usuários.

--- 
Feito por:

[Olívia Farias Domingues](https://github.com/oliviaworks)
