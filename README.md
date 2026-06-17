# 🛡️ AnjoGuardião — Rede de Proteção Digital para Idosos

> Autonomia com segurança • Cuidado sempre presente

Protótipo de interface web do sistema **AnjoGuardião**, uma fintech voltada à proteção financeira de idosos, desenvolvido como atividade prática da disciplina de Prototipação do curso de **Análise e Desenvolvimento de Sistemas — FIAP**.

---

## 📋 Sobre o Projeto

O AnjoGuardião é um sistema de proteção financeira inteligente que monitora transações, detecta comportamentos suspeitos e notifica contatos de confiança ("Anjos da Guarda") em tempo real.

Este repositório contém a implementação da **Tela de Alertas de Segurança (UC02)**, responsável por exibir e tratar transações suspeitas detectadas pelo sistema.

## 🖥️ Tela Implementada

### Alertas de Segurança — Validação de Transação Suspeita (UC02)

A tela apresenta ao usuário uma transação fora do padrão identificada pelo sistema, permitindo que ele tome uma ação imediata:
 Elementos:
 Descrição 
- 🔴 Banner de alerta 
 Destaque visual imediato de risco com ícone animado 

- 💳 Card de transação 
 Valor, estabelecimento, horário e contexto da compra suspeita 

- ❌ Botão "Não fui eu" 
 Bloqueia a operação imediatamente 

- ✅ Botão "Sim, fui eu" 
 Confirma e libera a compra 
 
- ⏱️ Contagem de 3 min 
 Notifica Anjo da Guarda automaticamente se não houver resposta 

- 📋 Painel lateral 
 Passos do bloqueio e contatos de confiança cadastrados 
---

## 🗂️ Estrutura de Arquivos

```
anjoguardiao/
├── index.html   # Estrutura HTML da tela
├── style.css    # Identidade visual e estilos customizados
└── README.md    # Este arquivo
```

> ⚠️ O projeto utiliza **Tailwind CSS via CDN** — não é necessário instalar dependências. Basta abrir o `index.html` no navegador.

---

## 🎨 Identidade Visual

O sistema segue uma identidade visual consistente em todas as telas:

- **Paleta:** Navy escuro `#0d1b2a` · Teal `#1a9e8f` · Vermelho de alerta `#e63c3c` · Âmbar `#f0a500`
- **Tipografia:** `Space Grotesk` (títulos/display) + `Inter` (corpo e UI)
- **Padrão de borda:** `1px solid` em tons de navy para separação de seções
- **Botões:** Gradiente com elevação em hover e glow colorido por contexto
- **Badges de status:** Cor semântica — verde (seguro), vermelho (alerta), âmbar (pendente)
- **Sidebar:** Navegação fixa com item ativo destacado por borda esquerda em teal
---

## 📱 Responsividade

A interface é adaptada para diferentes tamanhos de tela usando os breakpoints do Tailwind CSS:
- **Mobile (`< md`):** layout em coluna, sidebar oculta, header simplificado no topo
- **Tablet/Desktop (`≥ md`):** sidebar visível, layout em duas colunas, espaçamento ampliado
---


## 🖥️ Tecnologias Utilizadas
- **HTML5**
- **CSS3**
- **Tailwind CSS (via CDN)**
- VS Code
- Google Fonts 


## 👩‍💻 Autora

**Jecika Saito** — RM 568787  
Análise e Desenvolvimento de Sistemas · FIAP  

---

## 📄 Licença

Projeto acadêmico desenvolvido para fins educacionais — FIAP 2026/2027
