<!-- Make a copy and remove comments -->
<!-- https://softwareontheroad.com/ideal-nodejs-project-structure/ -->
<!-- https://stackoverflow.com/questions/35807001/web-projects-folders-directories-structure-best-practices -->
<!-- https://stackoverflow.com/questions/51126472/how-to-organise-file-structure-of-backend-and-frontend-in-mern -->
frontend/
    libs/
        bootstrap/
    styleSheets/
        sass/
            _base.scss
            main.scss
            /components
                views/
                UI/
                    _button.scss
                    _chekbox.scss
                    _input.scss
                    _radiobutton.scss
                    _select.scss
                    _textarea.scss
        css/
            styles.css
    views/
        screens/
        components/
            navbar.html
            footer.html
    assets/
        fonts/
        images/
backend/
    App.js           <!-- App entry point -->
    api/             <!-- Express route controllers for all the endpoints of the app -->
    config/          <!-- Environment variables and configuration related stuff -->
    jobs/            <!-- Jobs definitions for agenda.js -->
    loaders/         <!-- Split the startup process into modules -->
    models/          <!-- Database models -->
    services/        <!-- All the business logic is here -->
    subscribers/     <!-- Event handlers for async task -->
    types/           <!-- Type declaration files (d.ts) for Typescript -->

<!-- 
npm package install global
nodemon
morganz

npm package install project
dotenv
 -->

mkdir frontend/ &&
mkdir frontend/libs/ &&
mkdir frontend/libs/bootstrap/ &&
mkdir frontend/styleSheets/ &&
mkdir frontend/styleSheets/sass/ &&
mkdir frontend/styleSheets/sass/components &&
mkdir frontend/styleSheets/sass/components/Views/ &&
mkdir frontend/styleSheets/sass/components/UI/ &&
mkdir frontend/styleSheets/css/ &&
mkdir frontend/views/ &&
mkdir frontend/views/screens/ &&
mkdir frontend/views/components/ &&
mkdir frontend/assets/ &&
mkdir frontend/assets/fonts/ &&
mkdir frontend/assets/images/ &&
mkdir backend/ &&
mkdir backend/api/ &&
mkdir backend/config/ &&
mkdir backend/jobs/ &&
mkdir backend/loaders/ &&
mkdir backend/models/ &&
mkdir backend/services/ &&
mkdir backend/subscribers/ &&
mkdir backend/types/

touch .env &&
touch frontend/styleSheets/sass/_base.scss &&
touch frontend/styleSheets/sass/main.scss &&
touch frontend/styleSheets/sass/components/UI/_button.scss &&
touch frontend/styleSheets/sass/components/UI/_chekbox.scss &&
touch frontend/styleSheets/sass/components/UI/_input.scss &&
touch frontend/styleSheets/sass/components/UI/_radiobutton.scss &&
touch frontend/styleSheets/sass/components/UI/_select.scss &&
touch frontend/styleSheets/sass/components/UI/_textarea.scss &&
touch frontend/styleSheets/css/style.css &&
touch frontend/views/components/navbar.html &&
touch frontend/views/components/footer.html &&
touch backend/App.js 
