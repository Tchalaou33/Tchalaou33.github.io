---
layout: post
title:      "Sinatra - It's Magic"
date:       2020-10-04 21:46:40 -0400
permalink:  sinatra_-_its_magic
---


It is Magic. Period! That's the end of today's blog, thank you and come again. 
If you did not know, laughing is my best talent. Get ready. After my last project, I discovered that I learn and retain the information better if I put it to work. Build a project to understand the labs and there functions in real-time. I know common sense, but let us be honest, it is not all that common. So, step one: What do I want? Step two: Let's make it pretty. These two steps are broad generalizations I used to simplify and stay on task, eliminating any attempt at ostentatious delusions. 

### Step One: What do I want?

Always the most madding endeavor. I replicated a step used in my last project, which came highly recommended by Avi. Check out this video [CLI Project](https://www.youtube.com/watch?v=_lDExWIhYKI) and this one [Sinatra Project Step 1](https://www.youtube.com/watch?v=y5XHoP5qwfY&feature=youtu.be). I wrote down what I wanted and needed my App to do. Out of the many videos that I watched regarding this project, a few thoughts stood out: make it relatable to you, what would you want an App to do, what kind of App would you use. I am a user learning to be a creator/developer. Insert clip of Sailor Moon twinkling stars. It is about to get magical. Here is what I came up with, A To-Do List App. I love making lists for everything. Not that I revisit even half of them. Sometimes I do. But just the act of getting ideas, tasks out of my head and on to paper is liberating. 

```
# App Overview

    Im going to build a To Do List Tracker app, where user can create To Do lists

# User Stories

## As a User, I will be able to ...
    - login, sign-up, and log out
    -create a To Do list
    -see all my To Do lists
    -edit my list_entries
    -delete my lists_entries

# Wireframing 

## Models will be: User and List-Entry

## User

### Attributes

    -name
    -email
    -password ( if use bcrypt, this will be 'password_digest' in th db)

### Associations 

    has_many :2Do_lists

## List_entry

### Attributes

    -content
    -user_id <-- this will be the foreign key!
    -date <-- this is a stretch goal?

### Associations 

    belongs_to :user

# MVP

Users can sign-up, login, logout, create lists, edit their own list_entries and view their list_entries


# Strecth Goals

    -CSS - make it look really nice
    -Tests
    -Include a join model
    -user can choose to my list public or private. (Accountabilty)
    
```

### Step Two: Let's make it pretty!

Now, let me build my App. I am going to keep it kosher my project will not be pretty. This step is all about getting my App working and meeting the guidelines. Striving for simplicity, I used the [Corneal](https://github.com/thebrianemory/corneal) gem. Blessing abundant, it scaffolded the bulk of my files and structure. Check out this link to learn more about it. All that remains is to fill in the blanks. There are a lot of them. It is never that easy, yet I will leave you with this last word, 'FIGHTING'!

### All the Rest

It took me three weeks and then some to complete this project: Procrastination, my ugly evil step-sister. But working through it, I must say that I have been in a state of constant awe. As you build and receive those confounded, irritating error messages (suprisingly helpful, Thank you Sinatra) you want, No need to keep pushing forward. Not excluding the thought of failing, creeping up behind you like the Ghost Rider with his flaming head and motorcycle. Stupid grin. Yet, you keep going. What is left is the sheer Boss B@$#&* swag that you made that,  BOOM! I'll leave you with these words of wisdom:

Fighting evil by moonlight
Winning love by daylight
Never running from a real fight!
She is the one named Sailor Moon!

 Magic.
