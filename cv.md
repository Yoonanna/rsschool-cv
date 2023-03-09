# ***Hanna Yanykova***

## **Contacts:**
### gmail: yanykovaanya@gmail.com 
### GitHub: Yoonanna
********* 


### Profile:
#### I am a student of "The Rolling Scopes School",
#### studying web development and I want to be a front-end developer.
#### Age: 24 yers
#### Country: Belarus

*********

### Skills:
* HTML
* CSS
* Basic JavaScript

********** 

### Language:
#### English (Pre-Intermediate level)
********** 
### Education:
#### "Belarusian State Medical University"
##### 2015-2021, Doctor
********** 
### Code:
```
"Nickname Generator"

function nicknameGenerator(name){
  let vowels = 'aeiou';
    let result;
    if (name.length < 4) {
        return "Error: Name too short";
    }
    else {
        let res = vowels.split('').some(el => el == name.charAt(2))
        if (res == true) {
            result = name.slice(0, 4)
        } else
            {result = name.slice(0, 3)}
    }
    return result
}
```
