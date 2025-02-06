# App Installation
npm i

npm start

### API Endpoints

The application fetches commit data from a backend service running at http://localhost:5000. Ensure the backend is running and exposes the following endpoints:

Get commit details:

GET /repositories/{owner}/{repo}/commits/{commitOid}

Get commit diff:

GET /repositories/{owner}/{repo}/commits/{commitOid}/diff

### Sample repo
http://localhost:3000/repositories/golemfactory/clay/commits/a1bf367b3af680b1182cc52bb77ba095764a11f9

### Backend env
GITHUB_TOKEN = your token from github ( Available in github settings/developer settings/personal access tokens/fine grained tokens) 

![image](https://github.com/user-attachments/assets/d78d34c6-fb4a-45fd-9102-5c9c6f39de6a)

