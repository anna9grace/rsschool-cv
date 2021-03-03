#My CV

1. ##Name / Surname
  Anna Rodionova

2. ##Contacts
  **Email**: anna9grace@gmail.com
  **Phone**: 8(965)098-63-84

3. ##Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении и способности быстро учиться и узнавать новое)

4. ##Skills:
  * HTML5, CSS3;
  * JavaScript;
  * Gulp, Webpack;
  * Figma;
  * Prepocessors: SCSS, Less;
  * adaptive layouts;

5. ##Code examples

  ```
    export default class Abstract {
      constructor() {
        if (new.target === Abstract) {
          throw new Error(`Can't instantiate Abstract, only concrete one`);
        }
        this._element = null;
        this._callback = {};
      }

      getTemplate() {
        throw new Error(`Abstract method not implemented: getTemplate`);
      }

      getElement() {
        if (!this._element) {
          this._element = createElement(this.getTemplate());
        }
        return this._element;
      }

      removeElement() {
        this._element = null;
      }
    }
  ```

6. ##Professional experience
  * **2014 - 2020**: worked as Accountor in several companies in Nizhny Novgorod and Saint-Peterburg
  * **2020**: created 3 web-pages as graduation projects of HTML Academy html/css-courses
  * **2020**: progammed 2 SPA as graduation projects of HTML Academy JS-courses
  * **2021 - to the current time**: create web-pages as part of HTML Academy "accelerator" programm (preparation to internship)

7. ##Education
  * **2009 - 2014**: Graduated Faculty of Economics of Nizhny Novgorod State University with specialization in accounting and audit.
  * **2020 - 2021**: Passed Frontend-development courses of HTML Academy.
  * **2021 - to the current time**: taking part in RS School JavaScript course

8. ##English
  *Level of language proficiency:* **B1-B2**
  In 2014 after University graduation participated in international volunteer programm in Germany (speaking language - English).
  In 2016 took part in Ecological School in Germany.
