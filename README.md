# TFM: Estudo e aplicacións dos códigos qLDPC para a computación cuántica

Os códigos LDPC (Low Density Parity Check) son uns códigos correctores de erros clásicos
que se caracterizan por ter unha matriz de paridade pouco densa, polo que favorecen
a súa implementación en hardware e teñen unha alta eficiencia de descodificación.
Os seus análogos cuánticos, os códigos qLDPC, son códigos CSS que se constrúen
mediante dúas matrices de paridade clásicas ortogonais entre si. O grafo de Tanner destes
códigos é disperso, e se se garante que nel non hai ciclos curtos, os códigos qLPDC son
os mellores candidatos para alcanzar a cota de hashing, o análogo cuántico da cota de
Shannon, que indica o límite inferior da capacidade máxima da canle cuántica.
Por outro lado, os códigos EA-LDPC son códigos cuánticos asistidos por entrelazamento,
nos que se comparte previamente un par de cúbits enlazados, denominados ebits.
Grazas a isto, conséguense corrixir os estabilizadores que anticonmutan e, por tanto, relaxar
a condición de ortogonalidade dos códigos CSS.
Neste traballo, impleméntase unha familia de códigos qLPDC e compróbanse as súas
prestacións e o efecto dos ciclos curtos na redución do éxito da descodificación. Ademais,
constrúese unha nova familia de códigos EA-LDPC baseados nestes, que relaxan a condición
de ortogonalidade, permitindo aproveitar outras propiedades de códigos clásicos que
se achegan á cota de Shannon.
