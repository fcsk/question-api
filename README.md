<h1>API for Quiz Server - <a href="https://github.com/fcsk/quiz">Quiz Project</a> </h1>
    <p>This repository contains the source code of the project's quiz server questions API - <a href="https://github.com/fcsk/quiz">https://github.com/fcsk/quiz</a></p>
    <h2>Installation</h2>
    <p>If you do not want to install the project yourself, see it at <a href="If you do not want to install the project yourself, see it at <a href="https://question-qpi.onrender.com/questions">https://question-qpi.onrender.com/questions</a></p>
    <ol>
      <li>Clone this repository to your local machine using the following command:</li>
      <code>git clone https://github.com/fcsk/question-api.git</code>
      <li>Navigate to the cloned repository directory:</li>
      <code>cd question-api</code>
      <li>Install the json-server using NPM:</li>
      <code>npm install -g json-server</code>
      <code>npm install -g json--registry https://registry.npmjs.org</code>
      <li>Start the JSON server:</li>
      <code>json-server --watch question.json</code>
      <li> The API will be available at http://localhost:3000/questions
    </ol>
    <h2>Usage</h2>
    <p>This API serves questions in JSON format. You can access the questions by sending HTTP requests to the appropriate endpoints.</p>
    <p>The available endpoints are:</p>
    <ul>
      <li>/questions - Returns an array of objects, each of which is a question with answers and flag of  correct answer</li>
    </ul>
    <p>You can use a tool like <code>curl</code> or a web browser extension like <code>RESTClient</code> to send HTTP requests to these endpoints.</p>
    <h2>Contributing</h2>
    <p>If you find a bug or have a suggestion for a new feature, please open an issue or submit a pull request.</p>
    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
  </body>
</html>
