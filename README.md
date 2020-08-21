# Doggy-Day-Care

### This is an example of how you can play around in Vue.js with an API.

This is a link to an API filled with [dogs](https://api.jsonbin.io/b/5f33ff6c1823333f8f226715.

### Initialize the Vue instance with some room for the doggies!

`
const app = new Vue({
        el: '#app',
        data: {
            dog: 'Chihuahua'
        }
    })
`

### Once you have created your Vue instance, let's make use of it in your HTML


<code>
        <html lang="en">
        <head>
            <meta charset="UTF-8">

            <title>Document</title>
        </head>
        <body>
            <div id="app">
                <h1>Dog care</h1>
                {{dog}} is here
            </div>
        </body>
        </html>
</code>


