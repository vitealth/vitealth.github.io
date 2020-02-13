# vitealth.github.io

http://www.vitealth.net/termsofservice
http://www.vitealth.net/privacypolicy

파일 : UTF-8로 저장.

지킬 local에서 실행-에러체크
bundle exec jekyll serve
 
수정하는법.

_site는 컴파일 결과로, client에서는 건드리지 않는다.
github에 올라가면 자동으로 컴파일되서 github의 _site가 생겨 html이 생성된다.

root에
*.html 파일이 github에 올라가면 jekyll 컴파일이 자동으로 이루어짐.

알파벳 순서로 자동 소팅.
현재는 respio 을 index 로 만들어 첫페이지를 영어로 나오게 하였음.




http://jmcglone.com/guides/github-pages/


https://gist.github.com/TylerFisher/6127328

Steps for Hosting a Website on GitHub
Create a GitHub account on github.com.
Download either GitHub for Mac or GitHub for Windows, depending on your operating system. Open the app and log in using the account you just created.
(On Mac): After you login, click advanced and make sure that your name and email are correct. Then, click "Install Command Line Tools", just in case you want to start using the command line later in life.
Create a new repository in your GitHub application. Name it your-username.github.io. The name is very important. Note the folder that GitHub is saving the repository to. Make sure the "Push to GitHub?" box is checked.
Move your website's files into the folder that GitHub just created when you made the repository. IMPORTANT: Your homepage HTML file must be called "index.html", and it must exist in the top-level directory.
Back in the GitHub application, you should see your files in the left column. Make sure they are all checked. If so, enter a message in the text box called "commit summary", something like "initial commit." Then, click the commit button.
Click the "Publish repo" button in the top right corner.
Give it about 10 minutes, then check your-username.github.io. Your website should be there!
Using a custom domain name
You can just leave your website at that address (it'll give you some serious street cred in the developer world), but if you have a custom domain you would like to use, it is very simple to make GitHub redirect your page.

Log in to your domain registrar and find where to change your host records. If you don't know, you can usually Google "(domain registrar) change host records", and your registrar will have an explainer telling you how to do it.
Change your domain's A Record to 204.232.175.78. This is GitHub's IP address, which allows GitHub to resolve your URL and serve the correct files.
In your website's directory folder on your computer, create a file called "CNAME". On the first line, type your domain name. Save the file.
In your GitHub application, you should see the file in the left column. Make sure it is checked and enter your commit message. Have it say something like "Adding CNAME file."
Click "Sync branches."
It can take as long as 48 hours for your domain to resolve to your GitHub page. However, it is usually pretty quick, so check back in an hour or so.


