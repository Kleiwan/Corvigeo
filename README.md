# Nobre Piscinas — Landing Page

Landing page institucional desenvolvida para a **Nobre Piscinas**, empresa especializada na fabricação e comercialização de piscinas de fibra de vidro. O projeto tem como objetivo apresentar a história da empresa, os modelos de piscinas oferecidos, capturar leads através de um formulário de orçamento e disponibilizar canais de contato.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da página.
- **Tailwind CSS (v3 via CDN):** Framework de estilização utilitária para layout responsivo e moderno.
- **DaisyUI (v4 via CDN):** Biblioteca de componentes para Tailwind CSS (utilizado em `navbar`, `hero`, `card`, `input`, `btn` e `footer`).

---

## 📌 Estrutura da Página

A landing page é composta pelas seguintes seções:

1. **Cabeçalho / Navbar:**
   - Logotipo da marca.
   - Links para redes sociais (WhatsApp e Instagram).
   - Navegação principal: *Sobre*, *Piscinas*, *Orçamentos*, *Garantia* e *Contatos*.

2. **Hero Section:**
   - Imagem de fundo promocional com overlay de contraste.
   - Título principal com destaque para a tradição e experiência da marca.
   - Chamadas para ação (CTAs): *"Conheça nossa história"* e *"Ver piscinas"*.

3. **Catálogo de Modelos (Piscinas):**
   - Apresentação em grid responsivo das linhas de produtos:
     - **Linha Princesa:** Compactas com degraus internos e bordas rebaixadas.
     - **Linha Condessa:** Modelos compactos e de fácil instalação.
     - **Linha Imperatriz:** Espaço amplo com escadas e banco lateral.
     - **Linha Duquesa:** Escadas de canto e banco interno.
     - **Linha Marquesa:** Amplo espaço interno e conforto para a família.
     - **Linha Viscondessa:** Design focado em conforto e profundidade.
   - Botão para download do catálogo em PDF.

4. **Formulário de Orçamento (Lead Generation):**
   - Formulário estilizado para captação de potenciais clientes com os campos: *Nome*, *Telefone*, *E-mail* e *Cidade/UF*.

5. **Rodapé (Footer):**
   - Resumo sobre a empresa.
   - Informações de contato telefônico e e-mail.
   - Endereço físico (Natal / RN).
   - Links para redes sociais e rodapé institucional.

---

## 📁 Estrutura de Pastas Recomendada

Para que as imagens e recursos funcionem corretamente, mantenha a seguinte organização de arquivos no repositório:

```text
.
├── index.html
├── img/
│   ├── logo.png
│   ├── wtsp.png
│   └── ig.png
└── assets/
    └── img/
        ├── princesa.png
        ├── condessa.png
        ├── Imperatriz.png
        ├── Duquesa.png
        ├── Marquesa.png
        ├── Viscondessa.png
        ├── Vector (1).png
        ├── instagram.svg
        ├── whatsapp.svg
        ├── logocima.svg
        └── logobaixo.svg
```

---

## 🚀 Como Executar o Projeto

1. Clone este repositório ou faça o download dos arquivos:
   ```bash
   git clone https://github.com/seu-usuario/nobre-piscinas.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd nobre-piscinas
   ```
3. Abra o arquivo `index.html` diretamente em qualquer navegador web ou utilize a extensão **Live Server** no VS Code para execução local.
