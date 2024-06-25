> Trabalho de Inteligência Artificial sobre a representação de **conhecimento** e **raciocinio**.

### Representação de Conhecimento e Raciocínio
A representação de conhecimento e raciocínio é um campo crucial da inteligência artificial dedicado a representar informações sobre o mundo de forma que sistemas computacionais possam utilizá-las para resolver tarefas complexas. Este campo incorpora descobertas da psicologia sobre como os humanos resolvem problemas e representam o conhecimento. Além disso, utiliza princípios da lógica para automatizar diversos tipos de raciocínio.
  
Para que uma máquina utilize um corpo de conhecimento, é fundamental escolher a maneira adequada de representá-lo. Segundo Waterman (1986), em IA, "conhecimento" refere-se à informação necessária para que um programa se comporte de maneira inteligente. 
  
Diferentes sistemas de representação podem ser mais adequados para problemas específicos, e há um esforço contínuo para desenvolver sistemas e linguagens de representação de propósito geral. Embora inicialmente a ênfase fosse em como representar o conhecimento formalmente sem considerar sua utilização, a maioria das pesquisas atuais reconhece que é essencial considerar o raciocínio em conjunto com a representação. 

### Frames
Frames, introduzidos por Marvin Minsky em 1974, são uma técnica desenvolvida para modelar conceitos complexos e suas relações de uma maneira estruturada e acessível. Caracterizam-se por identificar objetos complexos através de um nome e um conjunto de atributos. 
  
Um frame é composto por uma coleção de atributos (chamados de slots) e valores (chamados de fillers). Cada frame representa uma entidade ou situação, e os slots descrevem as propriedades ou características dessa entidade.
  
Por exemplo, considere um frame para representar o conceito de "Cachorro":

- Frame: **Cachorro**
	- Slots:
		- Nome: Bob
		- Raça: Vira-lata
		- Cor: Caramelo
		- Dono: Luiza
  
> Cada slot contém um valor específico, e juntos eles descrevem um cachorro específico.
> 
> Esses slots podem também conter outros frames, criando uma hierarquia ou rede de informações interligadas.
  
### Vantagens e Desvantagens
Os frames possuem várias vantagens e desvantagens. Entre as vantagens, destacam-se a estruturação, que oferece uma forma natural e intuitiva de organizar conhecimento, refletindo a maneira como os humanos categorizam e associam informações; a flexibilidade, que permite a inclusão de diferentes tipos de dados e regras na mesma estrutura; e o reuso, onde a herança facilita a reutilização de conhecimento, economizando tempo e recursos. 
  
Por outro lado, as desvantagens incluem a complexidade, pois a flexibilidade e a riqueza dos frames podem dificultar sua implementação e gerenciamento; o overhead, com o uso extensivo de procedimentos e heranças podendo causar sobrecarga computacional em sistemas grandes; e a ambiguidade, onde a definição inadequada de slots e valores padrão pode resultar em ambiguidades e erros na interpretação dos dados.


### Ontologias
Ontologias são representações formais de um conjunto de conceitos e categorias que representam um domínio específico e as relações entre eles. São amplamente utilizadas para modelar conhecimento de forma que ele possa ser compartilhado e reutilizado entre diferentes sistemas e aplicações. Elas permitem a modelagem de um domínio de conhecimento de maneira que as relações entre os conceitos e as regras de inferência possam ser formalmente especificadas.
  
A ontologia desempenha um papel importante no avanço de sistemas inteligentes, como assistentes virtuais, chatbots, sistemas de recomendação, entre outros. Ao oferecer uma estrutura de conhecimento compartilhada e claramente definida, ela contribui para aprimorar a precisão, a consistência e a eficiência das interações entre humanos e máquinas.
  
É composta por diversos elementos, sendo os principais:

1. **Classes (Conceitos):** Representam categorias ou tipos de coisas no domínio. Por exemplo, em uma ontologia de animais, "Mamífero" e "Ave" seriam classes.
2. **Indivíduos (Instâncias):** Representam objetos ou entidades específicas que pertencem a uma ou mais classes. Por exemplo, "Baleia" pode ser um indivíduo da classe "Mamífero".
3. **Propriedades (Relações):** Descrevem atributos dos indivíduos e relacionamentos entre eles. Dividem-se em:
	**-** **Propriedades de Dados (Data Properties):** Relacionam indivíduos a valores de dados (números, textos, datas).
	**-** **Propriedades de Objetos (Object Properties):** Relacionam indivíduos a outros indivíduos.
4. **Axiomas:** Declarações que especificam fatos sobre classes e propriedades, incluindo restrições e regras.
   
### OWL (Web Ontology Language)
  OWL é uma linguagem de marcação baseada em XML desenvolvida pelo W3C para criar e compartilhar ontologias na web. Baseada na lógica de descrição, OWL permite definir classes, propriedades e relações complexas entre conceitos, facilitando a interoperabilidade e a inferência semântica em aplicações web.
  
Uma ontologia OWL é composta por diversos elementos fundamentais, como classes, propriedades, indivíduos e axiomas, todos expressos em uma sintaxe baseada em RDF/XML. 

### Vantagens e Desvantagens
  Ontologias OWL oferecem diversas vantagens, como a capacidade de definir conceitos e relações de forma detalhada e precisa, facilitando a expressividade do conhecimento. Além disso, permitem inferência automática de novos conhecimentos a partir dos dados existentes e promovem a interoperabilidade entre sistemas e domínios, facilitando a integração e o compartilhamento de informações. 
  
  No entanto, apresentam desafios como a complexidade na criação e manutenção de ontologias complexas, que requerem expertise especializada, além da possível intensidade computacional na realização de inferências em ontologias muito grandes e complexas. O uso eficiente de OWL e suas ferramentas associadas também pode demandar uma curva de aprendizado significativa.
