<template>

  <div class="content">
      <form name="contact" action="/thankyou"  method="post" netlify>
        <input type="hidden" name="form-name" value="contact" />
        <p class="hidden">     
          <label>Don’t fill this out: <input name="bot-field"></label>   
        </p>
        <label class="form-label" for="name">
          Name:
        </label>
        <input class="form-field" name="name" id="name" />
        <label class="form-label" for="email">
          Email:
        </label>
        <input class="form-field" name="email" id="email" />
        <label class="form-label" for="message">
          Message:
        </label>
        
 <div data-netlify-recaptcha></div>
        <textarea class="form-field" name="message" id="message"></textarea>
        <input class="form-button" type="submit" value="Send message" />
      </form>
    </div>


</template>
  