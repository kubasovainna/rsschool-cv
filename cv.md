# Inna Kubasova
Junior Frontend Developer
=========


### Contact information:
**E-mail:** [kubasovainna@mail.ru](mailto:kubasovainna@mail.ru)  
**Telegram** [@kubasovainna](https://tlgg.ru/kubasovainna)  
[Linkedin](https://www.linkedin.com/in/innakubasova/)  
[Upwork](https://www.upwork.com/freelancers/~019244f526e34b432d)


========


### Briefly About Myself:
ITMO university second year master student in web-technology department. My goal is to become a highly qualified competent front-end developer to make this world a better place, kinder people, and friendlier applications.  
In addition I am fond of UX\UI design, besides, I regularly work on various projects of different complexity in the field of UX/UI website development.


========

### Skills and Proficiency:
* HTML(HTML5), CSS(CSS3), Sass/SCSS, Bootstrap    
* JS, basic NodeJS, Express  
* Git, Heroku, basic Docker  
* Figma, Photoshop, Illustrator

=======

### Code example:
**Unique In Order from CODEWARS:** *Implement the function unique_in_order which takes as argument a sequence and returns a list of items without any elements with the same value next to each other and preserving the original order of elements.*  

````
var uniqueInOrder = function(iterable) {
  let arr =[];
  if (iterable.length != 0) arr.push(iterable[0]);
  for (let i =1; i<iterable.length; i++) {
    if (iterable[i]!==iterable[i-1]) arr.push(iterable[i]);
  }
  return arr;
}

````
