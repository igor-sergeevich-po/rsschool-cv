[contacts](#contacts) | [about](#about) | [skills](#skills)
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
***
<a id= "about"></a>
### *about me:*
Hello, I am a web interface developer from Russia - Rostov-on-Don. My goal is to become a pro in this field. Perhaps today I do not have a rich resume and extensive knowledge, but this is temporary.
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
***
