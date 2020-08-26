# Doggy-Day-Care

### This is an example of how you can play around in Vue.js with an API.

This is a link to an API filled with [dogs](https://api.jsonbin.io/b/5f33ff6c1823333f8f226715 "Dog API").

### Initialize the Vue instance with some room for the doggies!
<code>
const app = new Vue({
        el: '#app',
        data: {
            dog: 'Chihuahua'
        }
    })
</code>

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

### Don't forget to include the CDN 
<code>
        <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
</code> 

### Let's add some more dogs to the party!

<code>
    const app = new Vue({
        el: '#app',
        data: {
            dogs: ['chihuahua',
                'poodle',
                'rottweiler'
            ]
        }
    })
</code>


### To be able to iterate over our list of dogs, we got to make use of Vue's "v-for"

<code>
        
        <li v-for="dog in dogs">
            {{dog}}
        </li>
        
 </code>


