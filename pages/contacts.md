---
permalink: /contacts/
---

# Contactos

Para qualquer pedido de informação pode enviar diretamente um e-mail para <a href="mailto:urticariacronicaportugal@gmail.com">urticariacronicaportugal@gmail.com</a>, ou utilize o formulário abaixo:


<form
  action="https://asofiafonso.github.io/apurtica/assets/formmail.php"
  method="POST"
>
<input type="hidden" name="env_report" value="REMOTE_HOST,REMOTE_ADDR,HTTP_USER_AGENT,AUTH_TYPE,REMOTE_USER" />
<input type="hidden" name="recipients" value="urticariacronicaportugal@gmail.com" />
<input type="hidden" name="required" value="ContactEmail:O seu e-mail,ContactName:O seu nome "/>
<input type="hidden" name="subject" value="Contacto Formulario" />
<input type="hidden" name="derive_fields" value="email=ContactEmail,realname=ContactName" />
<label class="required">
    Nome
<br>
    <input type="text" name="nome" size="75" placeholder="Nome..." required>
  </label>
<br>
 <label class="required">
    Morada:
<br>
    <input type="text" name="morada" size="75" placeholder="Rua..." required>
</label>
<br>
<br>
 <label class="required">
    Código Postal:
    <input type="text" name="postal" size="8" placeholder="NNNN-NNN" required>
</label>
 <label class="required">
    Localidade:
    <input type="text" name="city" size="30" placeholder="Localidade..." required>
</label>
<br>
<br>
<label class="required">
    E-mail:
    <input type="email" name="_replyto" size="30" placeholder="example@server.com" required>
  </label>
<label class="required">
    Telefone:
    <input type="number" name="phone" size="12" placeholder="NNNNNNNNN" required>
  </label>
<br>
<br>
 <label class="required">
    Núm. CC/BI:
    <input type="number" name="cc_id" size="10" placeholder="NNNNNNNNN" required>
</label>
 <label class="required">
    NIF:
    <input type="number" name="cc_id" size="10" placeholder="NNNNNNNNN" required>
</label>
 <label class="required">
    Data de Nascimento:
    <input type="date" name="cc_id" size="10" required>
</label>
<br>
<br>
 <label>
    Área(s) de interesse/contributo para a associação:
<br>
    <input type="text" name="contrib" size="75" placeholder="">
</label>
<br>
<br>
   <label class="required">Tem urticária crônica?</label>
<br>
      <input type="radio" id="yes_spt" name="disease" value="yes_sp" required>
      <label for="yes_spt">Sim, espontânea</label><br>
      <input type="radio" id="yes_ind" name="disease" value="yes_ind">
      <label for="yes_ind">Sim, induzida</label><br>
      <input type="radio" id="no_fam" name="disease" value="no_fam">
      <label for="no_fam">Não, mas sou familiar de doente</label><br>
      <input type="radio" id="no" name="disease" value="no">
      <label for="no">Não</label><br>
<br>
 <label>
    Em que ano foi diagnosticada a doença:
<br>
    <input type="number" name="year" size="75" placeholder="NNNN">
</label>
<br>
 <label>
    É acompanhado por especialidade médica:
<br>
    <input type="text" name="med_speciality" size="75" placeholder="Ex. imunoalergologia">
</label>
<br>
 <label>
    Como tomou conhecimento da APUrtica:
<br>
    <input type="text" name="know_how" size="75" placeholder="Ex. facebook, familiar">
</label>
<br>
<br>
<input type="checkbox" id="authorization" name="auth" value="authorization" required>
<label for="authorization"> Autorizo a recolha, registo, tratamento e conservação dos meus dados pessoais pela APUrtica, nos termos da legislação aplicável à proteção e privacidade de dados pessoais</label><br>
<br>
  <button type="submit">Aderir</button>
</form>


<!-- <form method="post" action=”https://formspree.io/f/xjvjlvdk”  name="ContactForm">
<input type="hidden" name="env_report" value="REMOTE_HOST,REMOTE_ADDR,HTTP_USER_AGENT,AUTH_TYPE,REMOTE_USER" />
<input type="hidden" name="recipients" value="urticariacronicaportugal@gmail.com" />
<input type="hidden" name="required" value="ContactEmail:O seu e-mail,”ContactName”:O seu nome "/>
<input type="hidden" name="subject" value="Contacto Formulario" />
<input type="hidden" name="derive_fields" value="email=ContactEmail,realname=”ContactName”" />
<div class="form-column">
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
</div>
<div class="form-column">
    Message:
    <br> 
    <textarea name="Message" rows=”30″ cols=”20″ placeholder="A sua mensagem">
    </textarea>
</div>
<div class="g-recaptcha" data-sitekey="6LfrFZ8cAAAAAP9SaqZdAfFMNQVw_U02hRabQYrf"></div>
<button type="submit">Enviar</button>
</form> -->


<!--js-->
<script src='https://www.google.com/recaptcha/api.js'></script>
