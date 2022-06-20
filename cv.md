# Andrei Yurkouski

---

## Contacts:

* e-mail: andrey.yurkovsky@gmail.com

* telegram: emp74ark

* discord: emp74ark#5876



---

## About myself

More than ten years I had been working as a surgeon in Belarus. Computer technologies were always in the sphere of my interests and everyday life. I started learning web-development several months ago by myself. I've planned to use this knowledge to improve my local self-made patients database. Then I understood that my education needs better structure and started to learn JS/Frontend at Rolling Scopes.

New knowledge and circumstances made me change my plans again. From just a hobby learning web development turned into a professional goal.

It’s like when you obtain a driver license just to drive from home to work but some time later you find yourself making a big car journey, I realized that my journey in web development is just starting.

I haven't got any experience in real project development so far and understand that my skills in this field still need further enhancement, but I intend to keep on learning and practicing to do my best and finally become a skilled web-developer. 



---

## Education

- 2002:2009 Gomel State Medical University, Surgery;

- 2022 The Rolling Scopes, JavaScript/Front-end Course, stage 1;

- HTML, CSS, SQL at Sololearn



### Code example

This is one of my solutions on [Codewars](https://www.codewars.com/users/emp74ark):

```

var Cat = (function () {
  let allCats = [];
  return class Cat {
    constructor(name, weight){
      if(!name || !weight) throw Error();
      Object.defineProperty(this, "weight", {
        get: () => this._weight,
        set: (w) => (this._weight = w)
      })
      this.name = name;
      this.weight = weight;
      allCats.push(this);
    }
    static averageWeight(){
      return allCats.map(w => w.weight).reduce((a,b) => a+b, 0) / allCats.length;
    }
  }
 }());
```

---
## Language

- English B1