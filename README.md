# 🌧️ AlagaSorocaba

**Mapa colaborativo de alagamentos em tempo real para Sorocaba – SP.**

> Plataforma web onde moradores reportam pontos de alagamento na cidade, visualizam ocorrências ativas no mapa e consultam o histórico de pontos crônicos.

---

## 📸 Demo

> Versão demo com dados em memória — nenhum dado é persistido entre sessões.

**Login de acesso rápido:**
- **E-mail:** `demo@teste.com`
- **Senha:** `123456`

---

## ✨ Funcionalidades

- **🗺️ Mapa ao vivo** — visualização de alagamentos ativos sobre mapa interativo (Leaflet.js) centrado em Sorocaba
- **📍 Reporte colaborativo** — qualquer usuário autenticado pode marcar um novo ponto de alagamento clicando no mapa
- **🚨 Níveis de gravidade** — Leve 💧 / Moderado 🌊 / Crítico 🚨 / Resolvido ✅
- **📷 Upload de foto** — possibilidade de anexar imagem ao reportar
- **⏱️ Expiração automática** — ocorrências somem após 2 horas
- **📊 Histórico** — aba com pontos crônicos de alagamento da cidade e número de ocorrências registradas
- **🔴 Indicador ao vivo** — pill animada mostrando status em tempo real
- **🌙 Alternância de tema** — toggle entre modo claro e escuro
- **👤 Autenticação simples** — login e cadastro de usuário (em memória na versão demo)

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 / CSS3 | Estrutura e estilização |
| JavaScript (Vanilla) | Lógica da aplicação |
| [Leaflet.js 1.9.4](https://leafletjs.com/) | Mapa interativo |
| [DM Sans / DM Mono](https://fonts.google.com/) | Tipografia |

> Projeto 100% front-end, sem dependências de back-end ou build tools — basta abrir o arquivo `.html` no navegador.

---

## 🚀 Como usar

1. Faça o download ou clone este repositório
2. Abra o arquivo `AlagaSorocaba-Demo.html` diretamente no navegador
3. Faça login com as credenciais de demo ou crie uma nova conta
4. Explore o mapa, veja ocorrências ativas e reporte novos alagamentos

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/alaga-sorocaba.git

# Abrir no navegador (macOS)
open AlagaSorocaba-Demo.html

# Abrir no navegador (Linux)
xdg-open AlagaSorocaba-Demo.html
```

---

## 📂 Estrutura do projeto

```
alaga-sorocaba/
└── AlagaSorocaba-Demo.html   # Aplicação completa (single-file)
```

---

## 🗺️ Pontos crônicos mapeados

| Bairro | Local | Ocorrências hist. |
|---|---|:---:|
| Centro | Av. Independência (entre R. Boa Morte e R. Souza Menezes) | 47 |
| Vila Hortência | Rua 15 de Novembro próx. à Praça | 38 |
| Éden | Terminal Éden — acesso sul | 31 |
| Jardim Paulistano | Cruzamento Av. Itavuvu com R. Lauro Gomes | 24 |
| Wanel Ville | Rua Comendador Oeterer próx. ao viaduto | 19 |
| Alto da Boa Vista | Praça Cel. Fernando Prestes | 14 |

---

## 🔮 Próximos passos (roadmap sugerido)

- [ ] Back-end com persistência real (Firebase / Supabase)
- [ ] Notificações push ao surgir novo alagamento crítico próximo ao usuário
- [ ] Integração com API de chuva / meteorologia
- [ ] PWA com suporte offline
- [ ] Moderação de reportes (votação da comunidade)
- [ ] App mobile nativo

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Abra uma _issue_ para sugestões ou envie um _pull request_.

1. Faça um fork do projeto
2. Crie sua branch: `git checkout -b feature/minha-feature`
3. Commit suas alterações: `git commit -m 'feat: minha feature'`
4. Push para a branch: `git push origin feature/minha-feature`
5. Abra um Pull Request

---

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

---

<p align="center">Feito com ❤️ para Sorocaba 🌧️</p>
