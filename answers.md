<!-- Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead.
PROTIP: use the inspector to learn the dimensions of the current profile image and use a placeholder image service such as Place Bear to get an image of the same size. -->
document.querySelector('.profile-image').src = "https://placebear.com/400/400";

<!-- Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing. -->
document.querySelector('.portfolio-image img').src = "https://placebear.com/325/225";

<!-- Select the heading that says "Panda the Bear" and change it to your own name. -->
document.querySelector('section .highlight').innerText = "Cindy Chea";

<!-- Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector) -->
document.querySelector('#employment h3').innerText = "Experience";

<!-- Change the colour of the body. -->
document.querySelector('body').style.backgroundColor = '#db2b2b';

<!-- Change the colour of each element using the highlight class. Use a for loop to do this. -->
var highlights = document.querySelectorAll('.highlight');
for (i=0; i<highlights.length; i++) {
    highlights[i].style.backgroundColor = '#101e56'
}

<!-- Change the font family of the h1 to 'monospace'. -->
document.querySelector('h1').style.fontFamily = 'monospace';

<!-- Find a way to select the round icons in the sidebar and then change their colour. -->
var circles = document.querySelectorAll('.action-icon-container a');
circles.forEach(circle => circle.style.background = '#dc00ff');

<!-- Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself". -->
document.querySelector('form .contact-info').placeholder = 'identify yourself';

<!-- Change the placeholder attribute of the message field to "state your business". -->
document.querySelector('textarea').placeholder = 'state your business';

<!-- Give the name field a "value" attribute of "your nemesis". -->
document.querySelector('form .contact-info').value = 'your nemesis';
"your nemesis"

<!-- Change the value attribute of the email field to "koalathebear@gmail.com". -->
document.querySelectorAll('form .contact-info')[1].value = 'koalathebear@gmail.com';

<!-- Change the value of the submit button on the contact form to "En garde!". -->
document.querySelectorAll('form input')[2].value = 'En garde!';

<!-- We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute). -->
document.querySelectorAll('form input')[2].disabled = true;

<!-- We should help Panda protect their privacy by erasing their personal details from the sidebar. -->
document.querySelector('.bio-info').parentNode.removeChild(document.querySelector('.bio-info'));












