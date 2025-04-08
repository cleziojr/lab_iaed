# ITS-IT: Template para Implementação de um Intelligent Tutor System para o Concursos de Nível Superior na área de Tecnologia da Informação

**Bem-vindo(a)!** Este repositório é um trabalho em andamento (work in progress) utilizado para propósitos ilustrativos de como um ITS pode ser implementado para concursos públicos que avaliem o conhecimento na área de Tecnologia da Informação. 

O repositório tem objetivo de servir como template base para implementação do seu ITS. 

## O que fazer neste repositório?

Um ITS é formado por três componentes principais:

- Um modelo de domínio que define a estrutura de tópicos e áreas do seu conteúdo.
- Um modelo pedagógico que define as regras de feedback do ITS.
- Um modelo de aluno que define em variáveis sobre o processo de aprendizagem do aluno diante das questões do ENEM.

Para projetar o seu próprio ITS, você deve então começar por:

1. Implementar o seu próprio modelo de domínio (model/domain.yml)
2. Implementar o seu próprio modelo pedagógico (model/pedagogy.yml)
3. Implementar o seu próprio modelo de aluno (model/learner.py)

> Dica: Na pasta `model` você encontrará arquivos `domain.yml`, `pedagogy.yml` e `learner.py` que servirão de base para o seu ITS.

Após a fase de design, você deve então implementar o controlador e uma interface de usuário.

1. Implementar o seu próprio controlador (controller.py)
2. Implementar o seu próprio UI e/ou open learner model


## 📚 Mais sobre o exemplo do ITS-IT

 Pitch: "ITS-IT fornece tutoria de estudos em tópicos e áreas de **Tecnologia da Informação** com dicas de estudo para fortalecer sua auto-determinação e confiança para o próximo exame! 🚀"

## ❓ Do Que Se Trata?
- **📝 Dicas Inteligentes**: Baseado no seu gabarito do ano anterior, diz o que você precisa estudar (ex: "Revise Banco de Dados!").
- **😊 Feedback Legal**: Te incentiva com mensagens como "Você é craque em Tecnologia da Informação!" nos tópicos que você foi bem.

## 💡 Como Isso Funciona?
- **Entradas**: Escolha A, B, C, D ou E.
- **Saidas**: Receba um relatório pedagogicamente significativo com tópicos e áreas para focar nos seus estudos para futuros exames.

## 🏃 Como Executar o Código?
1.  **Obtenha o código**: `git clone https://github.com/cleziojr/lab_iead.git`
2.  **Configure**: `cd lab_iead` , então  `pip install -r requirements.txt`
3.  **Execute!**: Você pode utilizar o ITS abrindo o `lab_iead.ipynb` e executando as células do notebook. Tente mudar o seu gabarito para ver como o ITS se comporta com diferentes respostas.


## 💬 Fórum de Discussões
Entre em contato pelo [GitHub](https://github.com/cleziojr/lab_iead/issues)! 😊
