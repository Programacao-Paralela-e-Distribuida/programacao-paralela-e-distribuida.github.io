# Programação Paralela e Distribuída

> _"Dar-me-eis um grão de trigo pela primeira casa do tabuleiro; dois pela segunda, quatro pela terceira, oito pela quarta, e, assim dobrando sucessivamente, até a sexagésima quarta e última casa do tabuleiro. Peço-vos, ó rei, de acordo com a vossa magnânima oferta, que autorizeis o pagamento em grãos de trigo, e assim como indiquei!"_ Malba Tahan, O Homem que Calculava.

---

<p>
  <img src="Capa.webp" width="300" height="400">
</p>

A pesquisa científica moderna, em diversas áreas de conhecimento, tem desenvolvido modelos computacionais sofisticados para solucionar problemas cada vez mais complexos. Esses modelos são transformados em aplicações paralelas que realizam simulações visando obter, no menor prazo possível, aproximações cada vez mais precisas da realidade.

Essas aplicações paralelas são construídas utilizando interfaces de programação e bibliotecas associadas a linguagens de programação convencionais, como **C** e **FORTRAN**, e fazendo uso de plataformas de computação paralela, como _clusters_, sistemas multiprocessadores de memória compartilhada e aceleradores com alto poder computacional para alcançar o desempenho desejado.

A formação de recursos humanos especializados nessa área demanda um longo tempo de investimento e deve ser iniciada o mais cedo possível, já nos primeiros anos dos cursos de graduação, seja nos cursos de Engenharia da Computação, Ciência da Computação ou Engenharia de Software.

O livbro "Programação Paralela e Distribuída", publicado pela editora Casa do Código, tem como objetivo apresentar conceitos iniciais de programação paralela para alunos de graduação. Aqui, são abordadas as interfaces de programação e bibliotecas MPI, para uso com o paradigma de troca de mensagens, além de OpenMP e OpenACC, para utilização com o paradigma de memória compartilhada e aceleradores.

O **MPI** é uma das interfaces de programação paralela mais utilizadas na computação científica, podendo ser empregada desde os equipamentos mais simples, com apenas algumas dezenas de processadores, até os clusters de alto desempenho, com dezenas de milhares de processadores. O **OpenMP** e o **OpenACC**, por suas vezes, são padrões para programação de sistemas multiprocessadores com memória compartilhada e aceleradores como GPUs e processadores manycores, caracterizados pela sua extrema facilidade de uso e relativo baixo custo.

Este livro está organizado da seguinte maneira: primeiramente são apresentados conceitos gerais de programação paralela, os diversos paradigmas de programação e formas de desenvolvimento de um programa paralelo, com considerações sobre balanceamento de carga e as métricas de avaliação de desempenho, comuns a qualquer tipo de programa paralelo.

No capítulo seguinte as funções básicas para o envio e recepção de mensagens do MPI são introduzidas. Logo após, as funções de comunicação coletiva, de grande importância para o trabalho cooperativo entre processos, são descritas. Em seguida, são apresentados detalhes sobre os diversos modos disponíveis no MPI para o envio e recepção de mensagens. No capítulo sobre o OpenMP, as diversas diretivas e suas respectivas cláusulas que são utilizadas para explorar o paralelismo embutido nos laços computacionais são apresentadas, junto das primitivas de sincronização disponíveis na linguagem, essenciais no paradigma de memória compartilhada.

No último capítulo, as diretivas e cláusulas do OpenACC são discutidos. O OpenACC é compatível com os modelos de programação OpenMP e MPI, ambas as abordagens podem ser combinadas com o OpenACC. O OpenACC é um modelo de programação aberta para computação paralela desenvolvido com o objetivo de simplificar a programação paralela, oferecendo alto desempenho e portabilidade entre diversos tipos de arquiteturas: multicore, manycore e GPUs.

O livro inclui também apêndices com detalhes dos ambientes de execução do **MPI**, **OpenMP** e **OpenACC**. São discutidas as diferenças entre os diversos pacotes e compiladores disponíveis, além das opções de compilação e outros detalhes para extrair o máximo desempenho das aplicações.

Ao longo deste livro são apresentados exemplos simples e objetivos para o uso de cada uma das funções, diretivas e cláusulas dos diversos paradigmas, bibliotecas e interfaces de programação abordados. Todos os exemplos foram cuidadosamente elaborados, compilados e testados em ambientes paralelos, de modo que possam ser baixados, compilados e reproduzidos facilmente em qualquer equipamento onde um mínimo de paralelismo esteja disponível. Estudos de caso e exercícios propostos podem ser encontrados ao final de cada capítulo, como forma de fixação e complemento dos conceitos elencados na parte teórica.


No repositório [Programação Paralela e Distribuída](https://github.com/Programacao-Paralela-e-Distribuida) estão disponíveis os códigos fontes de todos os exemplos utilizados no livro.

Esperamos que este livro possa ser um guia seguro para os passos iniciais das pessoas interessadas no uso da programação paralela de uma forma eficiente e produtiva.

O Livro está organizado da seguinte maneira:

1. Introdução
   - Exemplos de aplicações paralelas
   - MPI
   - OpenMP
   - OpenACC
2. Conceitos básicos
   - Processos e Threads
   - Programação paralela
   - Balanceamento de carga
   - Avaliação de desempenho
   - Arquiteturas paralelas
   - Exercícios propostos
3. Comunicação ponto a ponto no MPI
   - Introdução
   - Comunicadores
   - Exemplo de um programa em MPI
   - Funções de gerenciamento do ambiente
   - Envio e recepção de mensagens
   - Identificando as mensagens recebidas
   - Algumas recomendações
   - Estudo de caso: método do trapézio
   - Exercícios propostos
4. Comunicação coletiva no MPI
   - Barreira
   - Difusão
   - Distribuição
   - Coleta
   - Redução
   - Redução com difusão
   - Coleta com difusão
   - Transposição
   - Algumas observações
   - Estudo de caso: multiplicação de matriz por vetor
   - Exercícios propostos
5. Comunicação MPI em detalhes
   - Introdução
   - Rotinas de envio e recepção bloqueantes
   - Rotinas de envio e recepção não bloqueantes
   - Esperando a mensagem
   - Modos de comunicação
   - Evitando o impasse ou deadlock
   - Considerações de desempenho
   - Estudo de caso: números primos
   - Exercícios propostos
6. OpenMP
   - Introdução
   - Diretivas principais
   - Funções OPENMP
   - Cláusulas
   - Sincronização
   - Variáveis de ambiente
   - Erros comuns e recomendações
   - Estudos de caso
   - Exercícios
7. OpenACC
   - Modelo de programação OpenACC
   - Diretivas principais
   - Movimentação de dados
   - Cláusulas das diretivas parallel
   - Cláusulas da diretiva loop
   - Diretivas avançadas
   - Funções OpenACC
   - Variáveis de ambiente
   - Erros comuns e recomendações
   - Estudos de caso
   - Exercícios
8. Ambientes de execução
   - Preparação do ambiente de execução MPI
   - Preparação do Ambiente de Execução OpenMP
   - Preparação do ambiente de execução OpenACC




