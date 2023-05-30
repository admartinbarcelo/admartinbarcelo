<p align="center">
  <img src="https://github.com/admartinbarcelo/admartinbarcelo/raw/main/cover-admartin.png" />
</p>

```js
import { SoftwareDeveloper } from '@Admartinbarcelo';

class AdrianMartin extends SoftwareDeveloper {
  constructor() {
    super();
    this.helloWorld();
    this.mySkills();
    this.currentlyLearning();
  }
  
  helloWorld() {
    console.log(`
      ¡Hola, mundo! Soy Adrian Martin, un desarrollador Full Stack ubicado en Barcelona, España.
      Si quieres saber más sobre mí, visita mi página web en: https://admartinbarcelo.netlify.app/
    `);
  }

  mySkills() {
    console.log(`
      Tengo experiencia en una variedad de tecnologías, incluyendo:

      Frontend: JavaScript, TypeScript, HTML, CSS, TailwindCSS, Bootstrap
      Backend: NodeJS, Express
      Bases de Datos: MongoDB
      Frameworks: React
      Herramientas: Git, GitHub, VS Code, npm, Webpack
    `);
  }

  currentlyLearning() {
    console.log(`
      Me encanta aprender y actualmente estoy trabajando en mejorar mis habilidades en Python y Django.
    `);
  }
}


```

```js
import { SoftwareDeveloper } from '@Admartinbarcelo';

class Developer extends SoftwareDeveloper {
  constructor() {
    super();
    this.name = 'Adrian Martin';
    this.title = 'Full Stack Developer';
    this.location = 'Barcelona, Spain';
    this.website = 'https://admartinbarcelo.netlify.app/';
    this.skills = {
      frontend: ['JavaScript', 'TypeScript', 'HTML', 'CSS', 'TailwindCSS', 'Bootstrap'],
      backend: ['NodeJS', 'Express'],
      databases: ['MongoDB'],
      frameworks: ['React'],
      tools: ['Git', 'GitHub', 'VS Code', 'npm', 'Webpack' ],
      currentlyLearning: ['Python', 'Django'],
    };
  }
}

```
