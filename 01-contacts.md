---
layout: page
title: Kontakt
permalink: /contacts/
long_title: Kontaktinformasjon
---
<div class="container">
<div class="row">
  <ul class="contact-list">
    <li>{{ site.description }}</li>
    <li>E-post: <a href="mailto:{{ site.email }}">{{ site.email }}</a></li>
    <li>Mobiltelefon: {{ site.phone }}</li>
    <li>Addresse: {{ site.address }}</li>
    <li>Organisasjonsnummer: <a href="http://w2.brreg.no/enhet/sok/detalj.jsp?orgnr={{ site.orgnumber }}">{{ site.orgnumber }}</a></li>
  </ul>
</div>
</div>

## Kontaktskjema

<div class="container">
  <div class="row">
    <form role="form" action="https://docs.google.com/forms/d/1KN1BQ1HWdrGHOZ0njf2K3WXvjQWT8EyiQwBKqHcTz6Q/formResponse?embedded=true" method="POST" target="_self" onsubmit="">
    <div class="col-lg-4">
      <div class="form-group required">
        <label for="InputName" class="control-label">E-post eller telefonnummer du kan nås på</label>
        <div class="input-group">
          <input type="text" class="form-control" name="entry.203897919" id="InputName" placeholder="Tast inn e-post eller telefonnummer" required>
          <span class="input-group-addon"></span></div>
      </div>
      <div class="form-group">
        <label for="InputMessage" class="control-label">Melding</label>
        <div class="input-group">
          <textarea name="entry.1247437116" id="InputMessage" class="form-control" rows="5" placeholder="Melding"></textarea>
          <span class="input-group-addon"></span></div>
      </div>
      <input type="submit" name="submit" id="submit" value="Send inn" class="btn btn-default pull-right">

        <input type="hidden" name="draftResponse"
            value="[,,&quot;7629806278334928560&quot;]">
        <input type="hidden" name="pageHistory" value="0">
        <input type="hidden" name="fbzx" value="7629806278334928560">
      </div>
    </form>
  </div>
</div>
