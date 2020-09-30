![foto](docs/logo.png)                                            
# O que é o projeto Além dos Olhos?
Projeto open source para criação de modelos 3D a partir de imagens, usando placas de desenvolvimento que possibilitem processamento de imagens na ponta.

## Como surgiu o projeto?
Este projeto foi desenvolvido para possibilitar fotografias acessíveis a pessoas com deficiência visual. Desenvolvemos uma oficina de fotografia para um grupo de pessoas cegas e baixa visão, o resultado dessa oficina foi traduzido para obras em relevo. Visamos que o desenvolvimento da leitura de imagem dê liberdade ao leitor cego para que ele consiga compreender as imagens a partir de suas referências e não somente por uma áudio descrição. Conjuntamente estimular a inclusão, não só desse grupo como também outros grupos minoritários no âmbito da fotografia.

![fotometria](docs/fotometria.gif) 

## Resultados
* Realização da [Oficina de fotografia](http://www.youtube.com/watch?v=k0_edVc_BuE) para um grupo de pessoas cegas e baixa visão
* Modelagem utilizado técnicas de fotométria para obter uma malha bruta que foi refinada posteriormente no Zbrush
* A confecção das peças foi feita na Fresadora CNC, ferramenta que nos permitiu dar as peças a maior quantidade de detalhes como gostaríamos, neste processo o [L.O.U.Co - Laboratório de Objetos Urbanos Conectados](https://www.instagram.com/portodigitalouco/) foi fundamental.
* Realização uma [exposição](https://www.behance.net/gallery/70063129/Alm-dos-Olhos) no Apolo 235, localizado no Porto Digital.
* Publicação de [artigo](https://dl.acm.org/doi/10.1145/3357155.3358456) no IHC'19
 

# Objetivo
Inicialmente o projeto tinha como objetivo o desenvolvimento de uma forma de leitura das imagens tiradas na oficina, para pessoas cegas e de baixa visão. No decorrer do projeto, ampliamos os nossos horizontes e hoje temos como objetivo colaborar na criação de uma máquina fotográfica que gere arquivos tanto da imagem 2D como da imagem a ser esculpida ou impressa em 3D. Para isso queremos criar/melhorar os algoritmos de processamento de imagens que geram modelos 3D e aplicá-los em placas de desenvolvimento como Raspberry Pi, UP Square etc.

## Materiais de Estudo

| Título  |  Tópico  | Link de acesso |
| ------------------- | ------------------- | ------------------- |
|  Convert Images to 3D STL format |  Converter |  [Link](https://github.com/rmrao/img2stl) |
|  Consistent Video Depth Estimation |  Dephmap |  [Video](https://www.youtube.com/watch?v=5Tia2oblJAg) |

## Desafios atuais

* Melhoramento do dephmap

## Como posso colaborar?

Existem duas branchs: `master` e `develop`
- `master` : é o branch no qual está o código que está em produção, ou seja, que está sendo diretamente usado pelos usuários da ferramenta. Não se deve ter commits soltos; devemos apenas adicionar commits nele através de merges de branches de release e de hotfix.
- `develop` : é o que contém o código previsto para a próxima release, ou seja, o próximo código que irá pro ar. nele, também não devemos commitar diretamente, deixando que seu código seja fornecido pelos branches de feature e hotfix, mas essa regra é um pouco mais flexível que a do master.

Para criar uma nova funcionalidade ou corrigir algo, você deve abrir uma branch com base em `master`. Essa *branch* , apesar de nem sempre ser uma *feature*, é chamada de *feature branch*. Ela deve seguir o seguinte esquema de nome: `[tipo]/[descricao-da-funcionalidade]`

Os possíveis `tipos` são:
- **feature:** nova funcionalidade ou comportamento
- **fix:** correção de bug
- **update:** atualização de dependência


## Autores
* Arlindo Gomes - Modelagem 3D
* Cristiana Soares - Fotografia
* Laís Bandeira - Desenvolvimento de hardware
