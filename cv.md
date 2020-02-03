# Resume

1. Viacheslav Miloserdov
2. Phone number: +7 964 980 48 51; E-mail: slavmiloserdov@mail.ru
3. In recent years, I have been actively involved in mathematics. Participated in conferences, wrote scientific articles and much more. But now I realized that I want to became a web developer. I really want to learn to create beautiful sites with great functionality. I can learn fast and now I study only JavaScript and learn English.
4. In university i used Java, Python, C, C++, C#, Pascal and SQL. Now i learn HTML, CSS, JavaScript and React.
5. These are my solutions for Codewars:

---

- Solution for [Digital Root][2]:

```js
function digital_root(n) {
  if (n / 10 < 1) {
    return n;
  }
  return digital_root(
    n
      .toString()
      .split("")
      .reduce((a, b) => +a + +b, 0)
  );
}
```

---

- Solution for [Number Of Occurrences][3]:

```js
Array.prototype.numberOfOccurrences = function() {
  return this.filter(a => a === arguments[0]).length;
};
```

---

6. Projects: [Avia Tickets][1],

7. Bachelor's degree in Applied Mathematics and Computer Science. I finished courses in Udemy.
8. Now my English level is low, but i study with coach.

[1]: https://github.com/SlavaMiloserdov/Avia-Tickets
[2]: https://www.codewars.com/kata/541c8630095125aba6000c00
[3]: https://www.codewars.com/kata/52829c5fe08baf7edc00122b
