# IBANVerificationFrontend

Deployment instructions:
  prerequisites:
    http server installed (recommended http-server). Npm command: npm install --global http-server
    Following REST APIs deployed and running:
      https://github.com/tautvydaskub/SingleIBANVerificationService (uses port 8081)
      https://github.com/tautvydaskub/MultipleIBANVerificationService (uses port 8082)
  deployment steps:
    - Start the http-server on an open port. Command: http-server -p 8083
    - The website should now be accessible through http://localhost:8083
