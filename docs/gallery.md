{% include navigation.md %}

# Griffin Gallery

[<img alt="A Pride of Griffins" src="Griffin image 1.jpg" height="96" width="96" />](Griffin_image_1.md)
[<img alt="A Perfect Griffin" src="Griffin image 2.jpg" height="96" width="96" />](Griffin_image_2.md)
[<img alt="A Confident Griffin" src="Griffin image 3.jpg" height="96" width="96" />](Griffin_image_3.md)
[<img alt="A Sad Griffin" src="Griffin image 4.jpg" height="96" width="96" />](Griffin_image_4.md)
[<img alt="A Giffin Serpentinis" src="Griffin image 5.jpg" height="96" width="96" />](Griffin_image_5.md)
[<img alt="A Cute Griffin" src="Griffin Image 6.png" height="96" width="96" />](Griffin_image_6.md)

# Submit your Favorite Griffin Photos

<form id="imagesubmit" method="POST" action="https://formspree.io/bwart@marketo.com">
  <input type="hidden" name="_subject" value="Griffin Image Submission" />
  <input type="hidden" name="_gotcha" style="display:none" />
  <input type="hidden" name="_next" value="https://bwart-mkto.github.io/scrum-team-griffin-site/thankyou" />
  <input type="hidden" name="_cc" value="sfabini@marketo.com,kbielewicz@marketo.com,mfenwick@marketo.com,talkhateeb@marketo.com" />
Email<br/><input type="email" name="email" placeholder="Your email" /><br/>
Caption<br/><input type="text" name="caption" placeholder="My Favorite Griffin" /><br/>
Image<br/><input type="text" name="image_url" placeholder="Link to Image" /><br/>
Or<br/><input type="hidden" role="uploadcare-uploader" name="griffen_image" /><br/>
  <button type="submit">Submit</button>
</form>
<script>
    var imagesubmit =  document.getElementById('imagesubmit');
    contactform.setAttribute('action', '//formspree.io/' + 'bwart' + '@' + 'marketo' + '.' + 'com');
</script>

{% include footer.md %}
