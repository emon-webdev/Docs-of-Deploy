# startToDeploy
start To Deploy


List of startToDeploy:

- [netlifyDeploy](#netlifyDeploy)
- [netlify404](#netlify404)
- [vercelDeploy](#vercelDeploy)


### netlifyDeploy

```js
// step 1 
$ netlify login
// step 2 (open cmd to root folder)
$ npm run build

// step 3 (open root folder then build folder drag and drop netlify > Sites)
// if you want modifie root file (then again command run)
$ npm run build
// open netlify project then drag and drop netlify project update

```

### netlify404

```js
// step 1 
create _redirects in public folder  
//step 2
open _redirects file paste it
/* /index.html 200

```
### vercelDeploy

```js

https://fahimahammed-cse.medium.com/deploy-an-express-api-on-vercel-eebc13ace629


// typescript mongoose

Vercel এ ডেপ্লয় এর ক্ষেত্রে কয়েকটি জিনিস খেয়াল রাখতে হবে
১। tsconfig.json এর মধ্যে
"module": "commonjs" */* Specify what module code is generated. */*,
"rootDir": "./src" */* Specify the root folder within your source files. */*,
"outDir": "./dist" */* Specify an output folder for all emitted files. */*,
এই কনফিগটি add করে নিতে হবে যদি আগে থেকে করা না থাকে
২। package.json এর মধ্যে
"scripts": {
"dev": "ts-node-dev --respawn --transpile-only src/server.ts",
"start": "node dist/server.js",
"build": "tsc"
}
৩। প্রজেক্টের রুট এর মধ্যে vercel.json ফাইল বানিইয়ে নিতে হবে
{

  "version": 2,
  "builds": [
   {
     "src": "dist/server.js",
     "use": "@vercel/node"
   }
  ],
  "routes": [
    {
      "src": "/(.*)",
      "dest": "dist/server.js"
    }
  ]
}
এরপর Cli দিয়ে deploy করে নিলেই কাজ শেষ , সার্ভার রেডি
vercel --prod
module.exports = app

```


### Table
<div class="overflow-x-auto">
  <table class="table w-full">
    <!-- head -->
    <thead>
      <tr>
        <th></th>
        <th>Name</th>
        <th>Job</th>
        <th>Favorite Color</th>
      </tr>
    </thead>
    <tbody>
      <!-- row 1 -->
      <tr>
        <th>1</th>
        <td>Cy Ganderton</td>
        <td>Quality Control Specialist</td>
        <td>Blue</td>
      </tr>
      <!-- row 2 -->
      <tr>
        <th>2</th>
        <td>Hart Hagerty</td>
        <td>Desktop Support Technician</td>
        <td>Purple</td>
      </tr>
      <!-- row 3 -->
      <tr>
        <th>3</th>
        <td>Brice Swyre</td>
        <td>Tax Accountant</td>
        <td>Red</td>
      </tr>
    </tbody>
  </table>
</div>



## 🌐 Socials: Connect with Emon Hossain!

[![Facebook Badge](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://fb.com/emonhossain6) [![Linkedin Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emon007iu/) [![Twitter Badge](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/@emon_hossain7) [![Mail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emon.hossain.wd@gmail.com)

<h4>❤️🤔 You can follow my Github and other social accounts 🤔❤️</h4>
<h2>❤️ Thank you very much! ❤️</h2>
