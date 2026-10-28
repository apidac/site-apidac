# site-apidac

Site institucional da Associação Piauiense em Defesa da Advocacia Consumerista (APIDAC).

## Executar localmente

O projeto usa HTML, CSS e JavaScript, sem instalação de dependências ou etapa de compilação.

```sh
python3 -m http.server 4173 --directory dist
```

Abra http://localhost:4173.

## Estrutura

- `dist/index.html`: página institucional e formulário de afiliação.
- `dist/style.css`: identidade visual e layouts responsivos.
- `dist/app.js`: navegação, galeria ampliada e fluxo do formulário.
- `dist/assets/`: logo, banner e fotografias fornecidas para o projeto.
- `dist/formulario-apidac.docx`: modelo de inscrição em branco.

Para hospedar como site estático, utilize `dist` como diretório de publicação.

## Afiliação

Fluxo demonstrativo: dados pessoais → dados profissionais → Pix → documentos e comprovante → revisão e envio simulado.

Nesta versão é possível avançar sem preencher dados. Nenhuma inscrição é transmitida ou armazenada. A chave Pix, o beneficiário e o valor permanecem pendentes. Os dados confirmados podem ser configurados no objeto `pix` em `dist/app.js`.

Antes de receber inscrições reais, implementar validação no servidor, entrega de e-mail com anexos e proteção contra abuso; confirmar as regras de admissão, disponibilizar o Estatuto e definir o tratamento dos dados pessoais. Confirmar também a apresentação da presidência com a associação.
