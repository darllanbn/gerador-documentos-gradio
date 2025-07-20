# 📄 Gerador de Documentos Word com Gradio (Google Colab)

Sistema completo para preenchimento automático de documentos administrativos em formato `.docx`, com interface moderna baseada em abas e execução prática via Google Colab. Ideal para gerar **advertências, termos, faturas e notificações internas** de forma padronizada, rápida e sem erro humano.

---

## 🎯 Objetivo

Automatizar o processo de preenchimento de documentos como:

- Advertência I
- Advertência II
- Termo de Eliminação COOP

Cada modelo é carregado e preenchido dinamicamente com os dados inseridos via interface Gradio, podendo conter **campos extras** como parcelas adicionais, valores e vencimentos.

---

## 🧪 Tecnologias utilizadas

- Python 3 (Google Colab)
- `gradio` – para criação da interface gráfica
- `python-docx` – para manipulação e geração dos arquivos Word
- Google Colab – execução na nuvem com upload/download interativos

---

## 🖥️ Funcionalidades

- Upload de modelos `.docx` personalizados
- Preenchimento de campos como nome, contrato, data, valor, vencimento etc.
- Campos extras opcionais para múltiplas linhas
- Interface visual com múltiplas abas: Advertência I, II, Termo
- Geração e download do documento final preenchido

---

## 🚀 Como usar

1. Abra o notebook no Google Colab
2. Faça upload dos arquivos `.docx` (Advertência I, II e Termo)
3. Use a interface para preencher os dados
4. Baixe o documento gerado

---

## 📸 Exemplo da Interface
<img width="1800" height="851" alt="image" src="https://github.com/user-attachments/assets/c73c53db-337c-4aff-aca4-4800223dcce2" />

 
---

## 📂 Estrutura esperada dos modelos `.docx`

Use **chaves como marcadores** no documento Word:

```
{{NOME}}, {{NºCONTRATO}}, {{EMAIL}}, {{DIA}}, {{MES}}, {{NÚMERO}}, {{VALOR}}, {{VENCIMENTO}}
```

Esses campos serão substituídos automaticamente. Campos extras (2 a 6) são adicionados em novas linhas da tabela, se fornecidos.

---

## 👨‍💻 Desenvolvedor

**Darllan Barba**  
📧 darllanbarba15@gmail.com  
🐱 [GitHub](https://github.com/darllanbn)

---

## 📄 Licença

Projeto desenvolvido como ferramenta de uso interno para geração rápida e padronizada de documentos administrativos. Uso livre para fins educacionais e organizacionais.
