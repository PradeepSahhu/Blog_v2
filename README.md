# Blog_v2
Blog server with mongooseDB. Used mongooseDB as a database for storing blog posts and cloud storage with the help of mongoose Atlas. node modules like lodash, ejs formed a dynamic functionality .

# Node Modules


## Express
- Express route parameters.
- body-parser

## EJS
- For multiple *for generating web pages that can include dynamic data and can share templated pieces with other web pages*
- ejs.co

![ejs](https://user-images.githubusercontent.com/94203408/154403247-cfdb792f-aa1f-4a23-a0bf-dd278238837c.png)


```
let ejs = require('ejs');
let people = ['geddy', 'neil', 'alex'];
let html = ejs.render('<%= people.join(", "); %>', {people: people});
```

### Usage
```
let template = ejs.compile(str, options);
template(data);
// => Rendered HTML string

ejs.render(str, data, options);
// => Rendered HTML string

ejs.renderFile(filename, data, options, function(err, str){
    // str => Rendered HTML string
});
```

## lodash
-  Havascipt library - helped  write more concise and maintainable JavaScript.

## Mongoose
- For database and cloud storage.(mongoose Atlas)

