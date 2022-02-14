# TinderClone for us to add anyone with name and image
Tinder for you to add whoever you like and use to have fun?
\
\
Buttons are not working, so... don't poke them :|
> **If you want to add someone please see the [Adding new people](#adding-new-people) section**


# Application URL
Website is served on Firebase, you can use the application from this link

https://tinder-clone-9be9a.web.app/

# Adding new people
Backend is deployed on heroku so you need to send a post request to this url

```https://tinder-clone-backend-mus.herokuapp.com/tinder/cards```

example url body:
```
[
	{
	  "name": "Albert Einstein",
	  "imgUrl": "https://upload.wikimedia.org/wikipedia/commons/thumb/d/d3/Albert_Einstein_Head.jpg/1536px-Albert_Einstein_Head.jpg"
	}
]
```

# Getting People as JSON
Click or type this on your favorite browser. This way you could get a json that filled with other people on TinderClone.

https://tinder-clone-backend-mus.herokuapp.com/tinder/cards
