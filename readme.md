# Documentação semana 3 - Experiências Imersivas

## Estrutura de pastas

Segue a estrutura de arquivos atual do diretório:

```
├── jukebox
│    ├── assets
│    ├── index.html
│
├── store_experience
│    ├── assets
│    ├── index.html
│
├── unity_project
│    ├── Assets
│    ├── Logs
│    ├── Packages
│    ├── ProjectSettings
│    ├── UserSettings
│    ├── My project.sln
│
├── README.md
```

-   unity_project: Projeto que envolveu a instalação do Unity, a construção de uma cena, e a adição de diversos assets para aprimorar a experiência visual e funcional.
-   store_experience: Evolução do Unity Project, desenvolvido com o A-frame, incorporando animações e sons para uma experiência interativa mais imersiva.
-   jukebox: Projeto criado para explorar e aplicar conceitos de áudio, utilizando uma jukebox como exemplo prático para o aprendizado.
-   readme.md: Documentação oficial do projeto.

## Processo de desenvolvimento

### Unity Project

O projeto "Unity Experience" foi desenvolvido para replicar o ambiente interativo do *Store Experience*, adaptando seus elementos ao ecossistema da Unity. Ele utiliza os mesmos **assets visuais e modelos 3D** do *Store Experience*, mas com algumas mudanças no cenário devido a limitações de compatibilidade.

Assim como na versão do a-frame, os usuários podem explorar um espaço tridimensional com foco em interação e imersão. No entanto, a casa que estava presente no Store Experience precisou ser substituída no ambiente da Unity por questões técnicas. Apesar disso, os outros elementos principais — texturas e modelos foram mantidos, garantindo que a essência do projeto fosse preservada.

A Unity foi utilizada para aproveitar sua capacidade de renderização avançada e maior controle sobre física e iluminação, tornando a experiência visual ainda mais fluida e atraente. 


### Store Experience

O desenvolvimento desse foi realizado utilizando o A-frame para criar uma experiência interativa em realidade virtual baseada em um ambiente imersivo e interativo. O principal objetivo deste projeto foi evoluir as práticas aprendidas na Unity, mas agora utilizando tecnologias voltadas para aplicações web. O foco estava em combinar modelos 3D, sons, e interações para proporcionar uma experiência rica e envolvente.

Durante o processo, foi criado um cenário que simulava uma sala de estar aconchegante, onde diversos modelos 3D foram integrados, incluindo um personagem principal, roupas, um espelho, e o ambiente em si.

A interação do usuário foi um dos principais pontos explorados no projeto. Teclas do teclado foram mapeadas para controlar diferentes ações no ambiente. Por exemplo, ao pressionar a tecla "P", o personagem realiza uma animação de aceno enquanto um audio de introdução é tocado. Já a tecla "R" permite alternar a visibilidade da roupa no cenário, simulando a ação de vesti-las ou removê-las. Adicionalmente, a tecla "T" ativa uma rotação contínua nas roupas, criando um efeito dinâmico.

Outro elemento crucial foi a trilha sonora, que inclui música de fundo que toca automaticamente ao entrar na cena, contribuindo para uma atmosfera imersiva. Além disso, sons adicionais foram integrados para acompanhar interações específicas, como a animação do personagem, enriquecendo a experiência sensorial.

### Jukebox

O projeto foi desenvolvido com o objetivo de proporcionar uma experiência imersiva e interativa, onde os usuários podem escolher músicas e visualizar imagens associadas diretamente em um ambiente virtual.

No ambiente, os usuários encontram um cenário virtual com uma máquina de música como ponto central, cercada por elementos interativos que representam diferentes opções de seleção. Três cilindros coloridos foram configurados para servir como botões de ativação. Cada cilindro está associado a uma música específica e a uma imagem correspondente, criando uma conexão audiovisual que enriquece a experiência do usuário. Ao interagir com um cilindro, seja clicando ou pressionando as teclas configuradas no teclado, a música correspondente começa a tocar, e a imagem associado é exibido em uma tela localizada na máquina de música.

Além da funcionalidade de seleção, foi implementado um mecanismo que garante que apenas uma música toque por vez. Sempre que uma nova música é ativada, todas as outras são interrompidas, e o tempo de reprodução é redefinido, garantindo uma transição fluida entre as opções. A exibição dinâmica das imagem, que acompanha a música selecionada, complementa a experiência.