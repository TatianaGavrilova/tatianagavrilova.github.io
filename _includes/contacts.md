<div class="container">
<div class="row">
  <ul class="contact-list">
    <li>{{ site.title }}, {{ page.tutor_label }}</li>
    <li>{{ page.email_label }}:
        <a href="mailto:{{ site.email }}">{{ site.email }}</a></li>
    <li>{{ page.phone_label }}: {{ site.phone }}</li>
    <li>{{ page.address_label }}: {{ site.address }}</li>
    <li>{{ page.orgnumber_label }}: <a href="http://w2.brreg.no/enhet/sok/detalj.jsp?orgnr={{ site.orgnumber }}">{{ site.orgnumber }}</a></li>
  </ul>
</div>
</div>

## {{page.form_label}}

<div class="container">
  <div class="row">
    <form role="form" action="https://docs.google.com/forms/d/1KN1BQ1HWdrGHOZ0njf2K3WXvjQWT8EyiQwBKqHcTz6Q/formResponse?embedded=true" method="POST" target="_self" onsubmit="">
    <div class="col-xs-12 col-md-6">
        <div class="form-group required">
        <label for="InputName" class="control-label">{{ page.name_label }}</label>
        <div class="input-group">
          <input type="text" class="form-control" name="entry.1007638093" id="InputName" placeholder="{{ page.name_placeholder}}" required>
          <span class="input-group-addon"></span></div>
      </div>
      <div class="form-group required">
        <label for="InputName" class="control-label">{{ page.contact_label }}</label>
        <div class="input-group">
          <input type="text" class="form-control" name="entry.203897919" id="InputName" placeholder="{{ page.contact_placeholder}}" required>
          <span class="input-group-addon"></span></div>
      </div>
      <div class="form-group">
        <label for="InputMessage" class="control-label">{{ page.message_label }}</label>
        <div class="input-group">
          <textarea name="entry.1247437116" id="InputMessage" class="form-control" rows="5" placeholder="{{ page.message_placeholder }}"></textarea>
          <span class="input-group-addon"></span></div>
      </div>
      <input type="submit" name="submit" id="submit"
          value="{{ page.submit_label}} " class="btn btn-default pull-right">

        <input type="hidden" name="draftResponse"
            value="[,,&quot;7629806278334928560&quot;]">
        <input type="hidden" name="pageHistory" value="0">
        <input type="hidden" name="fbzx" value="7629806278334928560">
      </div>
    </form>
  </div>
</div>
