# Estatística Espacial - R


Data: 30.01.2022
---------------------------------------------------

Trabalho de conclusão da disciplina 'Estatística Espacial', em R, do MBA Executivo em Business Analytics e BigData, pela Fundação Getúlio Vargaa (FGV).


------------  
Dataset:  
> Base_Filadelfia:
Contém variáveis referentes a coordenadas (lng e lat) da localização da ocorrência de uma violação na Filadelfia. Além disso existe uma variável indicando um código (violation_code) para o tipo de violação cometido e uma variável com uma descrição (violation_description) para a mesma.   

  
> BaseMunicipioMensal:
Contém variáveis referentes aos municípios, código IBGE (fmun_cod) e nome (fmun). Além de informar o ano, mês e a região a qual o município se refere e os quantitativos de casos de lesão corporal dolosa e roubo de rua, ou seja, cada linha traz a informação do número de casos de lesão corporal dolosa e roubo de rua em um determinado mês de um determinado ano para um determinado município.  
   
> PopulacaoEvolucaoMensalMunic:
Contém variáveis referentes aos municípios, código IBGE (cod_munic) e nome (munic). Além da população estimada para o município no ano de 2019.

------------

Questões a serem respondidas:   

- Usando a base da Filadélfia faça o que se pede:

1) Escolha três das violações cometidas. Inicialmente a empresa gostaria de avaliar visualmente o comportamento das diferentes violações cometidas (violation_description). Discuta possíveis diferenças observadas nestes cenários.  
2) A seguir faça uma análise exploratória completa (investigar os efeitos de 1a e 2a ordem) das localizações das violações cometidas. Interprete todos os resultados apresentados. Discutam as possíveis diferenças observadas entre os efeitos estimados (1a e 2a ordem) dos 3 cenários avaliados, isto é, o comportamento da intensidade das violações parece ocorrer de forma similar para todos os seus tipos para a cidade da Filadélfia ou os padrões tendem a ser diferentes?  

- Usando os dados de crimes no Rio de Janeiro faça o que se pede:

1) Crie uma visualização apropriada para a taxa de lesão corporal dolosa por 100.000 habitantes em 2019 e para a taxa de roubo de rua por 100.000 habitantes no ano de 2019 considerando os municípios do Estado do Rio de Janeiro. Discuta a superfície de taxas estimadas.  
Verifique se existe dependência espacial para as duas taxas de interesse. Avalie diferentes critérios de vizinhança e diferentes pesos. Conclua usando um nível de significância de 5%.
  

Observação: Lembre-se de criar um relatório atrativo visualmente e conciso, com informações relevantes. Códigos de análise, podem ser apresentados em apêndices, mas nunca no corpo principal do relatório.
