1.
var profilePic = document.querySelector('.profile-image')
profilePic.src = 'http://fillmurray.com/400/400'

1.2 photography = document.querySelector('.portfolio-image').firstElementChild
photography.src = 'https://www.fillmurray.com/325/325'

2.
mainHeader = document.querySelector('section').firstElementChild.firstElementChild
mainHeader.innerHTML = "Kevin The Bear"

3.
employmentDiv = document.querySelector('#employment')
employmentHeader = employmentDiv.firstElementChild
employmentHeader.innerHTML = "Steve No Jobs"

4.
body = document.querySelector('body')
body.style.background = '#12767d'

5.
highlight = document.querySelectorAll('.highlight')
highlight.forEach( function(element) { element.style.color = 'black'; } );

6.
mainHeader.style.fontFamily = 'monospace'

7.
roundIcons = document.querySelectorAll('.action-icon-bg')
roundIcons.forEach( function(element) { element.style.backgroundColor = 'orange' });

8.
nameForm = document.getElementById('name')
nameForm.placeholder = 'Kevin'

9.
messageForm = document.getElementById('message')
messageForm.placeholder = "Please don't feed Kevin The Bear"

10.
nameForm.value = 'Your nemasis'

11.
emailForm = document.getElementById('email')
emailForm.value = "koalathebear@gmail.com"

12.
submitForm = document.getElementById('submit')
submitForm.value = 'En garde!'

13.
submitForm.disabled = true

14.
bioInfo = document.querySelector('.bio-info')
bioInfo.remove()
