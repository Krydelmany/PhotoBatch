# Projeto de Alteração de Arquivos em Lote

Este projeto visa facilitar a manipulação em lote de arquivos, oferecendo funcionalidades como a conversão entre formatos de imagem (PNG para JPEG e vice-versa), renomeação em massa com a possibilidade de adicionar números sequenciais, e redimensionamento flexível das imagens.

## Funcionalidades Principais

1. **Conversão de Formato:**
   - Transformação de imagens PNG para JPEG.
   - Transformação de imagens JPEG para PNG.

2. **Renomeação em Massa:**
   - Renomeação de arquivos para um nome especificado.
   - Adição de números sequenciais, por exemplo, de 5 a 30.

3. **Redimensionamento de Imagens:**
   - Ajuste do tamanho das imagens para torná-las menores ou maiores.
   - Opção para triplicar ou multiplicar o valor original do redimensionamento.

## Utilização por Linha de Comando

O projeto é executado por meio de comandos na linha de comando. Abaixo estão alguns exemplos de como usar as funcionalidades:

```bash
# Transformar PNG para JPEG
comando --converter png_para_jpeg --diretorio /caminho/do/diretorio

# Renomear arquivos com prefixo e números sequenciais
comando --renomear prefixo_nome_ --sequencial_de 5 --sequencial_ate 30 --diretorio /caminho/do/diretorio

# Redimensionar imagens para o dobro do tamanho original
comando --redimensionar 2 --diretorio /caminho/do/diretorio
```

## Futuras Melhorias

O projeto atualmente opera exclusivamente por linha de comando, mas há planos para aprimorá-lo com uma interface gráfica de usuário (GUI) no futuro. Isso tornará a utilização mais amigável e acessível a usuários que não estão familiarizados com comandos de linha.

Fique à vontade para contribuir, reportar problemas ou sugerir melhorias para o projeto!

**Nota:** Certifique-se de ter as dependências necessárias instaladas antes de usar o projeto. Consulte o arquivo `requirements.txt` para obter mais informações sobre as dependências.
