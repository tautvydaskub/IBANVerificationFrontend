# IBANVerificationFrontend
<br/>
<br/>
Deployment instructions: <br/>
  prerequisites: <br/>
    - http server installed (recommended http-server). Npm command: npm install --global http-server <br/>
    - Following REST APIs deployed and running: <br/>
      https://github.com/tautvydaskub/SingleIBANVerificationService (uses port localhost:8081)<br/>
      https://github.com/tautvydaskub/MultipleIBANVerificationService (uses port localhost:8082)<br/>
  deployment steps:<br/>
    - Start the http-server on an open port. Command: http-server -p 8083<br/>
    - The website should now be accessible through http://localhost:8083<br/>
