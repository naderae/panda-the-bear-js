1. var image = document.querySelector('.profile-image'); image.src = 'https://placebear.com/g/200/300'
2. var skyImage = document.querySelector('#left-image img');
3. var heading = document.querySelector('div h1'); heading.innerText = 'Nader'
4. var employment = document.querySelector('#employment h3'); employment.innerText = "Unemployment"
5. var body = document.querySelector('body'); body.style.backgroundColor = 'blue'
6. var highlight = document.querySelectorAll('.highlight');
   highlight.forEach(function(element){
     element.style.color = 'grey';
  });
7. var font = document.querySelector('h1');
   font.style.fontFamily = 'monospace';
8. var roundIcon = document.querySelectorAll('.action-icon-bg');
   roundIcon.forEach(function(element){
     element.style.backgroundColor = 'yellow';
    });
9. var n = document.querySelector("#name");
   n.placeholder = "identify yourself";

10. var message = document.querySelector('#message');
    message.placeholder = 'state your business';

11. var n = document.querySelector("#name");
    n.value = 'my nemesis';

12. var email = document.querySelector("#email");
    email.value = 'koalathebear@gmail.com';

13. var submit = document.querySelector("#submit");
    submit.value = 'En garde';

14. var submit = document.querySelector("#submit");
    submit.disabled = true

15. var info = document.querySelectorAll(".bio-info-value");
    info.forEach(function(infoPiece){
      infoPiece.innerText = null;
      });
