#Programação Paralela e Distribuída

> _"Dar-me-eis um grão de trigo pela primeira casa do tabuleiro; dois pela segunda, quatro pela terceira, oito pela quarta, e, assim dobrando sucessivamente, até a sexagésima quarta e última casa do tabuleiro. Peço-vos, ó rei, de acordo com a vossa magnânima oferta, que autorizeis o pagamento em grãos de trigo, e assim como indiquei!"_ Malba Tahan, O Homem que Calculava.

---

<p>
  <img src="Capa.webp" width="300" height="400">
</p>

A pesquisa científica moderna, em diversas áreas de conhecimento, tem desenvolvido modelos computacionais sofisticados para solucionar problemas cada vez mais complexos. Esses modelos são transformados em aplicações paralelas que realizam simulações visando obter, no menor prazo possível, aproximações cada vez mais precisas da realidade.

Essas aplicações paralelas são construídas utilizando interfaces de programação e bibliotecas associadas a linguagens de programação convencionais, como **C** e **FORTRAN**, e fazendo uso de plataformas de computação paralela, como _clusters_, sistemas multiprocessadores de memória compartilhada e aceleradores com alto poder computacional para alcançar o desempenho desejado.

A formação de recursos humanos especializados nessa área demanda um longo tempo de investimento e deve ser iniciada o mais cedo possível, já nos primeiros anos dos cursos de graduação, seja nos cursos de Engenharia da Computação, Ciência da Computação ou Engenharia de Software.

O livbro "Programação Paralela e Distribuída", publicado pela editora Casa do Código, tem como objetivo apresentar conceitos iniciais de programação paralela para alunos de graduação. Aqui, são abordadas as interfaces de programação e bibliotecas MPI, para uso com o paradigma de troca de mensagens, além de OpenMP e OpenACC, para utilização com o paradigma de memória compartilhada e aceleradores.

No repositório [Programação Paralela e Distribuída](https://github.com/Programacao-Paralela-e-Distribuida) estão disponíveis os códigos fontes de todos os exemplos utilizados no livro, que esperamos sejam úteis para vocês. 

O Livro está organizado da seguinte maneira:

1. Introdução
   1.1. Exemplos de aplicações paralelas
   1.2. MPI
   1.3. OpenMP
   1.4. OpenACC
2. Conceitos básicos
   2.1 Processos e Threads
   2.2 Programação paralela
   2.3 Balanceamento de carga
   2.4 Avaliação de desempenho
   2.5 Arquiteturas paralelas
   2.6 Exercícios propostos
3. Comunicação ponto a ponto no MPI
   3.1 Introdução
   3.2 Comunicadores
   3.3 Exemplo de um programa em MPI
   3.4 Funções de gerenciamento do ambiente
   3.5 Envio e recepção de mensagens
   3.6 Identificando as mensagens recebidas
   3.7 Algumas recomendações
   3.8 Estudo de caso: método do trapézio
   3.9 Exercícios propostos
4. Comunicação coletiva no MPI
   4.1 Barreira
   4.2 Difusão
   4.3 Distribuição
   4.4 Coleta
   4.5 Redução
   4.6 Redução com difusão
   4.7 Coleta com difusão
   4.8 Transposição
   4.9 Algumas observações
   4.10 Estudo de caso: multiplicação de matriz por vetor
   4.11 Exercícios propostos
5. Comunicação MPI em detalhes
   5.1 Introdução
   5.2 Rotinas de envio e recepção bloqueantes
   5.3 Rotinas de envio e recepção não bloqueantes
   5.4 Esperando a mensagem
   5.5 Modos de comunicação
   5.6 Evitando o impasse ou deadlock
   5.7 Considerações de desempenho
   5.8 Estudo de caso: números primos
   5.9 Exercícios propostos
6. OpenMP
   6.1 Introdução
   6.2 Diretivas principais
   6.3 Funções OPENMP
   6.4 Cláusulas
   6.5 Sincronização
   6.6 Variáveis de ambiente
   6.7 Erros comuns e recomendações
   6.8 Estudos de caso
   6.9 Exercícios
7. OpenACC
   7.1 Modelo de programação OpenACC
   7.2 Diretivas principais
   7.3 Movimentação de dados
   7.4 Cláusulas das diretivas parallel
   7.5 Cláusulas da diretiva loop
   7.6 Diretivas avançadas
   7.7 Funções OpenACC
   7.8 Variáveis de ambiente
   7.9 Erros comuns e recomendações
   7.10 Estudos de caso
   7.11 Exercícios
8. Ambientes de execução
   8.1 Preparação do ambiente de execução MPI
   8.2 Preparação do Ambiente de Execução OpenMP
   8.3 Preparação do ambiente de execução OpenACC




