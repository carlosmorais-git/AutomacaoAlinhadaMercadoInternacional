# Automacao Alinhada Mercado Internacional

---

**Proposito e Motivações**

Esse projeto foi pensado com o proposito de fazer uma integracao inteligem e pratica do setor de compras com o site melhor cambio e meu papel de desenvolvedor seria o pivo de tudo isso, me maneira ate que simples e digo o projeto tem sim possibilidades de escalar mais mostrei so o exemplo ate que funcional mas poderia ser uma busca de mil sites que teria o mesmo resultado. Entao dito o que me motivou vamos começar!

---

**Importações** 

Essa importações são classificadas em duas parte *Importacao importante* (para funcionamento) e *Bibliotecas para enviar email*, pontos para destacar para o uso do selenium usei o modo de baixar arquivo manual buscado no site oficial https://www.selenium.dev/downloads/ o arquivo para importacao das credenciais pode ser encontrado e modificado no diretorio do projeto nome 'credenciais.py'.

![image](https://github.com/user-attachments/assets/c510f7ca-3142-4b61-a85e-039381b60d82)

---

 **Inicio do Web Scraip**

 Apos criar o navegador e ler o arquivo que sera de referencia das futuras buscas, começo a extração do seu valor atual de mercado de cada item e sempre tomando cuidado em limpar os caracteres especiais antes de fazer cada busca pos a logica é criar um link dinamico passando cada produto a ele.
 
![image](https://github.com/user-attachments/assets/e878ade3-405f-4cd5-83a1-e5b3d55d74d5)

---

**Logica cenario de compra**

Para comprar o valor atual com o que ja tinha de base teria diverssas formas até mais complexas e que poderia me trazer novos insigth mas optei a comparacao de colunas do pandas mesmo pois ess metodo já vem embutido na biblioteca, ae agora fica destacado se vale ou nao a compra.

![image](https://github.com/user-attachments/assets/81aa08f6-4c4e-4071-b939-238b08470b67)

---

**Envio do email**

O pensameto desse envio foi pensada pra ser lembra escalavel pra quantos produtos for para isso o envio do email é padrao esse formato 
