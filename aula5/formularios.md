# Resumo
> Nessa aula iremos ter uma visão geral á respeito de Formulários.

O elemento HTML `<form>` representa uma seção de um documento que contém controles interativos que permitem ao usuário submeter informação a um determinado servidor web.

**Web Docs, Mozilla**

Referência: [W3C](http://www.w3.org/wiki/HTML/Elements/input
)

```
  <form action="sendEmail.php" method="post" name="post">
    <label for="">Nome:</label>
    <input 
      id="name" 
      name="name" 
      type="text" 
      required>

    <label for="email">E-mail:</label>
    <input 
      id="email" 
      name="email" 
      type="email" 
      required>
    
    <label for="telephone">Telefone Fixo ou Celular:</label>
    <input 
      id="telephone" 
      name="telephone" 
      type="tel" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" 
      required>

    <label for="city">Cidade:</label>
    <input 
      id="city" 
      name="city" 
      type="text" 
      required>

    <label for="state">Estado:</label>
    <select name="state" required>
      <option value="SC">Santa Catarina - SC</option> 
      <option value="SP">São Paulo - SP</option>
      <option value="PR" selected>Paraná - PR</option>
    </select>

    <label for="message">Mensagem:</label>
    <textarea 
      id="message" 
      name="message" 
      required> 
    </textarea>

    <button 
      id="send" 
      name="send" 
      type="submit">Enviar
    </button>
```