# Reconcept Angular assignment

This repository was forked from https://github.com/gothinkster/realworld. [Project README](REPO_README.md)

## What is this?

This repository is an example application which we use for our sollicitations. It is a simple blog application which is built with Angular and uses the RealWorld API.

There are a few bugs and a some feature requests we have for this application.

## What do I need to do?

You don't have to prepare anything, but of course you can write some code if you want to.
We use this project to have a few talking points during the interview. We'll ask some questions on how you would tackle the issue or feature, or maybe do some pair programming.

# API

- https://realworld-docs.netlify.app/docs/specs/backend-specs/endpoints

Below are the assignments you can do to show your Front-end Development skills.

## Bugs

### Update article

I am unable to update an article i created. The application shows an error message "title must be unique"

### Edit profile empty

When editing my profile, all the fields are empty.

### Menu becomes invisible after logging out and back in

When i logout and back in, the menu bar at the top disappears. It comes back after a refresh
Steps to reproduce

- login as: asdf@asdf.com, ww: asdf
- Go to Settings
- Click on 'Or click here to logout'
- Click on 'Sign in' in the top menu
- Relogin

Expected Result
The top menu bar is available

Actual resulta
The top menu bar is not visible
—

## Small Features

### Tag list component

The tag-list is duplicated in multiple components, this can be a component on its own.

### Long article titles

When an article has a very long title, this takes up most of the screen space.

### Minimal number of words in article

We'd like to have a minimal word count for the articles.

### Delete confirmations

When deleting in the application, like an article for example, we want a nice confirmation modal to make sure the user meant this action.

### Errors in Article form

We'd like to have a more visual indicator for the fields that have an error.

## Medium features

### Compact view of the feed

We'd like to have a compact view for the feeds.
Must have:

- The same information
- Can switch back

Nice to have:

- When i've set the compace view as an option, i'd like to have this remembered so the next time i go to the page i see the view as i have chosen

### Find article by author

In the feed overviews:

- Global feed
- Your feed
- Favourited posts tab in my profile

We'd like a simple filter to find articles for an author.

### Filter comments

In the Article view, we'd like to be able to filter the comments on the following:

- User
- In a certain period
- minimum word count

### Multiple tags as tabs on the home page.

When we select a tag on the Homepage, this gets added as a tab next to "Global Feed" and "Your Feed".
We'd like to have multiple tags as tabs on this page.

Must have

- Closeable
- Have to remain when selecting "Global Feed" or "Your Feed"

## Large feature

When i'm offline, i'd like to be able to create articles to post later when internet is available again

Must have

- publish article, when no internet available i should get a notification
- Overview of the saved articles to be published
- Publish one by one, or all at once

Nice to have

- Add option to automatically post when internet is available again. This should be an option for each indiviual article.

## General improvements

### Improve UX

Any improvement you can find to improve the user experience

### Refactors

Do any refactor you see in the codebase

### Testing

Add tests to code where you see an opportunity to do so.
this can be

- unit
- integratino
- e2e
