# 🤖 Super Prompt's

<div align="center">

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![AI](https://img.shields.io/badge/AI-Prompts-purple.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)

**Uma coleção curada de prompts profissionais para maximizar a eficiência em Inteligência Artificial**

[Características](#-características) • [Categorias](#-categorias) • [Como Usar](#-como-usar) • [Contribuir](#-contribuindo) • [Licença](#-licença)

</div>

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Características](#-características)
- [Categorias](#-categorias)
- [Como Usar](#-como-usar)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Melhores Práticas](#-melhores-práticas)
- [Exemplos de Uso](#-exemplos-de-uso)
- [Contribuindo](#-contribuindo)
- [Roadmap](#-roadmap)
- [Licença](#-licença)
- [Contato](#-contato)

---

## 🎯 Sobre o Projeto

Este repositório contém uma **coleção profissional de super prompts** otimizados para uso com modelos de IA generativa (ChatGPT, Claude, Gemini, etc.). Cada prompt foi cuidadosamente elaborado para:

- ✨ **Maximizar a precisão** das respostas
- 🎯 **Reduzir ambiguidades** e erros de interpretação
- 🚀 **Acelerar o workflow** em tarefas repetitivas
- 📚 **Padronizar outputs** com qualidade profissional
- 🔧 **Facilitar adaptações** para diferentes contextos

> **Nota:** Estes prompts foram testados e refinados em cenários reais de desenvolvimento, análise de dados, migração de sistemas e automação de processos.

---

## ✨ Características

### 🎨 Design Profissional
- Prompts estruturados com seções claras
- Instruções step-by-step para resultados consistentes
- Exemplos práticos incluídos em cada prompt

### 🔄 Versatilidade
- Compatível com múltiplas IAs (ChatGPT, Claude, Gemini)
- Adaptável para diferentes níveis de complexidade
- Modular: combine prompts para casos específicos

### 📊 Validação
- Testado em ambientes de produção
- Resultados verificados por especialistas
- Feedback da comunidade incorporado

### 🚀 Performance
- Otimizado para respostas rápidas e precisas
- Minimiza iterações desnecessárias
- Reduz tokens utilizados sem perder qualidade

---

## 📁 Categorias

### 💻 Desenvolvimento de Software
```
├── conversao-sql-server-postgresql.md
├── otimizacao-queries-sql.md
├── geracao-testes-unitarios.md
├── refatoracao-codigo-legado.md
└── documentacao-automatica-api.md
```

### 📊 Análise de Dados
```
├── limpeza-dados-csv.md
├── analise-exploratoria-dados.md
├── geracao-dashboards-insights.md
└── modelagem-preditiva.md
```

### 📝 Escrita e Conteúdo
```
├── readme-profissional-github.md
├── documentacao-tecnica.md
├── artigos-tecnicos-blog.md
└── emails-profissionais.md
```

### 🎨 Design e UX
```
├── geracao-wireframes-texto.md
├── melhorias-ui-ux.md
└── copy-landing-pages.md
```

### 🔧 DevOps e Infraestrutura
```
├── scripts-automacao-deploy.md
├── configuracao-ci-cd.md
└── troubleshooting-logs.md
```

### 🤝 Gestão e Processos
```
├── planejamento-sprints.md
├── analise-requisitos.md
└── documentacao-processos.md
```

---

## 🚀 Como Usar

### Uso Básico

1. **Clone o repositório:**
```bash
git clone https://github.com/Laurentx1/Super_Prompt-s.git
cd Super_Prompt-s
```

2. **Navegue até a categoria desejada:**
```bash
cd prompts/desenvolvimento/
```

3. **Abra o prompt no seu editor favorito:**
```bash
cat conversao-sql-server-postgresql.md
```

4. **Copie e cole na sua IA preferida**, substituindo os placeholders:
```
[SEU_CÓDIGO_AQUI] → Cole seu código SQL Server
[CONTEXTO_ESPECÍFICO] → Descreva seu caso de uso
```

### Uso Avançado

**Combinando Prompts:**
```markdown
# Exemplo: Migração + Otimização + Documentação

1. Use o prompt de conversão SQL Server → PostgreSQL
2. Aplique o prompt de otimização de queries
3. Finalize com o prompt de documentação técnica

Resultado: Código migrado, otimizado E documentado!
```

**Personalizando Prompts:**
```markdown
# Dica: Adicione suas próprias regras

No início do prompt, inclua:
"Considerações específicas do projeto:
- Padrão de nomenclatura: snake_case
- Framework: Laravel 10
- Banco: PostgreSQL 15"
```

---

## 📂 Estrutura do Repositório

```
Super_Prompt-s/
│
├── README.md                          # Você está aqui!
├── LICENSE                            # Licença MIT
├── CONTRIBUTING.md                    # Guia de contribuição
│
├── prompts/                           # Todos os prompts organizados
│   ├── desenvolvimento/
│   │   ├── conversao-sql-server-postgresql.md
│   │   ├── otimizacao-queries-sql.md
│   │   └── ...
│   │
│   ├── analise-dados/
│   │   ├── limpeza-dados-csv.md
│   │   └── ...
│   │
│   ├── escrita-conteudo/
│   │   └── ...
│   │
│   └── ...
│
├── exemplos/                          # Casos de uso reais
│   ├── antes-depois-conversao-sql/
│   ├── analise-dados-vendas/
│   └── ...
│
├── templates/                         # Templates base reutilizáveis
│   ├── template-prompt-tecnico.md
│   ├── template-prompt-criativo.md
│   └── ...
│
└── docs/                             # Documentação adicional
    ├── melhores-praticas.md
    ├── comparacao-ias.md
    └── troubleshooting.md
```

---

## 💡 Melhores Práticas

### ✅ Do's (Faça)

1. **Seja específico:** Forneça contexto detalhado sobre seu caso de uso
2. **Use exemplos:** Inclua inputs/outputs esperados quando possível
3. **Itere:** Refine o prompt baseado nas respostas iniciais
4. **Valide:** Sempre revise o output da IA antes de usar em produção
5. **Documente:** Anote modificações que funcionaram bem para você

### ❌ Don'ts (Evite)

1. **Prompts vagos:** "Faça algo com esse código" → ❌
2. **Excesso de contexto:** Não cole arquivos inteiros sem necessidade
3. **Confiar cegamente:** IA pode cometer erros, sempre valide
4. **Ignorar warnings:** Se a IA alerta sobre algo, investigue
5. **Não testar:** Teste os outputs em ambiente seguro primeiro

---

## 📖 Exemplos de Uso

### Exemplo 1: Conversão SQL Server → PostgreSQL

**Antes de usar o prompt:**
```sql
CREATE PROCEDURE dbo.calcular_total
    @cliente_id INT,
    @total DECIMAL OUTPUT
AS BEGIN
    SELECT @total = SUM(valor) FROM pedidos WHERE cliente_id = @cliente_id
END
```

**Depois de usar o prompt:**
```sql
CREATE OR REPLACE PROCEDURE public.calcular_total(
    IN p_cliente_id INTEGER,
    INOUT p_total DECIMAL
)
LANGUAGE plpgsql
AS $procedure$
BEGIN
    SELECT SUM(valor) INTO p_total 
    FROM pedidos 
    WHERE cliente_id = p_cliente_id;
END;
$procedure$;
```

**Resultado:** ✅ Conversão 100% funcional com melhores práticas PostgreSQL!

### Exemplo 2: Otimização de Query

**Query Original (2.3s):**
```sql
SELECT * FROM vendas v
JOIN clientes c ON v.cliente_id = c.id
WHERE YEAR(v.data_venda) = 2024
```

**Query Otimizada (0.15s):**
```sql
SELECT v.id, v.valor, c.nome
FROM vendas v
INNER JOIN clientes c ON v.cliente_id = c.id
WHERE v.data_venda >= '2024-01-01' 
  AND v.data_venda < '2025-01-01'
```

**Resultado:** ⚡ **93% mais rápida** + uso correto de índices!

---

## 🤝 Contribuindo

Contribuições são **muito bem-vindas**! Este projeto cresce com a comunidade.

### Como Contribuir

1. **Fork o repositório**
2. **Crie uma branch** para sua feature:
   ```bash
   git checkout -b feature/prompt-amazing
   ```
3. **Commit suas mudanças:**
   ```bash
   git commit -m 'Add: Prompt incrível para X'
   ```
4. **Push para a branch:**
   ```bash
   git push origin feature/prompt-amazing
   ```
5. **Abra um Pull Request**

### Guidelines para Contribuições

- ✅ Prompts devem ser testados em pelo menos 2 IAs diferentes
- ✅ Inclua um exemplo de uso real
- ✅ Siga a estrutura de template existente
- ✅ Documente quaisquer limitações conhecidas
- ✅ Use Markdown formatado corretamente

Veja mais detalhes em [CONTRIBUTING.md](CONTRIBUTING.md)

---

## 🗺️ Roadmap

### ✅ Concluído
- [x] Prompts de conversão SQL Server → PostgreSQL
- [x] Prompts de otimização de queries
- [x] README profissional
- [x] Estrutura de categorias

### 🚧 Em Desenvolvimento
- [ ] Prompts para Machine Learning
- [ ] Integração com VS Code (extensão)
- [ ] Biblioteca Python para uso programático
- [ ] Versões em Inglês e Espanhol

### 🔮 Futuro
- [ ] Web app para busca de prompts
- [ ] API REST para acesso aos prompts
- [ ] Marketplace de prompts da comunidade
- [ ] Sistema de rating e reviews

---

## 📊 Estatísticas

<div align="center">

| Métrica | Valor |
|---------|-------|
| 📝 Total de Prompts | Em crescimento |
| 📂 Categorias | 6 |
| ⭐ Stars | ![GitHub stars](https://img.shields.io/github/stars/Laurentx1/Super_Prompt-s?style=social) |
| 🔄 Forks | ![GitHub forks](https://img.shields.io/github/forks/Laurentx1/Super_Prompt-s?style=social) |
| 🐛 Issues Abertos | ![GitHub issues](https://img.shields.io/github/issues/Laurentx1/Super_Prompt-s) |
| 👥 Contribuidores | ![GitHub contributors](https://img.shields.io/github/contributors/Laurentx1/Super_Prompt-s) |

</div>

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

```
MIT License - você pode:
✅ Usar comercialmente
✅ Modificar
✅ Distribuir
✅ Uso privado
```

---

## 📬 Contato

**Laurent** - [@Laurentx1](https://github.com/Laurentx1)

**Link do Projeto:** [https://github.com/Laurentx1/Super_Prompt-s](https://github.com/Laurentx1/Super_Prompt-s)

---

## 🙏 Agradecimentos

- [OpenAI](https://openai.com) pelo ChatGPT
- [Anthropic](https://anthropic.com) pelo Claude
- [Google](https://deepmind.google/technologies/gemini/) pelo Gemini
- Comunidade open-source por inspiração e feedback
- Todos os [contribuidores](https://github.com/Laurentx1/Super_Prompt-s/graphs/contributors) deste projeto

---

<div align="center">

**Se este projeto te ajudou, considere dar uma ⭐!**

Feito com ❤️ e muita ☕

[⬆ Voltar ao topo](#-super-prompts)

</div>
