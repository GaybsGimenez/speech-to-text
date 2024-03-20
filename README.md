# Conversor de Áudio para Texto

Este script Python foi desenvolvido para realizar a transcrição de arquivos de áudio em texto usando a função de Speech to Text. Ele utiliza a biblioteca SpeechRecognition para realizar essa conversão.
Dado o arquivo contendo os áudios, ele transcreve os arquivos .wav e depois transcreve em um arquivo csv contendo a transcrição e o caminho do arquivo de audio correspondete. 

## Instalação

Para executar este script, é necessário instalar a biblioteca SpeechRecognition. Você pode instalar usando pip:

```
%pip install SpeechRecognition
```

## Função Speech to Text

A função `transcrever_audio(audio_path)` recebe o caminho para um arquivo de áudio como entrada e retorna o texto transcrito. Ele usa o reconhecedor de fala da SpeechRecognition para realizar essa tarefa. Se o áudio for em português do Brasil, o parâmetro `language` deve ser definido como 'pt-BR'.

## Execução

### Para executar o script, siga estas etapas:
*Lembre-se de executar as célular em ordem*

1. Coloque seus arquivos de áudio na pasta `PT-BR-SSDforSER`. Certifique-se de que os arquivos de áudio estejam no formato .wav.
2. Execute o script. Ele transcreverá todos os arquivos de áudio na pasta especificada e salvará as transcrições em um arquivo CSV chamado `transcricoes.csv`.
3. As transcrições concluídas serão salvas no arquivo CSV especificado.


