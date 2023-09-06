# Lab02a-Processos
## Integrantes
Enrico Najjar Galdeano - 32260407

Rodrigo Mironiuc Fernandes - 32274823

Mauricio Gabriel Gutierrez Garcia - 32266601

## Instruções
instalar git e gcc

Clonar o repositório : `git clone https://github.com/rodmironiuc/Lab02a-Processos.git`

Compilar os exemplos : `gcc (nomeDoArquivo) -o (novoArquivoExecutavel)`

Executar o arquivo criado : `./(novoArquivoExecutavel)`

## Respostas
1) Não, as mensagens não estarão sempre ordenadas pelo valor de i. O sistema operacional determina a ordem de 
execução dos processos, a qual pode variar.

2) Com o sys.stderr as mensagens são impressas na saída de erro. Se fosse substituído por sys.stdout seriam impressas na saída padrão, exibidas na tela ao executar o programa e com alteração na formatação. Devido a essa diferença, se estiverem sendo executadas muitas instâncias ao mesmo tempo, a interpretação pode se tornar mais complicada para o usuário.
