
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <meta name="description" content="">
    <meta name="google" content="notranslate">

      <script>
    window.dataLayer = window.dataLayer || [];
    dataLayer.push({"userId":20967,"visitorType":"student","batch":{"id":164,"fullNameWithC":"NBO-1123 (C#22)","schoolLocation":{"id":7,"name":"Nairobi"}},"curriculum":{"id":17,"name":"Short Specializations"}});

    window.gtm_user_custom_event = function (name, options) {
      if (typeof name === 'undefined') {
        return;
      }

      window.dataLayer.push({
        customEventOptions: typeof options !== 'undefined' ? options : {},
        event: name,
      });
    }
  </script>

  <!-- Google Tag Manager -->
  <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
  new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
  j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
  'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
  })(window,document,'script','dataLayer','GTM-N4C8MF2');</script>
  <!-- End Google Tag Manager -->


    <title>Project: 0x04. Typescript | Nairobi Intranet</title>

      <link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
      <link rel="stylesheet" media="all" href="/assets/application_alx-f0a62a714ef43c3f669c87b52d87de92b7b91cbdea68c47dee9fb68aea82ff62.css" />
      <script src="https://www.gstatic.com/charts/loader.js"></script>
      <script src="/assets/application-06e9a3ffafcb03d34c31475ffbd87ceb2261f0ec62464b93f7a96394b398ffa9.js"></script>
      <link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
      <meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="CDwV0JeiUPI1USFoNGkYnSC2bLkZ5NyEM_HvfESvWEd5Z7JxHVn7ReOB9CRqMdUNKWjbOIcx83c6Er78YHgpDw" />

      <link rel="apple-touch-icon" href="/apple-touch-icon_alx.png">

      <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
      <!--[if lt IE 9]>
        <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
        <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
      <![endif]-->

      <!-- Store user timezone -->
      <script>
        Cookies.set('timezone', (new Date()).getTimezoneOffset() / -60.0);
      </script>

      <!-- intro.js for interactive onboarding -->


      <!-- React -->
      <script src="/packs/js/application-e3c8526893bba4c3360e.js"></script>
      <link rel="stylesheet" media="screen" href="/packs/css/application-87456da7.css" />


  </head>

  <body class="signed_in env_production notranslate"
        translate="no"
        class="notranslate"
        data-theme-suffix="_alx">
      <!-- Google Tag Manager (noscript) -->
  <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-N4C8MF2"
  height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
  <!-- End Google Tag Manager (noscript) -->


      <div data-react-class="header/Header" data-react-props="{&quot;ehubHeaderSdkJsUrl&quot;:null,&quot;logoUrl&quot;:&quot;https://intranet.alxswe.com/assets/holberton-logo-full-alx-d053727941512ebe04b797ca87d81a195004e9ff2d8a6aedf4004c5365cf8944.png&quot;,&quot;discord&quot;:{&quot;label&quot;:&quot;Discord&quot;,&quot;targetUrl&quot;:&quot;https://discord.com/app&quot;,&quot;linkOpts&quot;:{&quot;target&quot;:&quot;_blank&quot;,&quot;rel&quot;:&quot;noreferrer&quot;}},&quot;user&quot;:{&quot;myProfileUrl&quot;:&quot;/users/my_profile&quot;,&quot;profilePictureUrl&quot;:&quot;https://intranet.alxswe.com/rails/active_storage/representations/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBM0NtQXc9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--f35470e67af7448578702c80daaae46cda5fe528/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaDdCem9MWm05eWJXRjBTU0lJYW5CbkJqb0dSVlE2RW5KbGMybDZaVjkwYjE5bWFYUmJCMmtCeUdrQnlBPT0iLCJleHAiOm51bGwsInB1ciI6InZhcmlhdGlvbiJ9fQ==--596ca5c9d0091ccfe5374ad3fb3471cc1878f984/262316877_699637327678017_4143005234748889252_n.jpg&quot;},&quot;listItems&quot;:[{&quot;label&quot;:&quot;My Planning&quot;,&quot;iconName&quot;:&quot;calendar&quot;,&quot;targetUrl&quot;:&quot;/planning/me&quot;},{&quot;label&quot;:&quot;Projects&quot;,&quot;iconName&quot;:&quot;code-fork&quot;,&quot;targetUrl&quot;:&quot;/projects/current&quot;,&quot;id&quot;:&quot;sidebar-current-projects-item&quot;},{&quot;label&quot;:&quot;QA Reviews I can make&quot;,&quot;iconName&quot;:&quot;check&quot;,&quot;targetUrl&quot;:&quot;/corrections/to_review&quot;},{&quot;label&quot;:&quot;Evaluation quizzes&quot;,&quot;iconName&quot;:&quot;question&quot;,&quot;targetUrl&quot;:&quot;/dashboards/my_current_evaluation_quizzes&quot;},{&quot;label&quot;:&quot;My resources&quot;},{&quot;label&quot;:&quot;Curriculums&quot;,&quot;iconName&quot;:&quot;graduation-cap&quot;,&quot;targetUrl&quot;:&quot;/dashboards/my_curriculums&quot;},{&quot;label&quot;:&quot;Concepts&quot;,&quot;iconName&quot;:&quot;file-text&quot;,&quot;targetUrl&quot;:&quot;/concepts&quot;,&quot;id&quot;:&quot;sidebar-concepts-item&quot;},{&quot;label&quot;:&quot;Conference rooms&quot;,&quot;iconName&quot;:&quot;comments&quot;,&quot;targetUrl&quot;:&quot;/dashboards/video_rooms&quot;,&quot;id&quot;:&quot;sidebar-dashboards-video-rooms&quot;},{&quot;label&quot;:&quot;Servers&quot;,&quot;iconName&quot;:&quot;server&quot;,&quot;targetUrl&quot;:&quot;/servers&quot;},{&quot;label&quot;:&quot;Sandboxes&quot;,&quot;iconName&quot;:&quot;terminal&quot;,&quot;targetUrl&quot;:&quot;/user_containers/current&quot;,&quot;id&quot;:&quot;sidebar-dashboards-my-containers&quot;},{&quot;label&quot;:&quot;Tools&quot;,&quot;iconName&quot;:&quot;wrench&quot;,&quot;targetUrl&quot;:&quot;/dashboards/my_tools&quot;},{&quot;label&quot;:&quot;Video on demand&quot;,&quot;iconName&quot;:&quot;film&quot;,&quot;targetUrl&quot;:&quot;/dashboards/videos&quot;},{&quot;label&quot;:&quot;My Campus&quot;},{&quot;label&quot;:&quot;Peers&quot;,&quot;iconName&quot;:&quot;users&quot;,&quot;targetUrl&quot;:&quot;/users/peers&quot;}]}" data-react-cache-id="header/Header-0"></div>

      <nav class="navbar navbar-default navbar-fixed-top topbar visible-xs">
  <div class="navbar-header">
    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-mobile" aria-expanded="false">
      <span class="sr-only">Toggle navigation</span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
    </button>

    <a class="navbar-brand" href="/">
      <div class="logo"></div>
</a>  </div>

  <div class="collapse navbar-collapse navigation" id="navbar-mobile">
    <ul class="nav navbar-nav">
      <li data-container="body" data-placement="right" data-toggle="tooltip" title="Home"><a href="/"><div class="icon "><i aria-hidden="true" class="fa-solid fa-home "></i></div><div class="visible-xs">Home</div></a></li>




    <li data-container="body" data-placement="right" data-toggle="tooltip" title="My Planning"><a href="/planning/me"><div class="icon "><i aria-hidden="true" class="fa-solid fa-calendar "></i></div><div class="visible-xs">My Planning</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-current-projects-item" title="Projects"><a href="/projects/current"><div class="icon "><i aria-hidden="true" class="fa-solid fa-code-fork "></i></div><div class="visible-xs">Projects</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="QA Reviews I can make"><a href="/corrections/to_review"><div class="icon "><i aria-hidden="true" class="fa-solid fa-check "></i></div><div class="visible-xs">QA Reviews I can make</div></a></li>
    
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="Evaluation quizzes"><a href="/dashboards/my_current_evaluation_quizzes"><div class="icon "><i aria-hidden="true" class="fa-solid fa-question "></i></div><div class="visible-xs">Evaluation quizzes</div></a></li>

    <hr title="My resources">

    <li data-container="body" data-placement="right" data-toggle="tooltip" title="Curriculums"><a href="/dashboards/my_curriculums"><div class="icon "><i aria-hidden="true" class="fa-solid fa-graduation-cap "></i></div><div class="visible-xs">Curriculums</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-concepts-item" title="Concepts"><a href="/concepts"><div class="icon "><i aria-hidden="true" class="fa-solid fa-file-text "></i></div><div class="visible-xs">Concepts</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-video-rooms" title="Conference rooms"><a href="/dashboards/video_rooms"><div class="icon "><i aria-hidden="true" class="fa-solid fa-comments "></i></div><div class="visible-xs">Conference rooms</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="Servers"><a href="/servers"><div class="icon "><i aria-hidden="true" class="fa-solid fa-server "></i></div><div class="visible-xs">Servers</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-my-containers" title="Sandboxes"><a href="/user_containers/current"><div class="icon "><i aria-hidden="true" class="fa-solid fa-terminal "></i></div><div class="visible-xs">Sandboxes</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="Tools"><a href="/dashboards/my_tools"><div class="icon "><i aria-hidden="true" class="fa-solid fa-wrench "></i></div><div class="visible-xs">Tools</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="Video on demand"><a href="/dashboards/videos"><div class="icon "><i aria-hidden="true" class="fa-solid fa-film "></i></div><div class="visible-xs">Video on demand</div></a></li>
    

      <hr title="My campus">

      
      <li data-container="body" data-placement="right" data-toggle="tooltip" title="Peers"><a href="/users/peers"><div class="icon "><i aria-hidden="true" class="fa-solid fa-users "></i></div><div class="visible-xs">Peers</div></a></li>
      


<hr class="visible-xs">

<li>
      <div
      data-container="body"
      data-placement="right"
      data-toggle="tooltip"
      title="Discord">
        <a rel="noreferrer" target="_blank" href="https://discord.com/app">
          <div class="icon discord">
            <i aria-hidden="true" class="fa-brands fa-discord "></i>
          </div>
          <div class="visible-xs">Discord</div>
</a>      </div>

  <div
    data-container="body"
    data-placement="right"
    data-toggle="tooltip"
    title="My Profile">
    <a href="/users/my_profile">
        <div class="image ">
          <div class="inner" style="background-image: url('https://intranet.alxswe.com/rails/active_storage/representations/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBM0NtQXc9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--f35470e67af7448578702c80daaae46cda5fe528/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaDdCem9MWm05eWJXRjBTU0lJYW5CbkJqb0dSVlE2RW5KbGMybDZaVjkwYjE5bWFYUmJCMmtCeUdrQnlBPT0iLCJleHAiOm51bGwsInB1ciI6InZhcmlhdGlvbiJ9fQ==--596ca5c9d0091ccfe5374ad3fb3471cc1878f984/262316877_699637327678017_4143005234748889252_n.jpg')"></div>
        </div>

      <div class="visible-xs">My Profile</div>
</a>  </div>
</li>


    </ul>
  </div>
</nav>


    <main class="content" id="content">
        

        <div id="layout-bars">
          
          <div class="px-5 py-3" id="student-switch-curriculum">
  <div class="dropdown d-flex flex-column gap-1">
    <span class="fs-small text-muted">Curriculum</span>

    <div aria-haspopup="true" aria-expanded="false" class="align-items-center d-flex gap-3" data-toggle="dropdown" id="student-switch-curriculum-dropdown" role="button">
      <div class="d-flex flex-column" style="line-height: 16px">
        <span class="fs-4 fw-600">
          Short Specializations
        </span>
        <span class="fs-small text-muted">
          Average: <span class="fw-500">161.45%</span>
        </span>
      </div>

      <div class="d-flex flex-column justify-content-center">
        <span style="margin-bottom: -4px">
          <i aria-hidden="true" class="fa-solid fa-angle-up  fa-fw"></i>
        </span>
        <span style="margin-top: -4px">
          <i aria-hidden="true" class="fa-solid fa-angle-down  fa-fw"></i>
        </span>
      </div>
    </div>

    <ul aria-labelledby="student-switch-curriculum-dropdown" class="dropdown-menu fs-5">
        <li>
          <a href="/curriculums/17/observe">
            <div class="align-items-center d-flex py-2">
              <div class="d-flex flex-column" style="line-height: 16px">
                <span class="fs-4 fw-500">
                  Short Specializations
                </span>
                <span class="text-muted">
                  Average: <span class="fw-500">161.45%</span>
                </span>
              </div>

                <span class="fw-600 text-info" style="margin-left: 42px">
                  <i aria-hidden="true" class="fa-solid fa-check "></i>
                </span>
            </div>
</a>        </li>
        <li>
          <a href="/curriculums/1/observe">
            <div class="align-items-center d-flex py-2">
              <div class="d-flex flex-column" style="line-height: 16px">
                <span class="fs-4 fw-500">
                  SE Foundations
                </span>
                <span class="text-muted">
                  Average: <span class="fw-500">117.91%</span>
                </span>
              </div>

            </div>
</a>        </li>
    </ul>
  </div>
</div>

          
          
          
        </div>

      <article class="">

        
  <div class="d-flex flex-wrap">

    <div class="flex-grow-1" id="curriculum_navigation_content">
      
<div class="project row">
  <div class="col-xs-12 col-lg-10 contains-images">

      <h1 class="gap">
    0x04. Typescript
    
  </h1>

  <div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:46,&quot;value&quot;:&quot;JavaScript&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;},{&quot;id&quot;:53,&quot;value&quot;:&quot;TypeScript&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

  <div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;requires_auto_correction&quot;:false,&quot;requires_manual_correction&quot;:true},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2024-10-09T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2024-10-10T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2024-10-12T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>




    


    <div id="project_id" style="display: none" data-project-id="1228"></div>



      

      

      <div class="panel panel-default" id="project-description">
  <div class="panel-body">
    <p><img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/12/baea85b5e9a9fb5c36ec.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20241009%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241009T170656Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e82d40aabb16b9b2ec88955e6637e255004efdbb90c6b3b7bec07164c240c7be" alt="" loading='lazy' style="" /></p>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/waTSa9Mguj912pel9On57w" title="TypeScript in 5 minutes" target="_blank">TypeScript in 5 minutes</a></li>
<li><a href="/rltoken/iPO8DlHCGzc1jnojLoP9HA" title="TypeScript documentation" target="_blank">TypeScript documentation</a></li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/PM-5MDItTT0M8Aaa2QIEyQ" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<ul>
<li>Basic types in Typescript</li>
<li>Interfaces, Classes, and functions</li>
<li>How to work with the DOM and Typescript</li>
<li>Generic types</li>
<li>How to use namespaces</li>
<li>How to merge declarations</li>
<li>How to use an ambient Namespace to import an external library</li>
<li>Basic nominal typing with Typescript</li>
</ul>

<h2>Requirements</h2>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code>, <code>Visual Studio Code</code></li>
<li>All your files should end with a new line</li>
<li>All your files will be transpiled on Ubuntu 18.04</li>
<li>Your TS scripts will be checked with <code>jest</code> (version 24.9.* )</li>
<li>A <code>README.md</code> file, at the root of the folder of the project, is mandatory</li>
<li>Your code should use the <code>ts</code> extension when possible</li>
<li>The Typescript compiler should not show any warning or error when compiling your code</li>
</ul>

<h2>Configuration Files</h2>

<p>Please use these files for the following tasks</p>

<h3><code>package.json</code></h3>

<details>
<summary>Click to show/hide file contents</summary>
<pre>
<code>
{
  "name": "typescript_dependencies",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "start-dev": "webpack-dev-server --open",
    "build": "webpack",
    "test": "jest"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "@babel/plugin-proposal-export-default-from": "^7.5.2",
    "@babel/preset-typescript": "^7.7.2",
    "@types/jest": "^24.0.23",
    "@typescript-eslint/eslint-plugin": "^2.4.0",
    "@typescript-eslint/parser": "^2.4.0",
    "clean-webpack-plugin": "^3.0.0",
    "fork-ts-checker-webpack-plugin": "^1.5.1",
    "html-webpack-plugin": "^3.2.0",
    "jest": "^24.9.0",
    "source-map": "^0.7.3",
    "ts-jest": "^24.1.0",
    "ts-loader": "^6.2.0",
    "typescript": "^3.6.4",
    "webpack": "^4.41.2",
    "webpack-cli": "^3.3.9",
    "webpack-dev-server": "^3.8.2"
  }
}
</code>
</pre>
</details>

<h3><code>.eslintrc.js</code></h3>

<details>
<summary>Click to show/hide file contents</summary>
<pre>
<code>
module.exports =  {
  parser:  '@typescript-eslint/parser',
  extends:  [
    'plugin:@typescript-eslint/recommended',  // Uses the recommended rules from @typescript-eslint/eslint-plugin
  ],
  parserOptions:  {
    ecmaVersion:  2018,
    sourceType:  'module',
  },
  rules:  {
  },
};
</code>
</pre>
</details>

<h3><code>tsconfig.json</code></h3>

<details>
<summary>Click to show/hide file contents</summary>
<pre>
<code>
{
  "compilerOptions": {
    "outDir": "./dist/",
    "sourceMap": true,
    "noImplicitAny": true,
    "module": "es6",
    "target": "es5",
    "allowJs": true,
    "moduleResolution": "node",
        "skipLibCheck": true
  }
}
</code>
</pre>
</details>

<h3><code>webpack.config.js</code></h3>

<details>
<summary>Click to show/hide file contents</summary>
<pre>
<code>
const path = require("path");
const HtmlWebpackPlugin = require('html-webpack-plugin');
const { CleanWebpackPlugin } = require('clean-webpack-plugin');
const ForkTsCheckerWebpackPlugin = require('fork-ts-checker-webpack-plugin');

module.exports = {
  entry: "./js/main.ts",
  devtool: "inline-source-map",
  module: {
    rules: [
      {
        test: /\.tsx?$/,
        loader: 'ts-loader',
        options: {
          transpileOnly: true
        }
      }
    ]
  },
  resolve: {
    extensions: [".tsx", ".ts", ".js"]
  },
  devServer: {
    contentBase: "./dist"
  },
  plugins: [
    new ForkTsCheckerWebpackPlugin(),
    new CleanWebpackPlugin(),
    new HtmlWebpackPlugin({
      title: "Development"
    })
  ],
  output: {
    filename: "bundle.js",
    path: path.resolve(__dirname, "dist")
  }
};
</code>
</pre>
</details>

  </div>
</div>


      

      

        
          <h2 class="gap">Tasks</h2>

    <div data-role="task11600" data-position="1" id="task-num-0">
      <div class="panel panel-default task-card " id="task-11600">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      0. Creating an interface for a student
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Copy the following configuration files (provided above) into the <code>task_0</code> directory: <code>package.json</code>, <code>.eslintrc.js</code>, <code>tsconfig.json</code>, <code>webpack.config.js</code></p>

<p>Write your code in the <code>main.ts</code> file:</p>

<ul>
<li>Write an interface named Student that accepts the following elements: <code>firstName(string)</code>, <code>lastName(string)</code>, <code>age(number)</code>, and <code>location(string)</code></li>
<li>Create two students, and create an array named <code>studentsList</code> containing the two variables</li>
<li>Using Vanilla Javascript, render a table and for each elements in the array, append a new row to the table</li>
<li>Each row should contain the first name of the student and the location</li>
</ul>

<p>Requirements:</p>

<ul>
<li>When running, Webpack should return <code>No type errors found</code>.</li>
<li>Every variable should use TypeScript when possible.</li>
</ul>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_0/js/main.ts, task_0/package.json, task_0/.eslintrc.js, task_0/tsconfig.json, task_0/webpack.config.js</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11600">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11600}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11601" data-position="2" id="task-num-1">
      <div class="panel panel-default task-card " id="task-11601">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      1. Let&#39;s build a Teacher interface
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create a directory <code>task_1</code> and copy these configuration files into this folder: <code>package.json</code>, <code>tsconfig.json</code>, <code>webpack.config.js</code></p>

<ul>
<li><code>firstName(string)</code> and <code>lastName(string)</code>. These two attributes should only be modifiable when a Teacher is first initialized</li>
<li><code>fullTimeEmployee(boolean)</code> this attribute should always be defined</li>
<li><code>yearsOfExperience(number)</code> this attribute is optional</li>
<li><code>location(string)</code> this attribute should always be defined</li>
<li>Add the possibility to add any attribute to the Object like <code>contract(boolean)</code> without specifying the name of the attribute</li>
</ul>

<p>Example:</p>

<pre><code>const teacher3: Teacher = {
  firstName: &#39;John&#39;,
  fullTimeEmployee: false,
  lastName: &#39;Doe&#39;,
  location: &#39;London&#39;,
  contract: false,
};

console.log(teacher3);

// should print
// Object
// contract: false
// firstName: &quot;John&quot;
// fullTimeEmployee: false
// lastName: &quot;Doe&quot;
// location: &quot;London&quot;
</code></pre>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_1/js/main.ts, task_1/webpack.config.js, task_1/tsconfig.json, task_1/package.json</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11601">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11602" data-position="3" id="task-num-2">
      <div class="panel panel-default task-card " id="task-11602">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      2. Extending the Teacher class
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write an interface named <code>Directors</code> that extends <code>Teacher</code>. It requires an attribute named <code>numberOfReports(number)</code></p>

<p>Example:</p>

<pre><code>const director1: Directors = {
  firstName: &#39;John&#39;,
  lastName: &#39;Doe&#39;,
  location: &#39;London&#39;,
  fullTimeEmployee: true,
  numberOfReports: 17,
};
console.log(director1);

// should print
// Object
// firstName: &quot;John&quot;
// fullTimeEmployee: true
// lastName: &quot;Doe&quot;
// location: &quot;London&quot;
// numberOfReports: 17
</code></pre>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_1/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11602">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11603" data-position="4" id="task-num-3">
      <div class="panel panel-default task-card " id="task-11603">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      3. Printing teachers
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write a function <code>printTeacher</code>:</p>

<ul>
<li>It accepts two arguments <code>firstName</code> and <code>lastName</code></li>
<li>It returns the first letter of the firstName and the full lastName</li>
<li>Example: <code>printTeacher(&quot;John&quot;, &quot;Doe&quot;) -&gt; J. Doe</code></li>
</ul>

<p>Write an interface for the function named <code>printTeacherFunction</code>.</p>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_1/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11603">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11604" data-position="5" id="task-num-4">
      <div class="panel panel-default task-card " id="task-11604">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      4. Writing a class
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write a Class named <code>StudentClass</code>:</p>

<ul>
<li>The constructor accepts <code>firstName(string)</code> and <code>lastName(string)</code> arguments</li>
<li>The class has a method named <code>workOnHomework</code> that return the string <code>Currently working</code></li>
<li>The class has a method named <code>displayName</code>. It returns the firstName of the student</li>
<li>The constructor of the class should be described through an Interface</li>
<li>The class should be described through an Interface</li>
</ul>

<p>Requirements:</p>

<ul>
<li>You can reuse the Webpack configuration from the previous exercise to compile the code.</li>
<li>When running <code>npm run build</code>, no TypeScript error should be displayed.</li>
<li>Every variable should use TypeScript when possible.</li>
</ul>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_1/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11604">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11605" data-position="6" id="task-num-5">
      <div class="panel panel-default task-card " id="task-11605">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      5. Advanced types Part 1
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create the <code>DirectorInterface</code> interface with the 3 expected methods:</p>

<ul>
<li><code>workFromHome()</code> returning a string</li>
<li><code>getCoffeeBreak()</code> returning a string</li>
<li><code>workDirectorTasks()</code> returning a string</li>
</ul>

<p>Create the <code>TeacherInterface</code> interface with the 3 expected methods:</p>

<ul>
<li><code>workFromHome()</code> returning a string</li>
<li><code>getCoffeeBreak()</code> returning a string</li>
<li><code>workTeacherTasks()</code> returning a string</li>
</ul>

<p>Create a class <code>Director</code> that will implement <code>DirectorInterface</code></p>

<ul>
<li><code>workFromHome</code> should return the string <code>Working from home</code></li>
<li><code>getToWork</code> should return the string <code>Getting a coffee break</code></li>
<li><code>workDirectorTasks</code> should return the string <code>Getting to director tasks</code></li>
</ul>

<p>Create a class <code>Teacher</code> that will implement <code>TeacherInterface</code></p>

<ul>
<li><code>workFromHome</code> should return the string <code>Cannot work from home</code></li>
<li><code>getCoffeeBreak</code> should return the string <code>Cannot have a break</code></li>
<li><code>workTeacherTasks</code> should return the string <code>Getting to work</code></li>
</ul>

<p>Create a function <code>createEmployee</code> with the following requirements:</p>

<ul>
<li>It can return either a <code>Director</code> or a <code>Teacher</code> instance</li>
<li>It accepts 1 arguments:

<ul>
<li><code>salary</code>(either number or string)</li>
</ul></li>
<li>if <code>salary</code> is a number and less than 500 - It should return a new <code>Teacher</code>. Otherwise it should return a <code>Director</code></li>
</ul>

<p>Expected result:</p>

<pre><code>console.log(createEmployee(200));
Teacher
console.log(createEmployee(1000));
Director
console.log(createEmployee(&#39;$500&#39;));
Director
</code></pre>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_2/js/main.ts, task_2/webpack.config.js, task_2/tsconfig.json, task_2/package.json</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11605">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11606" data-position="7" id="task-num-6">
      <div class="panel panel-default task-card " id="task-11606">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      6. Creating functions specific to employees
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write a function <code>isDirector</code>:</p>

<ul>
<li>it accepts <code>employee</code> as an argument</li>
<li>it will be used as a type predicate and if the employee is a director</li>
</ul>

<p>Write a function <code>executeWork</code>:</p>

<ul>
<li>it accepts <code>employee</code> as an argument</li>
<li>if the employee is a Director, it will call <code>workDirectorTasks</code></li>
<li>if the employee is a Teacher, it will call <code>workTeacherTasks</code></li>
</ul>

<p>Expected result:</p>

<pre><code>executeWork(createEmployee(200));
Getting to work
executeWork(createEmployee(1000));
Getting to director tasks
</code></pre>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_2/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11606">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11607" data-position="8" id="task-num-7">
      <div class="panel panel-default task-card " id="task-11607">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      7. String literal types
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write a String literal type named <code>Subjects</code> allowing a variable to have the value <code>Math</code> or <code>History</code> only.
Write a function named <code>teachClass</code>:</p>

<ul>
<li>it takes <code>todayClass</code> as an argument</li>
<li>it will return the string <code>Teaching Math</code> if <code>todayClass</code> is <code>Math</code></li>
<li>it will return the string <code>Teaching History</code> if <code>todayClass</code> is <code>History</code></li>
</ul>

<p>Expected result:</p>

<pre><code>teachClass(&#39;Math&#39;);
Teaching Math
teachClass(&#39;History&#39;);
Teaching History
</code></pre>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_2/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11607">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>



    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11607}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11608" data-position="9" id="task-num-8">
      <div class="panel panel-default task-card " id="task-11608">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      8. Ambient Namespaces
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create a directory called <code>task_3</code> and copy these configuration files into it: <code>package.json</code>, <code>webpack.config.js</code>, <code>tsconfig.json</code>.</p>

<p>The first part of will require that you build an <code>interface</code> and a <code>type</code>. Inside a file named <code>interface.ts</code>:</p>

<ul>
<li>Create a type <code>RowID</code> and set it equal to <code>number</code></li>
<li>Create an interface <code>RowElement</code> that contains these 3 fields:

<ul>
<li><code>firstName</code>: <code>string</code></li>
<li><code>lastName</code>: <code>string</code></li>
<li><code>age?</code>: <code>number</code></li>
</ul></li>
</ul>

<p>You are building the next part of the application architecture. The goal is to save the entities to a database.
Because of time constraints, you can&rsquo;t write a connector to the database, and you decided to download a library called <code>crud.js</code>. Copy this file into the <code>task_3/js</code> directory.</p>

<p>Here it is</p>

<pre><code>export function insertRow(row) {
  console.log(&#39;Insert row&#39;, row);
  return Math.floor(Math.random() * Math.floor(1000));
}

export function deleteRow(rowId) {
  console.log(&#39;Delete row id&#39;, rowId);
  return;
}

export function updateRow(rowId, row) {
  console.log(`Update row ${rowId}`, row);

  return rowId;
}
</code></pre>

<p>Write an ambient file within <code>task_3/js</code>, named <code>crud.d.ts</code> containing the type declarations for each crud function. At the top of the file import <code>RowID</code> and <code>RowElement</code> from <code>interface.ts</code>.</p>

<p>In <code>main.ts</code></p>

<ul>
<li>At the top of the file create a <a href="/rltoken/91U8IZgcc9cmk216FFy0-Q" title="triple slash directive" target="_blank">triple slash directive</a> that includes all the dependencies from <code>crud.d.ts</code></li>
<li>Import the <code>rowID</code> type and <code>rowElement</code> from <code>interface.ts</code></li>
<li>Import everything from <code>crud.js</code> as <code>CRUD</code></li>
</ul>

<p>Create an object called <code>row</code> with the type <code>RowElement</code> with the fields set to these values:</p>

<ul>
<li><code>firstName</code>: <code>Guillaume</code></li>
<li><code>lastName</code>: <code>Salva</code></li>
</ul>

<p>Create a <code>const</code> variable named <code>newRowID</code> with the type <code>RowID</code> and assign the value the <code>insertRow</code>  command.</p>

<p>Next, create a <code>const</code> variable named <code>updatedRow</code> with the type <code>RowElement</code> and update <code>row</code> with an age field set to <code>23</code></p>

<p>Finally, call the <code>updateRow</code> and <code>deleteRow</code> commands.</p>

<p>Expected result:</p>

<pre><code>const obj = {firstName: &quot;Guillaume&quot;, lastName: &quot;Salva&quot;};
CRUD.insertRow(obj)
// Insert row {firstName: &quot;Guillaume&quot;, lastName: &quot;Salva&quot;}

const updatedRow: RowElement = { firstName: &quot;Guillaume&quot;, lastName: &quot;Salva&quot;, age: 23 };
CRUD.updateRow(newRowID, updatedRow);
// Update row 125 {firstName: &quot;Guillaume&quot;, lastName: &quot;Salva&quot;, age: 23}

CRUD.deleteRow(125);
// Delete row id 125
</code></pre>

<p>Requirements:</p>

<ul>
<li>When running <code>npm run build</code>, no TypeScript error should be displayed.</li>
<li>Every variable should use TypeScript when possible.</li>
<li>The main file and the ambient file should both import the types defined in the interface file.</li>
<li>You can easily test your ambient file by looking at the intellisense of your IDE when using the 3rd party functions.</li>
</ul>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_3/js/main.ts, task_3/js/interface.ts, task_3/js/crud.d.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11608">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11609" data-position="10" id="task-num-9">
      <div class="panel panel-default task-card " id="task-11609">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      9. Namespace &amp; Declaration merging
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create a new directory <code>task_4</code> and copy the above <code>tsconfig.json</code> and put this <code>package.json</code> in there</p>

<pre><code>{
  &quot;name&quot;: &quot;task_4&quot;,
  &quot;version&quot;: &quot;1.0.0&quot;,
  &quot;description&quot;: &quot;&quot;,
  &quot;main&quot;: &quot;index.js&quot;,
  &quot;scripts&quot;: {
    &quot;build&quot;: &quot;webpack&quot;,
    &quot;test&quot;: &quot;echo \&quot;Error: no test specified\&quot; &amp;&amp; exit 1&quot;
  },
  &quot;keywords&quot;: [],
  &quot;author&quot;: &quot;&quot;,
  &quot;license&quot;: &quot;ISC&quot;,
  &quot;devDependencies&quot;: {
    &quot;@typescript-eslint/eslint-plugin&quot;: &quot;^2.4.0&quot;,
    &quot;@typescript-eslint/parser&quot;: &quot;^2.4.0&quot;,
    &quot;clean-webpack-plugin&quot;: &quot;^3.0.0&quot;,
    &quot;fork-ts-checker-webpack-plugin&quot;: &quot;^1.5.1&quot;,
    &quot;html-webpack-plugin&quot;: &quot;^3.2.0&quot;,
    &quot;ts-loader&quot;: &quot;^6.2.0&quot;,
    &quot;typescript&quot;: &quot;^3.6.4&quot;,
    &quot;webpack&quot;: &quot;^4.41.2&quot;,
    &quot;webpack-cli&quot;: &quot;^3.3.9&quot;,
    &quot;webpack-dev-server&quot;: &quot;^3.8.2&quot;
  }
}
</code></pre>

<p>In <code>task_4/js/subjects</code>:</p>

<ul>
<li><p>Create a file <code>Teacher.ts</code> and write a <code>Teacher</code> interface in a namespace named <code>Subjects</code>.</p>

<ul>
<li>the interface requires <code>firstName</code> and <code>lastName</code> as string</li>
</ul></li>
<li><p>Create a file <code>Subject.ts</code> and write a <code>Subject</code> class in the same namespace named <code>Subjects</code>.</p>

<ul>
<li>the class has one attribute <code>teacher</code> that implements the <code>Teacher</code> interface</li>
<li>the class has one setter method <code>setTeacher</code> that accepts a <code>teacher</code> in argument (and as setter, set the instance attribute <code>teacher</code> with it)</li>
</ul></li>
<li><p>Create a file <code>Cpp.ts</code> and make the following modifications in the same namespace.</p>

<ul>
<li>Using declaration merging, add a new optional attribute <code>experienceTeachingC</code> (number) to the <code>Teacher</code> interface</li>
<li>Create a class <code>Cpp</code> extending from <code>Subject</code></li>
<li>Write a method named <code>getRequirements</code> that will return a string <code>Here is the list of requirements for Cpp</code></li>
<li>Write a method named <code>getAvailableTeacher</code> that will return a string <code>Available Teacher: &lt;first name of teacher&gt;</code> </li>
<li>If the teacher doesn&rsquo;t have any experience in teaching C, then the method should return a string <code>No available teacher</code></li>
</ul></li>
<li><p>Create a file <code>React.ts</code> and write a <code>React Class</code> in the same namespace.</p>

<ul>
<li>Add a new attribute <code>experienceTeachingReact?</code> (number) to the <code>Teacher</code> interface</li>
<li>In the class, write a method named <code>getRequirements</code> that will return a string <code>Here is the list of requirements for React</code></li>
<li>Write a method named <code>getAvailableTeacher</code> that will return a string <code>Available Teacher: &lt;first name of teacher&gt;</code> </li>
<li>If the teacher doesn&rsquo;t have any experience in teaching React, then the method should return a string <code>No available teacher</code></li>
</ul></li>
<li><p>Create a file <code>Java.ts</code> and write a <code>Java Class</code> in the same namespace.</p>

<ul>
<li>Add a new attribute <code>experienceTeachingJava?</code> (number) to the <code>Teacher</code> interface</li>
<li>In the class, write a method named <code>getRequirements</code> that will return a string <code>Here is the list of requirements for Java</code></li>
<li>Write a method named <code>getAvailableTeacher</code> that will return a string <code>Available Teacher: &lt;first name of teacher&gt;</code> </li>
<li>If the teacher doesn&rsquo;t have any experience in teaching Java, then the method should return a string <code>No available teacher</code></li>
</ul></li>
</ul>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_4/package.json, task_4/tsconfig.json, task_4/js/subjects/Cpp.ts, task_4/js/subjects/Java.ts, task_4/js/subjects/React.ts, task_4/js/subjects/Subject.ts, task_4/js/subjects/Teacher.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11609">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11610" data-position="11" id="task-num-10">
      <div class="panel panel-default task-card " id="task-11610">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      10. Update task_4/js/main.ts
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <ul>
<li>create and export a constant <code>cpp</code> for Cpp Subjects</li>
<li>create and export a constant <code>java</code> for Java Subjects</li>
<li>create and export a constant <code>react</code> for React Subjects</li>
<li>create and export one Teacher object <code>cTeacher</code> with <code>experienceTeachingC = 10</code></li>
<li>for Cpp subject, log to the console <code>C++</code>, set <code>cTeacher</code> as the teacher, call the two methods <code>getRequirements</code> and <code>getAvailableTeacher</code> and print the strings they return</li>
<li>for Java subject, log to the console <code>Java</code>, set <code>cTeacher</code> as the teacher, call the two methods <code>getRequirements</code> and <code>getAvailableTeacher</code>, and print the strings they return</li>
<li>for React subject, log to the console <code>React</code>, set <code>cTeacher</code> as the teacher, call the two methods <code>getRequirements</code> and <code>getAvailableTeacher</code>, and print the strings they return</li>
</ul>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_4/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11610">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11611" data-position="12" id="task-num-11">
      <div class="panel panel-default task-card " id="task-11611">
  <span id="user_id" data-id="20967"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      11. Brand convention &amp; Nominal typing
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="20967"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create a directory <code>task_5</code> and copy these configuration files into the root of <code>task_5</code>: <code>package.json</code>, <code>tsconfig.json</code>, <code>webpack.config.js</code></p>

<p>Create two interfaces <code>MajorCredits</code> and <code>MinorCredits</code> in <code>task_5/js/main.ts</code>:</p>

<ul>
<li>Each interface defines a number named <code>credits</code></li>
<li>Add a brand property to each interface in order to uniquely identify each of them</li>
</ul>

<p>Create two functions named <code>sumMajorCredits</code> and <code>sumMinorCredits</code> in <code>task_5/js/main.ts</code>:</p>

<ul>
<li>Each function takes two arguments <code>subject1</code> and <code>subject2</code></li>
<li><code>sumMajorCredits</code> returns <code>MajorCredits</code> value and <code>sumMinorCredits</code> returns <code>MinorCredits</code> value</li>
<li>Each function sums the credits of the two subjects</li>
</ul>

  </div>

  <div class="list-group">
      <!-- LTI Resource -->

    <!-- Task Files -->

    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_5/js/main.ts, task_5/package.json, task_5/webpack.config.js, task_5/tsconfig.json</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11611">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>



            <div data-react-class="projects/ProjectReadyForReview" data-react-props="{&quot;csrfToken&quot;:&quot;wqnXNPaOiYYaybdQNN7nktZJ8QLvOUuhTRUA3N5RF5Gz8nCVfHUiMcwZYhxqhioC35dGg3HsZFJE9lFc-oZm2Q&quot;,&quot;firstReview&quot;:true,&quot;peerReview&quot;:{&quot;availableReviewersURI&quot;:&quot;/corrections/52486562/available_reviewers.json&quot;,&quot;canReviewPeerDirectly&quot;:true,&quot;cancelReadyForReviewURI&quot;:&quot;/corrections/52486562/cancel_ready_for_review.json&quot;,&quot;closeAt&quot;:&quot;2024-10-12T06:00:00.000+03:00&quot;,&quot;correctCorrectionURI&quot;:&quot;https://intranet.alxswe.com/corrections/52486562/correct&quot;,&quot;disabled&quot;:false,&quot;manualReviewBehavior&quot;:&quot;any_student&quot;,&quot;openAt&quot;:&quot;2024-10-09T06:00:00.000+03:00&quot;,&quot;qaReviewsURI&quot;:&quot;/corrections/to_review&quot;,&quot;readyForReviewURI&quot;:&quot;/corrections/52486562/toggle_ready_for_review.json&quot;,&quot;synchronousManualReview&quot;:false},&quot;toggled&quot;:false}" data-react-cache-id="projects/ProjectReadyForReview-0"></div>

          <div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;available&quot;:true,&quot;description&quot;:&quot;\u003cp\u003eUbuntu 18.04 with Node 12\u003c/p\u003e\n&quot;,&quot;id&quot;:29,&quot;name&quot;:&quot;Ubuntu 18.04 - Node 12&quot;,&quot;online&quot;:true}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;02i2fWrWL83STN_qdex3kToBX93c7hEzkN7cpf_HpGaiMxHc4C2EegScCqYrtLoBM9_oXEI7PsCZPY0l2xDVLg&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"></div></div></div></div></div>

  </div>
</div>


      
    </div>
  </div>


      </article>

        <div class="copyright">Copyright © 2024 ALX, All rights reserved.</div>

    </main>

        <button class="btn btn-primary atop-help" id="search-button" data-search-active="false" data-toggle="modal" data-target="#search-modal">
  <i aria-hidden="true" class="fa-solid fa-magnifying-glass "></i>
  <i aria-hidden="true" class="fa-solid fa-window-minimize "></i>
</button>

        <div class="modal fade" id="search-modal" tabindex="-1" role="dialog" aria-labelledby="search-modal-label">
    <div class="modal-dialog modal-md">
        <div class="modal-content">
            <div class="modal-header">
                <div id="search-bar-container">
    <input id="search-bar"
            autocomplete="off"
            type="text"
            name="hbtn-search-bar"
            placeholder="✨Start search by typing in this field✨">
</div>

            </div>
            <div class="modal-body">
                <div id="modal-spinner" class="spinner gap">
                    <div class="bounce1"></div>
                    <div class="bounce2"></div>
                    <div class="bounce3"></div>
                </div>
                <div id="search-results-container">
</div>

            </div>
        </div>
    </div>
</div>



        <div class="modal fade" id="markdownGuideModal" tabindex="-1" role="dialog" aria-labelledby="markdownGuideModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-md">
    <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title">Markdown Guide</h4>
        </div>
        <div class="modal-body">
            <h4>Emphasis</h4>
<pre>**<strong>bold</strong>**
*<em>italics</em>*
~~<strike>strikethrough</strike>~~</pre>
<h4>Headers</h4>
<pre># Big header
## Medium header
### Small header
#### Tiny header</pre>
<h4>Lists</h4>
<pre>* Generic list item
* Generic list item
* Generic list item

1. Numbered list item
2. Numbered list item
3. Numbered list item</pre>
<h4>Links</h4>
<pre>[Text to display](http://www.example.com)</pre>
<h4>Quotes</h4>
<pre>> This is a quote.
> It can span multiple lines!</pre>
<h4>Images</h4>
<p>CSS style available: <code>width, height, opacity</code></p>
<pre>![](http://www.example.com/image.jpg)
![](http://www.example.com/image.jpg | width: 200px)
![](http://www.example.com/image.jpg | height: 124px | width: 80px | opacity: 0.6)
</pre>
<h4>Tables</h4>
<pre>| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John     | Doe      | Male     |
| Mary     | Smith    | Female   |

<em>Or without aligning the columns...</em>

| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John | Doe | Male |
| Mary | Smith | Female |
</pre>
<h4>Displaying code</h4>
<pre>`var example = "hello!";`

<em>Or spanning multiple lines...</em>

```
var example = "hello!";
alert(example);
```</pre>
        </div>
    </div>
  </div>
</div>


        <script id="cody-snippet">
          window.codySettings = { widget_id: "9993bc72-2258-452b-a4bf-b2fe1ad5e0d7" };
          !function(){var t=window,e=document,a=function(){var t=e.createElement("script");t.type="text/javascript",t.async=!0,t.src="https://trinketsofcody.com/cody-widget.js";var a=e.getElementsByTagName("script")[0];a.parentNode.insertBefore(t,a)};"complete"===document.readyState?a():t.attachEvent?t.attachEvent("onload",a):t.addEventListener("load",a,!1)}();
        </script>
  </body>
</html>

