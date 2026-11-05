# Vinícius Silva

Desenvolvedor sênior full stack em São Paulo. Software, integrações e IA orientada por especificações.

- **Backend:** C#, .NET, Node.js, Java e APIs REST.
- **Frontend:** React, Vue.js, Nuxt e Angular.
- **Integrações:** arquitetura orientada a eventos, Kafka e webhooks.
- **Dados e cloud:** SQL Server, PostgreSQL, Oracle, Firebase, Cosmos DB e Azure.
- **IA no desenvolvimento:** Codex e SDD (Spec-Driven Development).

[Portfólio ao vivo](https://viniciuzvieira.github.io/) · [LinkedIn](https://www.linkedin.com/in/viniciuzvieira/) · [Currículo em PDF](dist/docs/Vinicius_Silva_CV.pdf) · [E-mail](mailto:vinicius.silva@zcore.com.br)

## Portfólio

Site estático responsivo, com linguagem visual inspirada em [vidaltech.cloud](https://www.vidaltech.cloud/), adaptado à minha trajetória e aos meus comprovantes.

- Comparador local de competências com evidências do currículo.
- Linha do tempo profissional e frentes de atuação.
- Fluxo de desenvolvimento com IA e SDD.
- Galeria com seis comprovantes, filtros, imagens ampliáveis e links para as fontes.
- Currículo em uma página, com texto selecionável e links clicáveis.

O comparador reconhece palavras-chave de um conjunto definido de competências; serve para orientar a conversa técnica. Não depende de API, chave ou backend.

## Executar localmente

Sirva a pasta `dist` com qualquer servidor HTTP estático. Com Python:

```sh
python -m http.server 4173 --directory dist
```

Abra `http://localhost:4173`.

## Publicação no GitHub Pages

O workflow `.github/workflows/pages.yml` publica a pasta `dist` a cada alteração na branch `main`. O GitHub Pages está configurado para usar **GitHub Actions**. Acesse o [portfólio publicado](https://viniciuzvieira.github.io/).

## Atualizar conteúdo

- `dist/index.html`: apresentação, experiência, SDD, competências e contatos.
- `dist/app.js`: comprovantes e regras do comparador de vagas.
- `dist/styles.css`: identidade visual e comportamento responsivo.
- `dist/assets/`: foto e imagens dos certificados.
- `dist/docs/`: currículo e cópia do comprovante de graduação com identificadores pessoais omitidos.

As datas da trajetória foram conferidas no LinkedIn e a conclusão da graduação segue o certificado do Senac (2019). O curso preparatório de AWS é identificado como curso, separado da certificação Microsoft AZ-900.

Projeto produzido com apoio do Codex. Não há conteúdo ou credenciais de projetos corporativos neste repositório.
