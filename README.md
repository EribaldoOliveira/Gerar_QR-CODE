# QR Code Generator

Este é um simples gerador de QR Code em PHP que utiliza uma biblioteca chamada `qrcode.php` para criar QR Codes com base em um texto fornecido pelo usuário. O QR Code gerado é salvo como uma imagem PNG no diretório `files` e pode ser visualizado ou baixado através de um link.

---

## Funcionalidades

- Aceita um texto enviado pelo usuário através de um formulário.
- Gera uma imagem de QR Code com dimensões personalizáveis (500x500 pixels por padrão).
- Salva a imagem no diretório `files` com um nome único (hash MD5 baseado no timestamp atual).
- Exibe um link para visualizar o QR Code gerado.

---

## Pré-requisitos

- PHP instalado no servidor (versão mínima 7.0 ou superior recomendada).
- Extensão `GD` habilitada no PHP (necessária para a manipulação de imagens).
- Biblioteca `qrcode.php` disponível no mesmo diretório do script.

---

## Estrutura do Projeto

```plaintext
|-- index.php          # Script principal para gerar QR Codes
|-- qrcode.php         # Biblioteca para criar QR Codes
|-- files/             # Diretório onde as imagens geradas serão armazenadas


![image](https://github.com/user-attachments/assets/b651e813-5b0c-4e01-b12b-ccc01829cc87)
