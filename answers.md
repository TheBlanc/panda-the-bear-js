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


PART 2

Removing Elements from the DOM
1.
timeTravelSkill = document.querySelectorAll('.bar-default')[2]
timeTravelSkill.remove()

Adding Elements to the DOM
1.
pikachuDiv = document.getElementById('right-image')
pikachu = pikachuDiv.firstElementChild
pikachuClone = pikachu.cloneNode()
portfolioContainer = document.querySelector('.portfolio-container')
portfolioContainer.appendChild(pikachuClone)

2.
for (var i = 0; i < 10; i++) {
pikachuClone = pikachu.cloneNode();
document.querySelector('.portfolio-container').appendChild(pikachuClone);
}

3.
var listItem = document.createElement('li');
var leftSpan = document.createElement('span');
var lastUpdatedOn = document.createTextNode('Page last updated on');
leftSpan.appendChild(lastUpdatedOn);
listItem.appendChild(leftSpan);

rightSpan = document.createElement('span');
lastUpdatedDate = new Date(2017, 08, 15, 14, 45, 20);
rightSpan.appendChild(lastUpdatedText);
listItem.appendChild(rightSpan);

bioItem = document.querySelector('.bio-info');
bioItem.appendChild(listItem);
