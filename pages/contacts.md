---
permalink: /contacts/
---

# Contactos

Para qualquer pedido de informação pode enviar diretamente um e-mail para <a href="mailto:urticariacronicaportugal@gmail.com">urticariacronicaportugal@gmail.com</a>, ou utilize o formulário abaixo:


<form method="post" action=”https://asofiafonso.github.io/apurtica/assets/formmail.php”  name="ContactForm">
<input type="hidden" name="env_report" value="REMOTE_HOST,REMOTE_ADDR,HTTP_USER_AGENT,AUTH_TYPE,REMOTE_USER" />
<input type="hidden" name="recipients" value="urticariacronicaportugal@gmail.com" />
<input type="hidden" name="required" value="ContactEmail:O seu e-mail,”ContactName”:O seu nome "/>
<input type="hidden" name="subject" value="Contacto Formulario" />
<input type="hidden" name="derive_fields" value="email=ContactEmail,realname=”ContactName”" />
<!-- <div class="form-column"> -->
    Nome: 
    <input type=”text” size=”19″ name=”ContactName” placeholder="O seu Nome">
    <br>
    <br>
    E-mail: 
    <input type=”text” size=”19″ name="ContactEmail" placeholder="O seu e-mail">
    <br>
    <br>
    Assunto: 
    <input type=”text” size=”19″ name="MessageTitle" placeholder="O assunto">
<!-- </div>
<div class="form-column"> -->
    Message:
    <br> 
    <textarea name="Message" rows=”30″ cols=”20″ placeholder="A sua mensagem">
    </textarea>
<!-- </div> -->
<div class="g-recaptcha" data-sitekey="6LfrFZ8cAAAAAP9SaqZdAfFMNQVw_U02hRabQYrf"></div>
<button type="submit">Enviar</button>
</form>


<!--js-->
<script src='https://www.google.com/recaptcha/api.js'></script>
