# Web-ticketsite
<h1>Initial Request</h1>
<p>Client request for a website with the ability to view some events, and purchase tickets for events.</p>

<h2>Description</h2>
<p>To start I was thinking a simple website using Python, Flask and Bootstrap 5. It can start with limited functionality. I think the core goals would be to displaying, creating, editing events (most likely on the homepage), 
allowing users to purchase tickets for events (using Stripe, or other credit-payment APIs), and it is important to be PCI compliant in our production.</p>
<a href="https://chat.openai.com/share/e/cc6836e3-6ca0-47ad-9da3-b75033da1e10">Link to GrimoireGPT Code snippets</a>

<h2>Details</h2>
<h3>Backend</h3>
<p>As much as I want to avoid it I am going to need to think of a database solution. <ul>@LuisPuga</ul> you can weigh in on this. To what extent do we need a object relational mapper? Like now that I am thinking about it my initial pitch of using Flask might be wrong cause that's more for static webpages. We can integrate SQLAlchemy with flask for an ORM solution or Django (another python backend with ORM) is an option.</p>

<h3>Frontend</h3>
<p>Bootstrap 5 is a pretty simple CSS framework. I admit it is just what I've used briefly but have no particular attachments to it.</p>

<h2>Tasks</h2>
