
# Mannam
This is a team project in order to set up a date for someone who wish to make a girlfriend or boyfriend. 

https://myfirstproject-1639b.firebaseapp.com/

or you can also use here till 3/24/2018
https://mannam.site/

![ezgif-3-46b1edece110](https://user-images.githubusercontent.com/25196026/51435289-c454de80-1cb7-11e9-9c1e-03320d077a93.gif)

Used set of skills
---
Back_end: Firsebase
Front_end: Javascript, CSS, HTML, Jquery, Bootstrap

Database rules
---

    {
      "rules": {
        "user": {
          "$time":{
            "major2vs2-6시-남자":{
              ".read":true,
              "$key":{
                ".write": "newData.hasChildren(['이름', '이름2', '입력된시간', '전화번호', '학과'])",
                "이름": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "이름2": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "입력된시간": {".validate": "newData.isString() && newData.val().length < 15 && newData.val().length > 5"},
                "전화번호": {".validate": "newData.isString() && newData.val().length < 14 && newData.val().length > 9"},
                "학과": {".validate": "newData.isString() && newData.val().length < 11 && newData.val().length > 3"}
              }
            },
    
            "major2vs2-6시-여자":{
              ".read":true,
              "$key":{
                ".write": "newData.hasChildren(['이름', '이름2', '입력된시간', '전화번호', '학과'])",
                "이름": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "이름2": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "입력된시간": {".validate": "newData.isString() && newData.val().length < 15 && newData.val().length > 5"},
                "전화번호": {".validate": "newData.isString() && newData.val().length < 14 && newData.val().length > 9"},
                "학과": {".validate": "newData.isString() && newData.val().length < 11 && newData.val().length > 3"}
              }
            },
    
            "major3vs3-7시-남자":{
              ".read":true,
              "$key":{
                ".write": "newData.hasChildren(['이름', '이름2', '이름3', '입력된시간', '전화번호', '학과'])",
                "이름": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "이름2": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "이름3": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "입력된시간": {".validate": "newData.isString() && newData.val().length < 15 && newData.val().length > 5"},
                "전화번호": {".validate": "newData.isString() && newData.val().length < 14 && newData.val().length > 9"},
                "학과": {".validate": "newData.isString() && newData.val().length < 11 && newData.val().length > 3"}
              }
            },
    
            "major3vs3-7시-여자":{
              ".read":true,
              "$key":{
                ".write": "newData.hasChildren(['이름', '이름2', '이름3', '입력된시간', '전화번호', '학과'])",
                "이름": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "이름2": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "이름3": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "입력된시간": {".validate": "newData.isString() && newData.val().length < 15 && newData.val().length > 5"},
                "전화번호": {".validate": "newData.isString() && newData.val().length < 14 && newData.val().length > 9"},
                "학과": {".validate": "newData.isString() && newData.val().length < 11 && newData.val().length > 3"}
              }
            },
    
            "sol-6시-남자":{
              ".read":true,
              "$key":{
                ".write": "newData.hasChildren(['학과', '이름', '입력된시간', '전화번호'])",
                "이름": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "입력된시간": {".validate": "newData.isString() && newData.val().length < 15 && newData.val().length > 5"},
                "전화번호": {".validate": "newData.isString() && newData.val().length < 14 && newData.val().length > 9"},
                "학과": {".validate": "newData.isString() && newData.val().length < 11 && newData.val().length > 3"}
              }
            },
    
            "sol-6시-여자":{
              ".read":true,
              "$key":{
                ".write": "newData.hasChildren(['학과', '이름', '입력된시간', '전화번호'])",
                "이름": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "입력된시간": {".validate": "newData.isString() && newData.val().length < 15  && newData.val().length > 5"},
                "전화번호": {".validate": "newData.isString() && newData.val().length < 14 && newData.val().length > 9"},
                "학과": {".validate": "newData.isString() && newData.val().length < 11 && newData.val().length > 3"}
              }
            },
    
            "sol-7시-남자":{
              ".read":true,
              "$key":{
                ".write": "newData.hasChildren(['학과', '이름', '입력된시간', '전화번호'])",
                "이름": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "입력된시간": {".validate": "newData.isString() && newData.val().length < 15  && newData.val().length > 5"},
                "전화번호": {".validate": "newData.isString() && newData.val().length < 14 && newData.val().length > 9"},
                "학과": {".validate": "newData.isString() && newData.val().length < 11 && newData.val().length > 3"}
              }
            },
    
            "sol-7시-여자":{
              ".read":true,
              "$key":{
                ".write": "newData.hasChildren(['학과', '이름', '입력된시간', '전화번호'])",
                "이름": {".validate": "newData.isString() && newData.val().length < 5 && newData.val().length > 1"},
                "입력된시간": {".validate": "newData.isString() && newData.val().length < 15  && newData.val().length > 5"},
                "전화번호": {".validate": "newData.isString() && newData.val().length < 14 && newData.val().length > 9"},
                "학과": {".validate": "newData.isString() && newData.val().length < 11 && newData.val().length > 3"}
              }
            }
          }
        }
      }
    }

---
Made with ❤️ for the people of the internet.
