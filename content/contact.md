---
date: "2018"
title: "Contact me"
---

If you have any questions that you want to ask me I'll be glad to respond. Just fill out the fields below along with the message to get in touch. 


{{< rawhtml >}}
<form name="contact" class="contact-form width-normal" action="/submission_sent/" method="POST" data-netlify="true">
    <br>
    <input type="hidden" name="form-name" value="contact" />
    <!-- Text input-->
    <div class="form-group row">
        <label class="col-md-4 control-label" for="Name"></label>
        <div class="col-md-4">
            <input id="contact-form-name" name="Name" type="text" placeholder="Name" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div class="form-group row">
        <label class="col-md-4 control-label" for="Email"></label>
        <div class="col-md-4">
            <input id="contact-form-email" name="Email" type="email" placeholder="Email Address" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div class="form-group row">
        <label class="col-md-4 control-label" for="Subject"></label>
        <div class="col-md-4">
            <input id="contact-form-subject" name="Subject" type="text" placeholder="Subject" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <!-- Textarea -->
    <div class="form-group custom-form-message-padding">
        <label class="col-md-4 control-label" for=""></label>
        <textarea class="form-control" id="contact-form-message" name="Message" placeholder="What's up?" rows="8"></textarea>
    </div>
    <!-- Button -->
    <div class="form-group row">
    <div class="col-sm-10">
      <button type="submit" class="btn btn-primary">Submit</button>
    </div>
  </div>
</form>
{{< /rawhtml >}}