Hi there 👋 My name is Sarina 
==========================

Full Stack Software Engineer
----------------------------

Just like languages, designing is a form of communication. I am obsessed with the future me,\
who could "effortlessly" implement all kinds of designs she likes with code.\
[*React Docs - Empowering efficient and responsive user interfaces with JavaScript.*](https://react.dev/)\
[*MDN Web Docs - Your one-stop resource for web development.*](https://developer.mozilla.org/en-US/)\
[*Django Docs - The web framework for perfectionists with deadlines.*](https://docs.djangoproject.com/en/4.2/ref/settings/)

* 🖥️  See my portfolio at [*https://sarinawuphd.com*](http://sarinawuphd.com)
* 🧠  I'm learning React, JavaScript, AI, TailwindCSS, CI/CD, and various Cloud Platforms.
* 🧠  I thoroughly enjoyed dedicating my entire spring break last year to improving my Django skills.\
      Upon reviewing my Django projects, I find that I am still comfortable using them and have already deployed some of them.
* 🤝  I'm open to collaborating on AI Projects.

------------------------------------

### Technical Skills

|   |**Tools**                                                                                       |
|:---------------- |:------------------------------------------------------------------------------------------------------------------------- |
| *Frontend*       | JavaScript, TypeScript, React, React Native, Redux, Redux Toolkit, RTK Query, Next.js, Vite, HTML, CSS, Tailwind CSS, Bootstrap |
| *Backend*        | Python, Django, Node.js, Express.js, SQL, FastAPI, REST API, PostgreSQL, MongoDB, RabbitMQ, Postman, Insomnia, pgAdmin                        |
| *DevOps*         | Docker, Microservices, CI/CD, GitLab CI, GitHub Actions, Unit Testing, Heroku, Netlify, DigitalOcean, AWS, Hostinger       |
| *Documentation*  | Markdown                                                                                                          |

-------------------------------------

![my Tech Stack](https://res.cloudinary.com/practicaldev/image/fetch/s--ThRQXaMn--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_800/https://bezkoder.com/wp-content/uploads/2020/03/django-react-axios-rest-framework-crud-architecture.png)

------------------------------------
### 1/2 Compare TaskTales and ThriveTogether:
|     |       **TaskTales**           |         **ThriveTogether**                                                        |
|:--------------- |:------------------------------------------|:---------------------------------------------------------------- |
| *Backend Framework* | Django | FastAPI |
| *Containerization* | Virtual Environment | Docker |
| *Database* | SQLite | PostgreSQL |
| *Frontend* | HTML | React |
| *Authentication* | Built-In | Manual |

All five aspects seem simpler for the former (not saying Django is "easier" than FastAPI, just that I'm better at it at the moment 🙂);\
hence, when I set out to enhance my deployment skills, I decided to start with TaskTales. [*CI/CD - The Most Crucial DevOps Practice.*](https://www.simplilearn.com/tutorials/devops-tutorial/continuous-delivery-and-continuous-deployment)

*  Django App Deployment on Heroku actually is pretty straightforward if we follow [these steps](https://devcenter.heroku.com/articles/getting-started-with-python), although it simply doesn't work as it does locally...Troubleshooting is *tricky*.
*  OMG. I can't believe it...After 112 commits to the Repo (TaskTalesDeployment), it suddenly starts working as smoothly as in the local development mode (with zero console error on my end)...LOL. 🌸 [*My First Independently Deployed Django App on Heroku*](https://tasktales-e12d965b0fbc.herokuapp.com/) 🌸 [01/09/2024]
*  I'll focus on adding features and styling to this app in the future. :)
*  A mandatory pull request has been implemented on the main branch for *Branch Protection*.
  
-------------------------------------

### 2/2 Compare DealerDashboard and TaskTales:
|     |       **DealerDashboard**           |         **TaskTales**                                                        |
|:--------------- |:------------------------------------------|:---------------------------------------------------------------- |
| *Backend Framework* | Django | Django |
| *Database* | PostgreSQL | PostgreSQL |
| *Cloud Platform* | Heroku | Heroku |
| *Authentication* | Built-In | Built-In |
| *Containerization* | Docker | Virtual Environment |
| *Microservices* | Yes | No |
| *Polling* | Yes | No |
| *Frontend* | React | HTML |

I am excited about deploying this app because it shares similarities with TaskTales but exhibits greater complexity.
* Specifically, the incorporation of microservices, Docker, and polling, along with the React-based frontend, adds a layer of sophistication.
* Deploying an app from scratch presents a valuable opportunity to enhance my understanding of configurations.

[This is a helpful resource](https://dev.to/mdrhmn/deploying-react-django-app-using-heroku-2gfa). I wish I had discovered it when deploying my backend in the past two days. However, I managed to figure out the recommended practice on my own anyway. LOL. [*This one is worth reading too.*](https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react)

* We kept encountering CORS errors when deploying ThriveTogether, so I would go with the second option for this one.
* The Django-based server and PostgreSQL database are already up and running on Heroku.
* Now, I need to configure the React frontend to display in the browser.
* Just now realized that deployment could be harder than development. Netlify's UI is my favorite so far though, better than Heroku, DigitalOcean, Hostinger, AWS, Azure, etc. It would be perfect if I became good at it. [*Build Configs*](https://docs.netlify.com/configure-builds/overview/?_gl=1%2ap93753%2a_gcl_aw%2aR0NMLjE3MDU0MjAzMzEuQ2p3S0NBaUE3NWl0QmhBNkVpd0FraG85ZTN1ZTZ6a05qV3I2aFVCQVdRT1lFcnhhU1hGblJOTzdQS09vNGxPMnA1ZnR1M3VxaVJ5V0FCb0N5bEFRQXZEX0J3RQ..%2a_gcl_au%2aMTQ4NjI5NjQyMC4xNzA1NDIwMTc1) [*Dependencies*](https://docs.netlify.com/configure-builds/manage-dependencies/) [*Debugging*](https://answers.netlify.com/t/support-guide-failed-build-debugging-advice-preparing-the-best-help-request/73269?_gl=1*1fjzb8j*_gcl_aw*R0NMLjE3MDU0MjAzMzEuQ2p3S0NBaUE3NWl0QmhBNkVpd0FraG85ZTN1ZTZ6a05qV3I2aFVCQVdRT1lFcnhhU1hGblJOTzdQS09vNGxPMnA1ZnR1M3VxaVJ5V0FCb0N5bEFRQXZEX0J3RQ..*_gcl_au*MTQ4NjI5NjQyMC4xNzA1NDIwMTc1) (I wouldn't say I'm dumb. It's just *hard*.)
* 1/3 Backend is deployed on Heroku.\
  <img width="550" alt="1" src="https://github.com/wsrn829/wsrn829/assets/67284951/2eaa3f2e-2bb5-4b37-81b6-884745b4bb4b">
* 2/3 Frontend is deployed on Netlify.\
  <img width="550" alt="2" src="https://github.com/wsrn829/wsrn829/assets/67284951/f2990741-8174-45c3-8de7-6cdaf70f76f6">
* 3/3 I need to connect them and make them fully functioning...I'm so tired of debugging today. (Just learned about a position called 'DevOps Engineer.' Why am I doing this then? Because I was asked if I had experience during an interview last year.)
* Isn't it exciting to finally see something showing up in the browser? Although still a bunch of troubleshooting awaiting. Fun fact: I was asked to design a parking lot ticketing system (and a movie theater ticketing system) during another interview last year, and guess what? :p Anyway, below is my *Car Dealership App*.
  
| Image 1 | Image 2 |
| --------------- | ----------------------- |
|<img width="300" alt="111" src="https://github.com/wsrn829/wsrn829/assets/67284951/09a0634e-5623-404b-89b9-0793a5e3bf05">|<img width="300" alt="222" src="https://github.com/wsrn829/wsrn829/assets/67284951/a3a5e6e3-8ed4-4946-a8b1-d3bb7c53b5ea">|

* Setting up CI/CD (Continuous Integration/Continuous Deployment) for my projects has been really cool! The automated build and deployment process every time I push updates to my Git repository not only streamlines the development workflow but also enables the quick detection of errors as soon as a build fails. “The power of CI/CD lies in its ability to enhance efficiency, minimize manual interventions, and provide instant feedback, ultimately contributing to a more robust and agile software development lifecycle."
* Configuring CI/CD for full-stack apps, which includes setting up front-end and back-end deployment pipelines, managing database migrations, handling environment variables, and numerous debugging, has been quite a challenge. However, the rewarding outcomes make the entire effort absolutely worthwhile! 🌸
* Thankful for someone who said the part I wrote is better than the AI-generated one... LOL (I really appreciate that. 😊 )
* The CORS (Cross-Origin Resource Sharing) error turned out to be such a simple fix. Amazing.
* Look at my drawing for my team (using Excalidraw). This is the wireframe of the Car Dealership App. 

  <img width="800" alt="wireframe" src="https://github.com/wsrn829/wsrn829/assets/67284951/c7846198-e7a4-4496-99a7-b95523879e50">
  
* Just now thinking about why I didn't notice any difference when deploying an app with microservices. Then I found the inventory part (monolith) is working perfectly (both frontend and backend), but the microservices are having a 404 error. I assume Heroku is not detecting the microservices (just like what had happened with my frontend previously).
* [**Solution:**] Deploying microservices separately, in line with the principle of separation of concerns, should be able to resolve this issue. This is also the *essence* of microservices: being independent yet collaborative. :)
* After deploying my microservices in minutes, CI/CD is no longer a concern. I will focus on React and AI for future projects. (SalesForm getting an "invalid VIN" error, which should be from the code itself, probably from React components. Everything else is working. BTW, my backend is always bug-free so far as long as I use Django. LOL)
* This is my biggest confusion right now. I forgot to ask the instructors before graduation. TT
  
  <img width="500" alt="ai" src="https://github.com/wsrn829/wsrn829/assets/67284951/c722e36d-2e01-42c8-a31d-616a35c498be">

* I'm thrilled to incorporate [this link](https://dealerdashboard.netlify.app/) into my resume, even as the project continues to evolve. To date, this application integrates four remote GitHub repositories, three remote Heroku repositories, one remote Netlify repository, and three PostgreSQL databases on Heroku. I have a comprehensive understanding of its wireframe, backend and frontend code, database interactions via SQL commands from the terminal, and CI/CD processes. In essence, I am well-versed in all aspects of this application.
* This 2 AM message that left me speechless .. 

  <img width="300" alt="1" src="https://github.com/wsrn829/wsrn829/assets/67284951/ced03f5b-f2ab-4ab6-a8be-f50b88042874">

* I do need to add features, but at least this site is [live now](https://coin-crest.netlify.app/).

| Image 1 | Image 2 |
|---------------|----------------------- |
|<img width="450" alt="1" src="https://github.com/wsrn829/wsrn829/assets/67284951/06821b5d-05f1-410e-a6f5-322fb7d903f2">|<img width="450" alt="2" src="https://github.com/wsrn829/wsrn829/assets/67284951/79b57d25-8930-4f52-8b65-bdafaf338441">|



-------------------------------

### Continuing Education

| *Harvard CS50: Introduction to Computer Science*    | *Harvard CS50: Web Programming with Python and JavaScript*   |
|------------------------------------------------------|---------------------------------------------------------------|
| [ x ]  Week 0 - Scratch                              | [ - ]  HTML, CSS                                              |
| [ x ]  Week 1 - C                                    | [ - ]  Git                                                    |
| [ x ]  Week 2 - Arrays                               | [ - ]  Python                                                 |
| [ x ]  Week 3 - Algorithms                           | [ - ]  Django                                                 |
| [ x ]  Week 4 - Memory                               | [ - ]  SQL, Models, and Migrations                            |
| [ x ]  Week 5 - Data Structures                      | [ - ]  JavaScript                                             | 
| [ x ]  Week 6 - Python                               | [ - ]  User Interfaces                                        |
| [ - ]  Artificial Intelligence                       | [ - ]  Testing, CI/CD                                         |
| [ - ]  Week 7 - SQL                                  | [ - ]  Scalability and Security                               |
| [ - ]  Week 8 - HTML, CSS, JavaScript                |                                                               |  
| [ - ]  Week 9 - Flask                                |                                                               |
| [ - ]  Week 10 - Cybersecurity                       |                                                               |

-------------------------------------

### Socials

<p align="left"> 
  <a href="https://www.github.com/wsrn829" target="_blank" rel="noreferrer"> 
    <picture> 
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" /> 
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" /> 
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /> 
    </picture> 
  </a> 
  <a href="https://www.linkedin.com/in/wsrn829" target="_blank" rel="noreferrer"> 
    <picture> 
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin-dark.svg" /> 
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" /> 
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" /> 
    </picture> 
  </a>
</p>
