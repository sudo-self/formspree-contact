# formspree-html
<img width="1440" alt="Screenshot 2023-09-16 at 7 29 27 AM" src="https://github.com/sudo-self/formspree-contact/assets/119916323/cf823d12-a294-454f-b86d-8124b17aaf0f">
<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/xyyqpwbg" method="post">
  <a href="/"><img id="banner" src="https://i.ibb.co/5sZ8VJ5/Screenshot-2023-09-16-at-6-43-34-AM.png" hieght="300px" width="500px"></a>
  <fieldset id="fs-frm-inputs">
    <label for="full-name" style="Color:rgb(76, 73, 73)">Full Name</label>
    <input type="text" name="name" id="full-name" placeholder="First and Last" required="">
    <label for="email-address" style="color:rgb(72, 69, 69)">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="johnsmith@1234gmail.com" required="">
    <label for="message" style="color:rgb(22, 21, 21)">Message</label>
    <textarea rows="5" name="message" id="message" placeholder="description of the issue and the exact error your encountering"></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
  </fieldset>
  <input type="submit" value="Submit">
</form>
