I would like to present my inaugural personal portfolio website, which I've developed entirely using HTML.
So, for the structure, I used all the heading tags, from <h1> right down to <h6> tag. I figured that would be the best way to organize everything logically, you know? Like my name is the big <h1>, then sections like "Skills" and "Education" are <h2> or <h3> tag, and I even went down to <h6> tag just to really show how things could be nested.

When it came to listing stuff, I used unordered lists, <ul> tag, for my skills. Since there's no real order to those, it felt right. But for my educational background, I used ordered lists, <ol> tag, because the timeline definitely matters, from school up to where I am now – an engineering student right here at REC Mainpuri, U.P.! I know I haven't actually put together a formal portfolio before, but I've learned about all this stuff and even played around with it on other sites, so I've got a good handle on the concepts.

For showing off any projects or maybe even past experiences, I used a <table> tag. It just seemed like the clearest way to present things like the year, what the project was, and a quick rundown.

Of course, I added a profile picture using <img> tag and made sure to include alt text. Gotta make it accessible for everyone!

Then, on the contact.html page, I set up a contact form using <form>. I wanted to make it easy for people to get in touch, so I included fields for their name, email, phone number, and a message.

Inside the form, I used all sorts of input types to make it user-friendly. There's <input> tag for things like text, email, phone numbers (I even tried to add a pattern to make sure it's a proper 10-digit Indian number!), dates, and even a cool range slider. For longer messages, I used <textarea> tag, and for some options, I used <select> dropdown menus. Oh, and I grouped related things like checkboxes using <fieldset> tag to keep it organized.

I also played around with some of the neat input types. For example, type="email" is awesome because it automatically checks if the email looks right. For phone numbers (type="tel"), I added that pattern to try and guide users to enter a valid 10-digit number. The type="range" slider is just a fun, visual way to get feedback. And type="date"? So much better than having to type out dates!

I also made sure to use required on important fields and played with pattern and minlength to try and catch any mistakes before someone submits the form. Hopefully, it'll make things smoother for anyone trying to reach out.

The website is pretty simple to navigate. I put a <nav> tag section at the top of each page with three main links: "Home" (which is the main portfolio.html), "About Me" (about.html where I can share a bit more about myself – and I even added some internal and external links like to my GitHub), and "Contact" (contact.html with the form).

As a little bonus, I even added a favicon – that little icon in the browser tab – using <link rel="icon">. And I tried to use HTML5 semantic tags like <header>, <nav>, <main>, <section>, and <footer> tag to make the code cleaner and easier for browsers and search engines to understand.

For the contact form, I added a few extra touches like that date picker, a dropdown asking how they found me, the range slider for rating the site, and those validation rules to make sure everything's filled out correctly.

So, that's the basic rundown of my HTML portfolio. It was a good learning experience just focusing on the structure and content using HTML. The styling and all the visual stuff with CSS is definitely the next thing I want to tackle. But for now, this is what I've put together to show the foundation!

Thanks for taking a look!

:-Ritik Rai