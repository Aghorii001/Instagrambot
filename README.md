# Instagrambot
Instagrambot
enter image description here

Instagrambot is a high-performance system developed in JavaScript to create a bot for Instagram, support for creating posts, comments, liked posts, follow, unfollow and all types of design architecture for Instagram.

 Functions Instagrambot
Automatic Login	✔
Get Post, Commets, Media, Likes and Profile	✔
Search for keywords and Hashtag	✔
Register Automatic	
 and much more	✔
Installation
> npm i --save Instagrambot
Getting started
const venom = require('Instagrambot');

(async () => {

const insta = await venom.launchBot({ headless: true });

// login
await insta.login("[your-username]", "[your-password]");

.....

})();
After executing launchBot() function, venom will create an instance of Instagram web.

Optional create parameters
Venom launchBot() method third parameter can have the following optional parameters:

insta.launchBot({
  headless: true, // Headless chrome
});
Maintainers
Maintainers are needed, I cannot keep with all the updates by myself. If you are interested please open a Pull Request.
