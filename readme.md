MWTHOD 1:
gitv -repo create
Enter
git cline <link>
Enter
git add . / git add index.html
Enter
git commit -m "msg"
Enter
git push origin main


#Method 3
```
1. git beanch  --> hoe many branch in repo git branch <branch name>

2. git branch <branch name>
ex. git branch development

3.git checkout <branch name>
ex.git checkout development

```

#tailwind css clr
<h1>Website</h1>
1. copy - npm install tailwindcss @tailwindcss/cli
2. copy - @import "tailwindcss";
3. copy - npx @tailwindcss/cli -i ./input.css -o ./output.css --watch


<h1>vs scode</h1>
1. open terminal <br>
2. paste cmd <br>
3.Enter <br>
4.create index.html and input.css <br>
5. index.html -->   <link rel="stylesheet" href="./output.css"> <br>
6. inout.css --> @import "tailwindcss"; <br>
7. package-json --><br>
  "scripts": {
      "dev" : "npx @tailwindcss/cli -i ./input.css -o ./output.css --watch" 
    
  }
  8. npm run start
