# Otimização combinatória (2025/1)

*If one would take statistics about which mathematical problem is using up most of the computer time in the world, then ... the answer would probably be linear programming. (László Lovász)*

* Bem-vindo à otimização combinatória.

## Informações gerais

**Carga horária:** 60 h (em 30 aulas de 2h)\
**Créditos:** 4\
**Súmula:** Modelagem matemática, programação linear e não-linear. Programação inteira e solução via métodos exatos. Algoritmos de aproximação e heurísticas.\
**Turma:** A.\
**Horário/Sala:** Seg/Qua 10.30, 106 (43413).\
**Consultas:** a combinar.

## Resultados

* [Trabalhos](2025-1-Trabalhos)

## Notícias

* As aulas começam no dia 10 de março.
* Otimização: [O que você consegue fazer eu faço melhor](https://youtu.be/Dc38La-Xvog|tudo) 😃

## Materiais

* [Notas de aula (Abril de 2024)](assets/notas-e76bc7.pdf).
* Página da disciplina em [2024/2](2024-2), [2024/1](2024-1), [2023/2](2023-2), [2023/1](2023-1), [2022/2](2022-2), [2022/1](2022-1), [2021/2](2021-2), [2021/1](2021-1), [2020/2](2020-2), [2020/1](2020-1), [2019/2](2019-2), [2019/1](2019-1), [2018/2](2018-2), [2018/1](2018-1), [2017/2](2017-2), [2017/1](2017-1), [2016/2](2016-2), [2016/1](2016-1), [2015/2](2015-2), [2015/1](2015-1), [2014/2](2014-2), [2014/1](2014-1), [2013-2](2013-2), [2013-1](2013-1), [2012-2](2012-2), [2012-1](2012-1), [2011-2](2011-2), [2011-1](2011-1), [2010-2](2010-2), [2010-1](2010-1), [2009-2](2009-2), [2009-1](2009-1), [2008-2](2008-2), [2008-1](2008-1) e [2007/2](2007-2).
* [Anki](https://apps.ankiweb.net) flashcards para [unidade 1](<http://www.inf.ufrgs.br/~mrpritt/oc/Otimização combinatória_U1.apkg>), [unidade 2](<http://www.inf.ufrgs.br/~mrpritt/oc/Otimização combinatória_U2.apkg>) e [unidade 3](<http://www.inf.ufrgs.br/~mrpritt/oc/Otimização combinatória_U3.apkg>).

### Aulas

| No. | Data  | Tópicos                                       | Notas cáp. | Exercícios                     | Soluções                                                                                             | Leitura                                                                                                                             |
|-----|-------|-----------------------------------------------|------------|--------------------------------|------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
|     |       | **Heurísticas**                               |            |                                |                                                                                                      |                                                                                                                                       |
| 1   | 10/03 | Administrativa, Introdução, Busca local.      | 10.1,10.2  | [Q1](assets/qh0120251.pdf)            | [SQ1](assets/sqh0120251.pdf), [D1](https://nbviewer.org/url/github.com/mrpritt/otimizacao-combinatoria/blob/main/demos/D01-tsp-h1.ipynb) |                                                                                                                                       |
| 2   | 12/03 | GRASP, Simulated annealing, Busca local iterada, VNS. | 10.3-10.6 | [Q2](assets/qh0220251.pdf)            | [SQ2](assets/sqh0220251.pdf), [D2](https://nbviewer.org/url/github.com/mrpritt/otimizacao-combinatoria/blob/main/demos/D02-tsp-h2.ipynb) |                                                                                                                                       |
| 3   | 17/03 | Busca Tabu, Algoritmos genéticos, meméticos.  | 11         | [Q3](assets/qh0320251.pdf)            | [SQ3](assets/sqh0320251.pdf), [D3](https://nbviewer.org/url/github.com/mrpritt/otimizacao-combinatoria/blob/main/demos/D03-tsp-h3.ipynb) |                                                                                                                                       |
|     |       | **Programação linear**                        |            |                                |                                                                                                      |                                                                                                                                       |
| 4   | 19/03 | Introdução: Exemplos e solução gráfica.       | 1.1,1.3    | [Q4](assets/q0120251.pdf)             | [Q4](assets/sq0120251.pdf)                                                                                  | [V1](http://dx.doi.org/10.1007/978-1-4614-7630-6_1),MF1,2                                                                              |
| 5   | 24/03 | Formulação e exemplos.                        | 1.1        | [E1](assets/e0120251.pdf), [Q5](assets/q0220251.pdf) | [S1](assets/se0120251.pdf), [Q5](assets/sq0220251.pdf)                                                             | [V1](http://dx.doi.org/10.1007/978-1-4614-7630-6_1),MF2                                                                                |
| 6   | 26/03 | Forma matricial e normal, introdução método simplex. | 1.2,2.1,2.2 | [Q6](assets/q0320251.pdf)             | [Q6](assets/sq0320251.pdf)                                                                                  | [V2](http://dx.doi.org/10.1007/978-1-4614-7630-6_2), [V6](http://dx.doi.org/10.1007/978-1-4614-7630-6_6),MF2,3                      |
| 7   | 31/03 | Laboratório de formulação (sala 104/43425).   | 1.1,B.2    | [L1](assets/l0220251.pdf)             | [L1](assets/sl0220251.pdf)                                                                                  |                                                                                                                                       |
| 8   | 02/04 | Método simplex. Sistemas ilimitados.          | 2.3,2.4    | [Q7](assets/q0420251.pdf)             | [Q7](assets/sq0420251.pdf)                                                                                  | [V2](http://dx.doi.org/10.1007/978-1-4614-7630-6_2),MF3.{1,2}                                                                           |
| 9   | 07/04 | Método simplex. Pivô tool, fase I. Soluções degeneradas. | 2.5 | [E2](assets/e0420251.pdf), [Q8](assets/q0520251.pdf) | [S2](assets/se0420251.pdf), [Q8](assets/sq0520251.pdf)                                                             | [V2](http://dx.doi.org/10.1007/978-1-4614-7630-6_2),MF3.3                                                                               |
| 10  | 09/04 | Revisão e exercícios.                         |            | [E3](assets/e0320251.pdf)             | [S3](assets/se0320251.pdf)                                                                                  | [V3](http://dx.doi.org/10.1007/978-1-4614-7630-6_3),MF3.6                                                                               |
| 11  | 14/04 | **Prova 1**                                   |            | [P1](assets/p0120251.pdf)             | [SP1](assets/sp0120251.pdf)                                                                                 |                                                                                                                                       |
| 12  | 16/04 | Dualidade: Introdução, teoremas de dualidade. | 3.1-3.3    | [Q9](assets/q0620251.pdf)             | [Q9](assets/sq0620251.pdf)                                                                                  | [V5](http://dx.doi.org/10.1007/978-1-4614-7630-6_5),MF4                                                                                |
|     | 21/04 | //Tiradentes//                                |            |                                |                                                                                                      |                                                                                                                                       |
| 13  | 23/04 | Dualidade: Folgas complementares. Método simplex dual. | 3.2 3.4 | [Q10](assets/q0720251.pdf)            | [Q10](assets/sq0720251.pdf)                                                                                 |                                                                                                                                       |
| 14  | 28/04 | Método simplex dual. Analise de sensibilidade. | 3.5,3.6   | [Q11](assets/q0820251.pdf)            | [Q11](assets/sq0820251.pdf)                                                                                 | [V6](http://dx.doi.org/10.1007/978-1-4614-7630-6_6),V7.1                                                                               |
| 15  | 30/04 | Analise de sensibilidade.                     | 3.7        | [E4](assets/e0420251.pdf), [Q12](assets/q0920251.pdf) | [Q12](assets/sq0920251.pdf)                                                                                 | [V6](http://dx.doi.org/10.1007/978-1-4614-7630-6_6),V7.1                                                                               |
|     |       | **Programação inteira**                       |            |                                |                                                                                                      |                                                                                                                                       |
| 16  | 05/05 | Introdução e aplicações.                      | 5, 6.1     | [Q13](assets/q1020251.pdf)            |                                                                                                      | [V23](http://dx.doi.org/10.1007/978-1-4614-7630-6_23), [W1.{1-4}](https://onlinelibrary.wiley.com/doi/10.1002/9781119606475.ch1),PS13.1 |
| 17  | 07/05 | Formulação e exemplos.                        | 6.1-6.3    | [Q14](assets/q1120251.pdf)            |                                                                                                      | [W1.{5-7}](https://onlinelibrary.wiley.com/doi/10.1002/9781119606475.ch1),PS13.1                                                        |
| 18  | 12/05 | Formulação e demonstrações.                   | B.2        | [E5](assets/e0520251.pdf)             | [S5](assets/se0520251.pdf)                                                                                  |                                                                                                                                       |
| 19  | 14/05 | Revisão e exercícios.                         |            | [E6](assets/e0620251.pdf)             | [S6](assets/se0620251.pdf)                                                                                  |                                                                                                                                       |
|     | 19/05 | Workshop Prova 2    .                         |            |                                |                                                                                                      |                                                                                                                                       |
| 20  | 21/05 | Matrizes totalmente unimodulares.             | 7.1        |                                |                                                                                                      | [W3.{1,2}](https://onlinelibrary.wiley.com/doi/10.1002/9781119606475.ch1),K5.4,PS13.2                                                |
| 21  | 26/05 | **Prova 2**                                   |            | [E7](assets/e0720251.pdf)             |                                                                                                      |                                                                                                                                       |
| 22  | 28/05 | Problemas com solução simples, desigualdades válidas. | 7.2-3 |                                |                                                                                                      | [W3.{3,4}](https://onlinelibrary.wiley.com/doi/10.1002/9781119606475.ch1),PS13.2,W8.{1-4}                                            |
| 23  | 02/06 | Algoritmos de planos de corte.                | 7.4        |                                |                                                                                                      | [W8.{5,6}](https://onlinelibrary.wiley.com/doi/10.1002/9781119606475.ch8),PS14.1                                                     |
| 24  | 04/06 | Algoritmos de Branch and bound 1.             | 7.5        |                                |                                                                                                      | [W7](https://onlinelibrary.wiley.com/doi/10.1002/9781119606475.ch7),G5.2.3                                                               |
| 25  | 09/06 | Algoritmos de Branch and bound 2.             | 7.5        |                                |                                                                                                      | [W7](https://onlinelibrary.wiley.com/doi/10.1002/9781119606475.ch7),G5.2.3                                                               |
| 26  | 11/06 | Revisão e exercícios.                         |            |                                |                                                                                                      |                                                                                                                                       |
| 27  | 16/06 | **Prova 3**                                   |            |                                |                                                                                                      |                                                                                                                                       |
| 28  | 23/06 | [Algoritmos de aproximação.](:inf05010:apr)   |            |                                |                                                                                                      |                                                                                                                                       |
| 29  | 25/06 | Apresentação de trabalhos.                    |            |                                |                                                                                                      |                                                                                                                                       |
| 30  | 30/06 | Apresentação de trabalhos.                    |            |                                |                                                                                                      |                                                                                                                                       |
|     |       | Provas de recuperação.                        |            |                                |                                                                                                      |                                                                                                                                       |
|     | 19/07 | Término oficial das aulas.                    |            |                                |                                                                                                      |                                                                                                                                       |

V: Vanderbei, W: Wolsey, PS: Papadimitriou/Steiglitz MF: Maculan/Fampa

### Material

* [Template em LaTeX](assets/r.tex) para a lista de exercícios e [uma versão compilada](assets/r.pdf).
* Uma [referéncia rápida](assets/GLPK-quickref.pdf) de GLPK e MathProg

### Ferramentas

* Visualização de LPs [GILP](https://gilp.henryrobbins.com/en/latest/examples/index.html)
* Vanderbei's [simple pivot tool](http://www.princeton.edu/~rvdb/JAVA/pivot/simple.html) and [advanced pivot tool](https://vanderbei.princeton.edu/JAVA/pivot/advanced.html).
* [GNU Linear programming kit](http://www.gnu.org/software/glpk)

### Bibliografia

* Nelson Maculan and Marcia H. Costa Fampa. Otimização linear. Editora UnB, 2006. INF 65.012.122 M175o.
* Marco Cesar Goldbarg. Otimização combinatória e programação linear : modelos e algoritmos. Campus, 2005. INF 65.012.122 G618o2.
* David G. Luenberger. Linear and nonlinear programming. Springer, 2nd edition, 2003.
* Bernhard H. Korte and Jens Vygen. Combinatorial optimization theory and algorithms. Springer, 4th edition, 2008. INF 65.012.122 K85c.
* Mokhtar S. Bazaraa, John J. Jarvis, and Hanif D. Sherali. Linear programming and network flows. Wiley, 3rd edition, 2004. ENG 519.852 B362l.
* Laurence A. Wolsey and George L. Nemhauser. Integer and Combinatorial Optimization. Wiley, 1999.
* Dimitri P. Bertsekas. Nonlinear programming. Athena, 2nd edition, 1999. INF 65.012.122 B551n.
* Laurence A. Wolsey. Integer Programming. Wiley, 1998.
* Christos H. Papadimitriou and Kenneth Steiglitz. Combinatorial optimization: Algorithms and complexity. Prentice-Hall, dover edition, 1982.
* G. Ausiello, P. Crescenzi, G. Gambosi, V. Kann, A. Marchetti-Spaccamela, and M. Protasi. Complexity and approximation – Combinatorial Optimization Problems and their Approximability Properties. Springer-Verlag, 1999. INF 510.5 C737.
* Robert J. Vanderbei. Linear programming: Foundations and Extensions. Kluwer, 2nd edition, 2001.
* Juraj Hromkovic. Algorithmics for hard problems. Springer, 2001. INF 65.012.122 H873a.
