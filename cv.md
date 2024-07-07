# Ivan Chernovalov
## React Developer
**Telegram:** @ivan_chernovalov  
**E-mail:** rulesprog@gmail.com  
### About me:
I teach adolescents programming remotely through zoom. I teach Frontend,Python, C++ (basically C, basics). This gives me extra free time, which I spend preparing to land a  full-time Frontend job. Now I am also preparing to enter the master’s program “Banking Information Technologies” - a joint master’s program of IKBFU and Sberbank with the support of MSU university. I like frontend because it deals with UI besides purely programming problems. I like Typescript because you can describe everything in great detail and everything you get to interact with is described in such a way. Since my childhood I've always been around computers and frontend. I created my first website at 8th grade. My goal is to participate in building great products that will bring benefit to users.

### Skills 
* React
* JavaScript HTML CSS
* Typescript TS
* Git Docker
* Python Django SQL C 
* IntelliJ (JetBrains) IDEs VSCode

### Code example

fonts.scss

```scss
$fws: (200, 300, 400, 500, 700, 800);
$ffs: ("woff2":'woff2', 'woff':'woff2', 'ttf':'truetype');
@each $fw in $fws {
  @font-face {
    font-family: "Eudoxus-Sans";
    $p: './Eudoxus-Sans/font/';
    $src: null;
    $i: 1;
    @each $fe, $ff in $ffs {
      $src: $src url("#{$p}variable.#{$fe}") format("#{$ff}-variations"),
      url("#{$p}#{$fw}.#{$fe}") format("#{$ff}")#{if($i !=3, ',', '')};
      $i: $i + 1;
    }
    src: $src;
    font-weight: #{$fw};
  }
}
```

### Experience.

1. Cuba-platform Application Development (Java, Postgres):
Developed an application using Cuba-platform, where the backend and frontend were both generated from Java code. Used VAADIN under the hood. Wrote technical specifications, managed a GitLab repository, and tracked issues in YouTrack.
2. Drupal (PHP, HTML, CSS) Project Enhancements: Made changes to an existing Drupal project.
3. Extended a resource consumption tracking project (e.g., hot water usage) using Laravel and integrated a PHP page displaying charts using google charts, PostgresSQL.
4. Playgendary JavaScript Developer (Cocos 2D):
Developed playable ads (mini-games within mobile ads) using JavaScript and Cocos 2D. Was interviewed for the position on basic JS knowledge but discovered that game development experience was crucial.
5. VK Internship (Web Development):
Explored backend, high-load concepts, and databases.
VK training/internship "Web development". Learned backend, highload, databases and why they invented KPHP. You could do anything, but it was assumed that you would make a telegram bot in PHP. I planned to create a fullstack project that lists applications/services and their disadvantages and advantages. But since I started with Go, which was completely new to me, and used GRAPHQL, which was completely new to me, I only managed to finish the backend.
6. Browser Extensions for DNS Store: I developed browser extensions that enhanced the DNS store website. Features included sorting mobile processors based on performance ratings, auto-loading more content, and sorting laptops by power (using performance data from various sources).
7. Sibdev Frontend Internship:
Enhanced existing dashboards, transitioning from Axios to fetchAPI.
8. Todolist Project (React):
Implemented a Todolist app for a client using React and Firebase.
It featured real-time updates, image handling, user registration, login, and password recovery.


### Education

2020 Bachelor's degree in Applied Mathematics and Computer Science,  Baltic Federal University. 
05/24/2024 Certificate of successful completion of the Beginner React Developer program (The authenticity of the certificate can be verified by writing to the official email hello@kts.tech with a request for confirmation)
10.10.2019 React - The Complete Guide Maximilian Schwarzmüller Udemy

### Languages
English C1 IELTS 7.0 Language practice: Mostly I consume all information in English; For a year, every Sunday I walked around the city and talked with foreigners (hash walks event)
Russian - Native