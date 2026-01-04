# 🎯 Apresentação Interativa - Estruturação Organizacional

Apresentação web interativa desenvolvida pela **STRAX360** para demonstração de serviços de estruturação organizacional e cargos & salários.

## 📋 Funcionalidades

### 🏢 Aba 1: Organograma Interativo
- ➕ Adicionar cargos/funções manualmente
- ✏️ Editar cargos existentes
- 📋 Copiar cargos (duplicar)
- 🗑️ Excluir cargos
- 📁 Importar estrutura via CSV
- 🔄 Carregar estrutura pré-configurada (Comtax)
- 💰 Cálculo automático de custos (mensal e anual)

### 💰 Aba 2: Simulador de Custos
- Simular impacto financeiro da estruturação
- Calcular custo de adequação salarial
- Estimar ROI (redução de turnover)
- Ajustar parâmetros em tempo real

### 📋 Aba 3: Fases do Projeto
- Comparação visual entre pacotes (Básico vs Completo)
- Detalhamento de 8 módulos de consultoria
- Tempo estimado e entregas de cada fase
- Módulos adicionais disponíveis

## 🚀 Como Usar

### Opção 1: Abrir Localmente
1. Baixe o arquivo `apresentacao_interativa_comtax.html`
2. Abra no navegador (Chrome, Edge, Firefox, Safari)
3. Pronto! Funciona 100% offline

### Opção 2: Deploy no GitHub Pages (Recomendado)

#### Passo a Passo:

1. **Criar repositório no GitHub:**
   - Acesse github.com e faça login
   - Clique em "New repository"
   - Nome: `apresentacao-comtax` (ou outro de sua escolha)
   - Marque "Public"
   - Clique em "Create repository"

2. **Upload do arquivo:**
   - Na página do repositório, clique em "Add file" → "Upload files"
   - Arraste o arquivo `apresentacao_interativa_comtax.html`
   - Clique em "Commit changes"

3. **Ativar GitHub Pages:**
   - Vá em "Settings" (no topo do repositório)
   - No menu lateral, clique em "Pages"
   - Em "Source", selecione "main" branch
   - Clique em "Save"
   - Aguarde 1-2 minutos

4. **Acessar a apresentação:**
   - URL: `https://seuusuario.github.io/apresentacao-comtax/apresentacao_interativa_comtax.html`
   - Compartilhe este link com clientes!

### Opção 3: Deploy na Vercel (Mais Profissional)

1. **Criar conta na Vercel:**
   - Acesse vercel.com
   - Faça login com GitHub

2. **Novo projeto:**
   - Clique em "Add New" → "Project"
   - Conecte seu repositório GitHub
   - Clique em "Deploy"

3. **Acessar:**
   - URL: `https://seu-projeto.vercel.app`
   - Link customizado e profissional!

## 📁 Importar CSV

### Formato do Arquivo CSV:
```
nome do cargo,area,quantidade de pessoas,valor por mes
```

### Exemplo (`exemplo_cargos.csv`):
```
Especialista Tributário,Consultoria,20,10000
Analista Especialista,Consultoria,15,7000
Gerente de Projetos,Projetos,5,15000
```

**Importante:**
- Sem cabeçalho (primeira linha já são dados)
- Separador: vírgula (,)
- Sem espaços extras
- Valores numéricos sem pontos ou vírgulas

## 🎨 Personalização

Para adaptar para outro cliente, edite no HTML:

1. **Título:** Linha 9
2. **Nome do cliente:** Linha 33
3. **Estrutura pré-carregada:** Função `loadComtaxDefault()` (linha ~340)

## 📱 Compatibilidade

- ✅ Chrome / Edge / Brave
- ✅ Firefox
- ✅ Safari
- ✅ Mobile (iOS / Android)
- ✅ 100% offline (não precisa internet)

## 🔧 Tecnologias

- HTML5
- CSS3 (Grid, Flexbox, Gradients)
- JavaScript Vanilla (sem dependências)
- Design Responsivo

## 📞 Suporte

Desenvolvido por **STRAX360 Consultoria**

Para dúvidas ou customizações:
- WhatsApp: (11) 99411-4499
- LinkedIn: [Paulo Henrique Pereira da Silva]

---

**Última atualização:** Janeiro 2025
