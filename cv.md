## [rsschool-cv](https://artdinwin.github.io/rsschool-cv/)

# Toporov Artem

### graphic designer / front-end web developer (Beginner)

---

### Contact information

- **E-mail:** the-ghetto@yandex.ru
- **Telegram:** @pogbaibr
- **GitHub:** [ArtDinWin](https://github.com/ArtDinWin)
- **Discord:** [Artem Toporov (@ArtDinWin)#4615](https://discordapp.com/users/494963285205057563/)

---

### About me

I have 1.5 years experience in graphic design. I have a little experience in web development (websites, js scripts, web app, training projects). I am self-taught in JS programming. I am executive, punctual, responsible. I am willing to learn and develop new skills in front-end as web developer.

---

### Skills

- HTML
- CSS/SASS
- JavaScript (Basic)
- PHP (Basic)
- React framework (Basic)
- Git (Basic)
- Graphic design (Figma, Adobe Photoshop, CorelDRAW, Inkscape, Adobe Illustrator, Adobe InDesign)

---

### Code example

Function of deleting a task from the list by attribute. Test task for the interview: [ToDo list](https://github.com/ArtDinWin/test_todolist)

```function removeTask(e) {
  if (e.target.hasAttribute("data-action") && e.target.getAttribute("data-action") == "delete")
    {
    let taskName = e.target.parentElement.querySelector("div").innerText;
    if (confirm(`Удалить задачу: ${taskName}?`)) {
      e.target.parentNode.remove();
      let indexTask = tasks.findIndex((i) => i == taskName);
      tasks.splice(indexTask, 1);
      resaveStorage(tasks);
    }
  }
}
```

### Education

- University: Mari State Technological University, Faculty of Informatics and Computer Engineering
- Software Systems Institute, Designer's Tools course

### Courses / Intensives / Developer Experience

- Intensive - News Aggregator in js (22.03.2022 - 25.03.2022) MethEd Online School
- Intensive - Your own online cinema in js (7.12.2021 - 10.12.2021) MethEd Online School. [Training project](https://github.com/ArtDinWin/methed_cinema)
- JavaScript Developer Course 2021. Stream 11 (06.09.2021 - 29.10.2021) WebCademy Online School
- Test task for the interview: [ToDo list](https://github.com/ArtDinWin/test_todolist)

### Languages

- Russian - Native
- English - B1
