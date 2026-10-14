# Etapa 5 Matriz de síntese e organização da revisão

## Solicitação

Compare os artigos e organize a revisão por temas ou eixos. Não produza apenas uma sequência de resumos.

## Eixos da revisão

1. `Consumo de energia e refrigeração: causas e estratégias de eficiência energética`
2. `Práticas de TI Verde e tecnologias sustentáveis aplicadas aos Data Centers`
3. `Limites da eficiência e desafios de implementação: crescimento da IA, consumo de água e regulação`

## Matriz de síntese

|Eixo|Artigos relacionados|Convergências|Divergências|Limitações|Lacunas|
|-|-|-|-|-|-|
|`1. Consumo de energia e refrigeração`|`Lima e Barbosa (2025); Santos e Borges (2026); Prieto et al. (2025)`|`Os três artigos apontam que o funcionamento contínuo dos equipamentos gera calor e exige refrigeração, o que mantém a demanda por energia elevada. Também concordam que melhorar a refrigeração (resfriamento natural, controle de temperatura, contenção de ar, sistemas mais eficientes) é um caminho central para reduzir o consumo.`|`Lima e Barbosa tratam a eficiência como forma de diminuir o consumo. Santos e Borges projetam crescimento do consumo energético e Prieto et al. mostram que, mesmo com PUE de 1,09, o consumo absoluto continua aumentando. Os enfoques também diferem: Lima e Barbosa focam em estratégias técnicas de climatização; Santos e Borges ampliam para o contexto dos Estados Unidos e dos Data Centers de hiperescala.`|`Lima e Barbosa dependem dos estudos e critérios de seleção da revisão sistemática; Santos e Borges usam dados secundários e projeções (Cadeias de Markov); Prieto et al. se limitam aos Google Data Centers e a dados da própria empresa. Nenhum apresenta seção específica de limitações, exceto Prieto et al.`|`Falta comparar a eficácia das estratégias de refrigeração em Data Centers de diferentes portes e climas, especialmente em contexto brasileiro. Os estudos não relacionam a refrigeração aos ruídos gerados pelos equipamentos.`|
|`2. Práticas de TI Verde e tecnologias sustentáveis`|`Santos e Borges (2026); Prieto et al. (2025); Nusdeo et al. (2025); Lima e Barbosa (2025)`|`Há convergência em práticas como energia renovável (incluindo a fotovoltaica citada por Lima e Barbosa), refrigeração mais eficiente, recuperação ou reaproveitamento do calor, virtualização e eficiência energética. Santos e Borges e Nusdeo et al. também citam a redução do lixo eletrônico e equipamentos mais duráveis e recicláveis.`|`Santos e Borges apresentam soluções mais inovadoras, como Data Centers em regiões frias e estruturas subaquáticas. Nusdeo et al. tratam a computação verde também como política pública, e não só como solução tecnológica. Prieto et al. avaliam as práticas por indicadores (PUE, WUE, CUE), enquanto os demais as descrevem de forma mais geral.`|`Boa parte das práticas é apresentada de forma descritiva ou teórica. Prieto et al. demonstram resultados concretos, mas apenas em uma empresa. Nusdeo et al. não realizam medições próprias de energia, água ou ruídos.`|`Poucas evidências comparando custos e viabilidade das práticas em Data Centers de menor estrutura. Alternativas como Data Centers subaquáticos e em regiões frias aparecem sem análise de viabilidade ambiental e operacional.`|
|`3. Limites da eficiência e desafios de implementação`|`Prieto et al. (2025); Nusdeo et al. (2025); Santos e Borges (2026)`|`Os três reconhecem que o crescimento dos Data Centers, impulsionado pela nuvem e pela Inteligência Artificial, aumenta a demanda por energia (e, em dois deles, por água) e que tecnologias sustentáveis precisam ser ampliadas.`|`Prieto et al. mostram o limite técnico: a eficiência avança, mas o consumo total cresce. Nusdeo et al. mostram o limite regulatório: lacunas no licenciamento ambiental e na proteção de recursos naturais no Brasil. Santos e Borges enfatizam a adoção acelerada de tecnologias verdes, com menor ênfase em regulação.`|`Prieto et al. têm foco em um único caso; Nusdeo et al. têm abordagem jurídica, qualitativa e documental; Santos e Borges têm foco principal nos Estados Unidos.`|`Os artigos discutem pouco as dificuldades operacionais de aplicar TI Verde (como manter o funcionamento 24 horas por dia). O consumo de água é tratado de forma limitada, sobretudo por Prieto et al. e Nusdeo et al. Nenhum dos quatro aprofunda os ruídos, que fazem parte do nosso recorte.`|

## Roteiro da revisão da literatura

### Eixo 1

* Ideia principal: `Os Data Centers funcionam continuamente, geram calor e dependem de refrigeração, o que mantém o consumo de energia elevado. Estratégias de climatização e controle térmico são apontadas como principal caminho para reduzir esse consumo.`
* Evidências que serão usadas: `Lima e Barbosa (2025): revisão sistemática com 156 trabalhos encontrados e 28 analisados, destacando resfriamento natural, controle inteligente de temperatura e umidade, contenção de ar e simulações computacionais. Santos e Borges (2026): crescimento do consumo energético e uso de refrigeração mais eficiente. Prieto et al. (2025): PUE de 1,09 e WUE de 1,7 L/kWh nos Google Data Centers.`
* Comparação entre estudos: `Lima e Barbosa mostram que o controle adequado da temperatura pode diminuir o consumo. Prieto et al. confirmam, com indicadores, que sistemas eficientes são possíveis, mas mostram que isso não impede o aumento do consumo total. Santos e Borges acrescentam a perspectiva de projeção do consumo futuro.`
* Ligação com o problema: `Responde à parte da pergunta sobre como o alto consumo de energia e a refrigeração contínua afetam o meio ambiente e atende ao objetivo específico 1 (fatores do consumo elevado). A refrigeração como possível fonte de ruído (objetivo específico 2) não é tratada pelos artigos.`

### Eixo 2

* Ideia principal: `O TI Verde reúne práticas tecnológicas e de gestão que reduzem os impactos dos Data Centers: energia renovável, refrigeração eficiente, reaproveitamento de calor, virtualização e redução do lixo eletrônico.`
* Evidências que serão usadas: `Santos e Borges (2026): energia renovável, reaproveitamento de calor, virtualização, Data Centers em regiões frias e estruturas subaquáticas. Prieto et al. (2025): energia renovável, resfriamento eficiente e recuperação de calor, avaliados por PUE, WUE e CUE. Nusdeo et al. (2025): computação verde com eficiência energética, virtualização, equipamentos duráveis e recicláveis e políticas públicas. Lima e Barbosa (2025): uso de energia fotovoltaica e modernização das instalações.`
* Comparação entre estudos: `As práticas se repetem entre os artigos, mas com abordagens diferentes: tecnológica e inovadora (Santos e Borges), baseada em indicadores e estudo de caso (Prieto et al.), voltada a políticas públicas (Nusdeo et al.) e baseada em revisão de estratégias de eficiência (Lima e Barbosa).`
* Ligação com o problema: `Atende ao objetivo específico 3 (tecnologias e alternativas sustentáveis) e à parte do problema sobre como o TI Verde pode reduzir os impactos ambientais.`

### Eixo 3

* Ideia principal: `Mesmo com ganhos de eficiência, o crescimento dos Data Centers, principalmente os voltados à Inteligência Artificial, faz o consumo total de energia e água continuar aumentando. Além disso, a adoção de práticas sustentáveis esbarra em lacunas regulatórias.`
* Evidências que serão usadas: `Prieto et al. (2025): o consumo absoluto de energia e água cresce com as cargas de trabalho de IA generativa, apesar do PUE de 1,09. Nusdeo et al. (2025): lacunas no licenciamento ambiental no Brasil e aumento da demanda por energia e água. Santos e Borges (2026): necessidade de acelerar a adoção de tecnologias verdes diante do crescimento da demanda por energia (citação da página 1 do fichamento).`
* Comparação entre estudos: `Prieto et al. e Nusdeo et al. concordam que a expansão da IA pressiona recursos, mas apontam desafios distintos (limite da eficiência versus ausência de regras adequadas). Santos e Borges reforçam a urgência de ampliar práticas verdes.`
* Ligação com o problema: `Responde à parte da pergunta sobre as dificuldades para aplicar práticas de TI Verde e atende ao objetivo específico 4 (desafios de implementação), incluindo aspectos ambientais e regulatórios.`

## Síntese crítica provisória

`Os quatro artigos convergem ao mostrar que o funcionamento contínuo dos Data Centers gera calor, exige refrigeração e mantém o consumo de energia elevado, e que práticas de TI Verde, como refrigeração eficiente, energia renovável, reaproveitamento de calor e virtualização, são as principais respostas a esse problema. A principal divergência está no alcance dessas práticas: enquanto Lima e Barbosa (2025) tratam a eficiência como caminho para reduzir o consumo, Prieto et al. (2025) mostram que ganhos de eficiência convivem com o aumento do consumo total de energia e água, e Nusdeo et al. (2025) apontam que a expansão ocorre com lacunas regulatórias no Brasil. Os métodos também variam (revisão sistemática, projeções com dados secundários, análise documental e estudo de caso) e há limitações como dependência de dados da própria empresa, foco em um único caso e ausência de medições próprias. A lacuna mais clara é que nenhum dos artigos aprofunda os ruídos gerados pelos Data Centers, tema do nosso recorte e do objetivo específico 2, além de haver pouca discussão sobre o consumo de água e sobre as dificuldades operacionais de implantar TI Verde em Data Centers de grande porte. Isso indica a necessidade de buscar fontes complementares sobre ruídos e de destacar essa lacuna no artigo.`

## Checklist

* \[X] Os artigos foram agrupados por ideias.
* \[X] Há comparações entre estudos.
* \[X] As divergências foram registradas.
* \[X] As lacunas são específicas e sustentadas pelas leituras.
