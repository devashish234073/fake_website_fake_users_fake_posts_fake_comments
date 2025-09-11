# fake_website_fake_users_fake_posts_fake_comments
This is a nodejs application that serves a minimal social medial like app, with the html having a copilot that every few seconds create new post by asking llm to create one, or searching and sending friend request or adding comment by sending the ollama model the context of the post

See this video for details: https://www.youtube.com/watch?v=AiQDjxESjwU

To run:

```
git clone https://github.com/devashish234073/fake_website_fake_users_fake_posts_fake_comments
cd fake_website_fake_users_fake_posts_fake_comments
npm install
node server.js
```
Then in browser go to http://localhost:8080/?user=deva to create and login as user deva 

You can add as many tab as the number of parallel users you need example http://localhost:8080/?user=deva2 in new tab

<img width="1787" height="965" alt="image" src="https://github.com/user-attachments/assets/edab1708-85c7-44d5-99af-cacc45bdb26e" />



