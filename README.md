# Recortar Arquivos de Áudio

Este é um script Python simples para auxiliar na organização e cópia de arquivos de áudio listados em arquivos Excel. Ele foi criado para facilitar tarefas de classificação e organização de arquivos de áudio em um projeto específico.

## Observação: 
Não consigo importar a pasta PT-BR-SSDforSER que contem os arquivos de audio, pois ela é muito extensa. Mas em resumo é uma pasta contendo 12k de arquivos de áudio na extensão .WAV divididos em audios de 1 a 5 segundos cada. 

## Funcionalidades Principais

- **Leitura de Arquivos Excel**: O script é capaz de ler arquivos Excel na pasta especificada e extrair os caminhos dos arquivos de áudio contidos neles.

- **Cópia de Arquivos de Áudio**: Ele copia os arquivos de áudio correspondentes da pasta de áudio de origem para uma pasta de destino especificada.

- **Organização em Subpastas**: Os arquivos de áudio copiados são organizados em subpastas, seguindo critérios específicos.

## Como Usar

1. **Configuração das Pastas**: Antes de executar o script, é necessário configurar as pastas de origem e destino. Você pode fazer isso editando diretamente o script e ajustando os caminhos para as pastas desejadas.

2. **Execução do Script**: Após configurar as pastas, basta executar o script Python. Você pode fazer isso através do terminal ou da IDE Python de sua preferência.

## Requisitos

- **Python 3.11**: Certifique-se de ter Python 3.x instalado em seu sistema.
- **Pandas**: O Pandas é utilizado para ler os arquivos Excel.
- **Módulos OS e shutil**: Módulos padrão do Python utilizados para operações de sistema e cópia de arquivos.
- **Arquivos Excel**: Os arquivos Excel na pasta de origem devem estar no formato .xlsx.

## Exemplo de Uso

Suponha que você tenha arquivos Excel na pasta 'arquivos_divididos', arquivos de áudio na pasta 'PT-BR-SSDforSER', e deseje copiar os arquivos de áudio para a pasta 'Arquivos_Copiados'.

```python
pasta_excel = 'caminho/para/arquivos_divididos'
pasta_audios = 'caminho/para/PT-BR-SSDforSER'
pasta_destino = 'caminho/para/Arquivos_Copiados'

recortar_arquivos_audio(pasta_excel, pasta_audios, pasta_destino)
```
