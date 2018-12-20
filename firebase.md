Status: Firebase is not fully banned in China
Solution source :https://github.com/Gaubee/blog/issues/106

## Firebase-tool
You should add proxy attribution in the sourcecode, find _request function in api.js, add:
 >options.proxy = "http://127.0.0.1:8118";
 
## Firebase-admin
