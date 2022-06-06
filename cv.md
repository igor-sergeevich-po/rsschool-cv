<a id= "up"></a>
[contacts](#contacts) | [about](#about) | [skills](#skills) | [education](#education) | [languages](#languages)
***
## Pochichenko Igor Sergeevich
![avatar_pic](/cv-avatar.jpg)
***
<a id="contacts"></a>
### *contacts info:*
  connection type|connection info|
:-:|---:|-----:
 phone number :| + 7 (951) 507 67 79
| email :| 89515076779@ya.ru|
| telegram :| [elScrooge](https://t.me/elScrooge)|
| skype| https://join.skype.com/invite/AiO2FFbjWr68|
| gitHub :| [igor-sergeevich-po](https://github.com/igor-sergeevich-po)|
[↑ up ↑](#up)
***
<a id= "about"></a>
### *about me:*
Hello, I am a web interface developer from Russia - Rostov-on-Don. My goal is to become a pro in this field. Perhaps today I do not have a rich resume and extensive knowledge, but this is temporary.
[↑ up ↑](#up)
***
<a id= "skills"></a>
### *base skills:*
- HTML
- CSS
- JavaScript
- git
- Visual Studio Code
- figma
- Photoshop
```
function duplicateEncode(word){
    let finelyResult = [];
    let resultCount = '';
    let result = word.toLowerCase().split('').reduce((acc, value) => {
        acc[value] ? acc[value] +=1 : acc[value] = 1;
        return acc;
    },{});
   word.toLowerCase().split('').forEach((item) => {
        for(key in result) {
            
            if(key == item && result[key] == 1) {
                resultCount+=result[key];
            } else if (key == item && result[key] > 1) {
                resultCount+= "2"
            }
        }
   })
   resultCount.split('').forEach((item)=> {
       if(item == 1) {
        finelyResult.push('(')
       }else if (item > 1) {
           finelyResult.push(')')
       }
   })
   return finelyResult.join('');
}
```
[↑ up ↑](#up)
***
<a id= "education"></a>
## *courses & education* :
* Moscow Technological Institute "VTU", Moscow : automation and management in commercial and administrative spheres - 2015
- HTML course - sololern : [
course completion certificate](https://www.sololearn.com/Certificate/1014-9727737/pdf/)
- CSS course - sololern : [
course completion certificate](https://www.sololearn.com/Certificate/1023-9727737/pdf/)
- Java Script :
   - sololearn : [course completion certificate](https://www.sololearn.com/certificates/course/en/9727737/1024/landscape/png)
   - stepik : [course completion certificate](https://stepik.org/cert/1346296)
   - udemy : [course completion certificate](https://udemy-certificate.s3.amazonaws.com/image/UC-b9ba6859-672f-4f83-9b0e-5e90cb1cb832.jpg?v=1640435180000)

[↑ up ↑](#up)
<a id= "languages"></a>
## *languages* :
- russian - main
- english - A2 (Pre-Intermediate)+

[↑ up ↑](#up)
***
