# Automação Alinhada ao Mercado Internacional  

---

## **Propósito e Motivações**  

Este projeto foi desenvolvido com o propósito de integrar, de forma inteligente e prática, o setor de compras ao site **Melhor Câmbio**. Meu papel como desenvolvedor é ser o ponto central dessa automação. Apesar de ser um exemplo funcional, o projeto tem grande potencial de escalabilidade, podendo ser expandido para realizar buscas em centenas de sites com resultados semelhantes. Essa ideia me motivou, e agora, vamos ao que interessa!  

---

## **Importações**  

As importações foram organizadas em duas categorias:  
- **Importações Essenciais**: Necessárias para o funcionamento da automação.  
- **Bibliotecas para Enviar E-mails**: Para envio automatizado de relatórios.  

> **Nota**:  
> Para usar o Selenium, fiz o download manual do driver diretamente no site oficial: [Selenium Downloads](https://www.selenium.dev/downloads/).  
> O arquivo para importar e modificar as credenciais está no diretório do projeto, com o nome **`credenciais.py`**.  

---

![image](https://github.com/user-attachments/assets/c510f7ca-3142-4b61-a85e-039381b60d82)  

---

## **Início do Web Scraping**  

Após configurar o navegador e carregar o arquivo que será referência para as buscas, ai comecei a extração do valor atual de mercado de cada item. Durante esse processo, limpo caracteres especiais antes de realizar cada busca, garantindo que o link dinâmico seja gerado corretamente para cada produto.  

---

![image](https://github.com/user-attachments/assets/e878ade3-405f-4cd5-83a1-e5b3d55d74d5)  

---

## **Lógica do Cenário de Compra**  

Para comparar os valores atuais com a base de referência, escolhi uma abordagem prática e eficiente utilizando a funcionalidade embutida do **Pandas** para comparação de colunas. Apesar de existirem métodos mais complexos que poderiam trazer insights adicionais, este se mostrou suficiente para destacar de forma clara se vale ou não realizar a compra.  

---

![image](https://github.com/user-attachments/assets/81aa08f6-4c4e-4071-b939-238b08470b67)  

---

## **Envio do E-mail**  

O envio de e-mails foi pensado para ser escalável, atendendo a qualquer número de produtos. Utilizei o formato padrão da biblioteca **`smtplib`** documentado em: [Documentação do SMTPLib](https://docs.python.org/3/library/smtplib.html).  

A tabela enviada no e-mail destaca, com cores (vermelho para "não" e verde para "sim"), os cenários de compra analisados.  

---

![image](https://github.com/user-attachments/assets/e4c1b471-d603-45c8-b707-5b5de49b6e72)  

---

Este foi um resumo geral do projeto, destacando apenas os pontos que considero mais importantes. Para uma compreensão mais detalhada, confira o projeto completo.
