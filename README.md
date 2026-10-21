# Sistemas-Distribuídos-21-10-aula-7

# Relógios Vetoriais e Causalidade

Fiz esse projeto em Python para a atividade prática da Aula 7 de Sistemas Distribuídos.

Comecei criando a classe Processo, com os métodos para registrar os eventos e mostrar os vetores na tela. Depois, implementei o envio e o recebimento de mensagens, para simular a comunicação entre três processos, chamados A, B e C.

Na execução, cada processo começa com seu próprio vetor. Quando uma mensagem é enviada e recebida, os valores são atualizados de acordo com os eventos que aconteceram. Fiz a simulação do envio de A para B e depois de B para C, acompanhando as mudanças nos vetores pelo terminal.

Também fiz o desafio dos eventos concorrentes, usando os vetores D1 e D2 para verificar se existia uma relação causal entre eles.

Por último, fiz o desafio extra, criando a função aconteceu_antes() e testando diferentes vetores. Com isso, consegui verificar quando um evento aconteceu antes de outro e quando essa relação não existe.

Para executar o projeto, basta ter o Python instalado e rodar o arquivo vetor.py pelo terminal usando o comando python vetor.py.
