# the Sideline Story | a Coder's Blog

the Sideline Story a Coder's Blog will profile my journey to becoming a professional and freelance web developer. My goal is to   


## Built With

* Embedded JavaScript (EJS)
* Javascript
* Node JS & Express
* Mongoose
* MongoDB Atlas


## What I learned building the Sideline Story

*  What is EJS?
    * templating language/engine that generates HTML with plain JS

    * EJS is extremely helpful in generating dynamic content with real-time updates.

    * EJS has 4 frequently used tags:
      * **<% %>** : are used to for control flow i.e. bindings, control flow, conditional, no output

      ex:
        ```<% previousPost.forEach((post) => { %>
          <h2>
            <%= post.title %>
          </h2>

          <% }); %>
        ```


      * **<%= %>** : outputs the value into the into the template

        ex:
        ```<%= post.content.substring(0, 100) + " ..." %>```

      * **<%- -%>** : outputs the unescaped value in the template

         ex.
        ```<%- include('partials/footer') -%>```


      * **<%# %>** : are used for comments



* Overall more comfort with Javascript, Node, and Express. <br/>
