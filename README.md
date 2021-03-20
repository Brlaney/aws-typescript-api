# Modern dilemma

### An ameteur's attempt at developing a modern web-application. 

### Keywords

- Typescript
- Webpack
- serverless.ts
  
### Let's be honest though I followed a tutorial on youtube:
Link: [**Complete Coding**](https://youtu.be/HhgXwKFUzT8)

<hr>


### Step 1.) Generate your boilerplate app with **aws-nodejs-typescript** template 

`
serverless create --template aws-nodejs-typescript --path aws-typescript-api
`
</br>

### Step 2.) Create **lambdas** folder in project directory

Use npm to install all package.json dependencies that come striaght out of the box with the *aws-typescript-api* template we've used

`npm install`

</br>

### Step 3.) Create **lambdas** folder in project directory

```
mkdir lambdas 
cd lambdas

for windows
echo > getCityInfo.ts

for linux
touch getCityInfo.ts
```

</br>
