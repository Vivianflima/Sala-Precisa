# Sala Precisa - Repositório de Arquivos para Testes

Bem-vindo(a) à "Sala Precisa"! Inspirado na misteriosa "Sala Precisa" de Hogwarts, a Sala que possui tudo o que você precisa no momento, este repositório foi criado para fornecer uma variedade de arquivos que podem ser utilizados por QAs e testers em seus testes e avaliações, especialmente em cenários de upload de arquivos diversos e de diferentes tamanhos. Aqui você encontrará arquivos de diferentes formatos, como imagens, áudios, vídeos, documentos e muito mais.

## Como usar este repositório

1. Navegação: Use a interface do GitHub para explorar os arquivos nesta Sala Precisa. Você pode navegar pelas pastas para encontrar os arquivos organizados por tipo ou tamanho.

2. Download: Para baixar um arquivo, basta abrir o arquivo desejado e clicar no botão "Download". Isso fará o download do arquivo para o seu computador.

3. Clonar o repositório: Se preferir, você pode clonar toda a Sala Precisa para obter todos os arquivos em seu ambiente local. Use o comando Git no Terminal (ou Prompt de Comando no Windows):

`git clone https://github.com/vivianflima/sala-precisa.git`

Isso criará uma cópia local de todos os arquivos da Sala Precisa em seu sistema.

## Criando arquivos de tamanhos específicos através da linha de comando: 

Se você precisar criar arquivos de tamanhos específicos para seus testes, você pode usar os seguintes exemplos de comandos em diferentes sistemas operacionais:

### Windows

Para criar um arquivo de tamanho específico no Windows, você pode usar o utilitário "fsutil" no Prompt de Comando. Abra o "Prompt de Comando" e use o seguinte comando:

Para criar um arquivo JPG de 50 MB:
`fsutil file createnew "C:\caminho_do_arquivo\Fakefile_50mb.jpg" 52428800`


Para criar um arquivo MP4 de 100 MB:
`fsutil file createnew "C:\caminho_do_arquivo\Fakefile_100mb.mp4" 104857600`


### Mac e Linux

No macOS e nas distribuições Linux, você pode usar o comando "dd" para criar arquivos de tamanhos específicos. Abra o Terminal e utilize o seguinte comando:

Para criar um arquivo WAV de 30 MB:
`dd if=/dev/zero of="/caminho_do_arquivo/Fakefile_30mb.wav" bs=31457280 count=1`


Para criar um arquivo PDF de 5 MB:
`dd if=/dev/zero of="/caminho_do_arquivo/Fakefile_5mb.pdf" bs=5242880 count=1`

Certifique-se de substituir `/caminho_do_arquivo/` pelo caminho da pasta onde você deseja criar o arquivo em seu sistema. Isso garantirá que os arquivos sejam criados no local correto.

Lembre-se também de que esses comandos criarão arquivos vazios com os tamanhos especificados. O tamanho real do arquivo criado pode ser ligeiramente maior devido a metadados e informações de formatação.

### Conversão de MB para Bytes

Para criar arquivos de tamanhos específicos, é importante entender a conversão de MB (megabytes) para bytes, pois os comandos requerem o tamanho em bytes para funcionar corretamente. Aqui está uma tabela de conversão para ajudar você a determinar o tamanho em bytes para diferentes valores em MB:

| Tamanho em MB | Tamanho em Bytes |
|---------------|------------------|
| 1 MB          | 1.048.576 bytes  |
| 5 MB          | 5.242.880 bytes  |
| 10 MB         | 10.485.760 bytes |
| 30 MB         | 31.457.280 bytes |
| 50 MB         | 52.428.800 bytes |
| 100 MB        | 104.857.600 bytes|

Por exemplo, se você deseja criar um arquivo de 30 MB, será necessário usar o valor de 31.457.280 bytes no comando.

Lembre-se de que o tamanho real do arquivo criado pode ser ligeiramente maior devido a metadados e informações de formatação. Caso precise de um tamanho de arquivo exato, faça ajustes no número de bytes para alcançar o tamanho desejado.

Aproveite os arquivos desta Sala Precisa para auxiliar nos seus testes de upload e garantir a robustez e qualidade dos seus projetos. Se tiver alguma dúvida ou sugestão, sinta-se à vontade para abrir uma "Issue" e compartilhar sua opinião.

Que os seus testes sejam tão mágicos e precisos quanto a "Sala Precisa" de Hogwarts! 🪄🔮

Divirta-se testando na "Sala Precisa"! 🚀
