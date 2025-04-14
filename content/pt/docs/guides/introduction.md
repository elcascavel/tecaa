---
title: "Introdução"
description: "O princípio da Compreensibilidade é o terceiro dos quatro princípios das Diretrizes de Acessibilidade para Conteúdo Web (WCAG)."
summary: "O princípio da compreensibilidade ajuda os desenvolvedores de websites a criar uma experiência mais acessível para todos os utilizadores, permitindo que qualquer pessoa, independentemente das suas capacidades, consiga compreender e utilizar o conteúdo digital."
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
weight: 1
toc: true
seo:
  title: "Introdução" # título personalizado (opcional)
  description: "O princípio da compreensibilidade ajuda os desenvolvedores de websites a criar uma experiência mais acessível para todos os utilizadores, permitindo que qualquer pessoa, independentemente das suas capacidades, consiga compreender e utilizar o conteúdo digital." # descrição personalizada (recomendado)
  canonical: "" # URL canónica personalizada (opcional)
  robots: "" # etiquetas de robôs personalizadas (opcional)
---

O princípio da **Compreensibilidade** é o terceiro dos quatro princípios das Diretrizes de Acessibilidade para Conteúdo Web (WCAG).  
Este princípio segue-se ao Conteúdo Web Claro e garante que o seu site tenha:<br>
**•	Texto Legível;**<br>
**•	Navegação Previsível;**<br>
**•	Apoio na Introdução de Dados.**<br><br>
<img src="/images/Introduction_Accessibility.png" alt="Explicação visual dos princípios WCAG com ícones e texto" width="344">
<img src="/images/Introduction_Accessibility_2.png" alt="Princípios da WCAG 2.0" width="344"><br>
- Fonte: Librarias da [Universidade de Indiana](https://blogs.libraries.indiana.edu/redux/2018/06/13/understanding-the-4-principles-of-accessibility/) & [Universidade de Minnesota](https://itss.d.umn.edu/articles/wcag-principles)

## 📝 Texto Legível 
O texto deve ser legível e compreensível, com **significados claros** para termos especiais ou técnicos.<br><br>
📌 **Mau Exemplo:**<br>
"Os utilizadores devem autenticar-se utilizando as suas credenciais designadas para aceder ao portal."<br><br>
✅ **Bom Exemplo:**<br>
"Inicie sessão com o seu nome de utilizador e palavra-passe para aceder à sua conta."<br><br>
### **Dicas Principais** para Texto Legível:<br>
•	Use **linguagem simples** (evite palavras complexas).<br>
•	Escreva **frases curtas** e **divida parágrafos longos**.<br>
•	Forneça **definições** para termos técnicos, se necessário.<br>

## 🔄 Navegação Previsível
Os websites devem ser construídos de forma consistente, para que os utilizadores saibam o que esperar.<br><br>
📌 **Mau Exemplo:**<br>
•	O menu muda de posição entre páginas.<br>
•	O botão "Submeter" muda para "Ir" noutra página.<br>
•	O ícone do carrinho de compras redireciona inesperadamente para a página inicial em vez da lista de produtos guardados para comprar.<br><br>
✅ **Bom Exemplo:**<br>
•	A barra de navegação mantém-se no mesmo local em todas as páginas.<br>
•	Os botões usam palavras consistentes (ex: o botão "Submeter", nunca muda para "Ir").<br>
•	A barra de pesquisa e o menu mantêm-se iguais em todas as páginas.<br><br>
### **Dicas Principais** para Navegação Previsível:<br>
•	Mantenha o menu, botões e layout **consistentes** em todas as páginas.<br>
•	Garanta que **links** e **botões** se comportam **como esperado** (ex: ícone do carrinho leva sempre ao carrinho).<br>
•	Evite **mudanças inesperadas** no design, na linguagem ou no comportamento da navegação.<br>

## 🛠️ Apoio na Introdução de Dados
Os formulários devem orientar os utilizadores, fornecendo instruções claras e mensagens úteis em caso de erro.<br><br>
📌 **Mau Exemplo:**<br>
•	Antes de submeter: O formulário não indica o formato que a palavra-passe deve ter.<br>
•	Depois de submeter: Em caso de erro, não aparece nenhuma mensagem, o que poderá deixar o utilizador confuso.<br><br>
✅ **Bom Exemplo:**<br>
•	Antes de submeter: O formulário mostra dois campos de palavra-passe com uma instrução clara:<br>
"Confirme a sua palavra-passe escrevendo-a novamente abaixo."<br>
•	Depois de submeter (se não coincidirem): O segundo campo é destacado com uma mensagem de erro:<br>
"As palavras-passe não coincidem. Por favor, tente novamente."<br><br>
### **Dicas Principais** para Apoio na Introdução de Dados:<br>
•	Forneça **instruções claras** antes da submissão (ex: requisitos da palavra-passe).<br>
•	Mostre **mensagens de erro específicas** quando houver erros.<br>
•	Utilize **pistas visuais** (como destacar o campo com erro).<br>
•	Evite mensagens genéricas como "Ocorreu um erro" — **explique sempre o que precisa de ser corrigido**.<br><br>
Em resumo, o princípio da compreensibilidade ajuda os desenvolvedores de websites a criar uma experiência mais acessível para o utilizador, permitindo que qualquer pessoa, independentemente das suas capacidades, compreenda e utilize o conteúdo digital.

-[Leia mais sobre o Princípio da Compreensibilidade no site do World Wide Web Consortium (W3C)](https://www.w3.org/WAI/WCAG22/quickref/?versions=2.2&showtechniques=312%2C315#principle3) 
