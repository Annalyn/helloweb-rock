#Planning our Application
###Answer Questions
- What are we building?
- Who are we building it for?
- What features do we need to have?
- User Stories
- Model Our Data
- Think through the pages we need our app


# What are we building?  
We are building a personal site.  A place where we can blog, share examples of our work, and have people to contact us.

# Who are we building it for?  
We are building it for ourselves, but also the community.  Sharing what we are learning by blogging is a great way to learn for ourselves.  but we teach others in the process.  Show potential employers that we know what we are doing.
# What features do we want to have?
Posts
create / Edit/ Destroy
markdown
Syntax highlighting
Comments (Disqus)
Projects
Create / Edit /Destroy
Contact
-Contact form
Sendgrid
User (Devise)

## User stories.
- As a blank, I want to be able to blank, so the blank.
- As a user, I want to be able to create a posts so that I can share what I am learning on my blog.
- As a user,  I want to be able to edit & destroy posts, so that i can manage my blog.
- As a user, I want to be able to edit & destroy posts in markdown format so that it’s easy for me to write posts.
- As a user, I want to be able to highlight the various syntax of code blocks that I share my blog.
- As a user, I want to show the visitors and potential employers examples of my work, or stuff I’ve built.
- As a user, I want to be able to have visitors contact me through a form on my site.
- As a user, I want visitors to be able to leave comments on my posts.

## Modeling Our Data
	Posts
		title:string
		content:string

	Projects
		title: string
		description: text
		link: string

	User
		Devise

## Think through the pages we need in our app
- Home
- Posts
- Posts#
- Projects#index
- Projects#show
- Contact