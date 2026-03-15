# 🏛️ TrataDoc v2.0 🚀

**Ferramenta Institucional de Processamento e Proteção de Dados em Documentos Digitais**

O **TrataDoc** é uma solução robusta desenvolvida para otimizar o fluxo de trabalho na **Corregedoria do Ministério do Planejamento e Orçamento (MPO)**. Ele combina Inteligência Artificial e Processamento de Linguagem Natural (NLP) para automatizar tarefas críticas de tratamento de documentos PDF.

---

## ✨ Funcionalidades Principais

* **🛡️ Anonimização via IA:** Identificação e tarjamento automático de nomes e dados sensíveis utilizando o modelo `spaCy` (pt_core_news_md).
* **👤 Borramento de Rostos:** Detecção automática de faces em imagens e PDFs para garantir a privacidade de terceiros.
* **🔍 OCR Integrado:** Reconhecimento óptico de caracteres para tornar PDFs digitalizados pesquisáveis (via Tesseract).
* **📂 Gestão de Arquivos:** Unificação (Merge) de múltiplos PDFs e compressão de arquivos.
* **💻 Operação 100% Offline:** Segurança máxima — nenhum documento sai da rede interna ou sobe para a nuvem.

---

## 🚀 Como Utilizar

### 🪟 Windows (Recomendado)
1. Baixe o instalador oficial (`Setup_TrataDoc_v9.exe`).
2. Siga as instruções do assistente de instalação.
3. Utilize o atalho criado na Área de Trabalho.

### 🍎 macOS
1. Baixe o artefato gerado pelo GitHub Actions.
2. Como o software é de uso interno, na primeira execução:
   - Clique com o **botão direito** no aplicativo.
   - Selecione **Abrir**.
   - Confirme a abertura na mensagem de segurança do sistema.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.10
* **Interface:** CustomTkinter (UI Moderna)
* **IA/NLP:** SpaCy & OpenCV
* **Manipulação de PDF:** PyMuPDF (fitz)
* **Build:** Inno Setup (Windows) & GitHub Actions (macOS)

---

## 👤 Desenvolvedor

**Anderson Guedes Francisco** *Analista Técnico Administrativo - Corregedoria/MPO* Engenheiro de Produção e Especialista em Liderança e Gestão de Pessoas.

---
> *Este projeto foi desenvolvido com foco em eficiência administrativa, transparência e proteção de dados sensíveis (LGPD) no setor público.*
