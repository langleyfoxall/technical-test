# Langley Foxall - Technical Test

## General
This test is designed to focus on assessing how developers approach certain tasks, whilst also demonstrating programming
capability, followed by displaying knowledge of the languages/frameworks/packages.

Whilst you can spend as long as you would like on it, we recommend you spend no longer than a few hours.

The project should be easy to get running by a developer on our team after you've finished. Any nuances should be 
documented.

The use of well supported, open source packages is allowed.

You should complete this test yourself and shouldn't outsource any of the work.

## Tech Stack
We primarily use Laravel and React for our web based systems, among other technologies - so we heavily prefer that you 
use this stack for this test.

There is the option to make the front end side of this task reactive, but this isn't necessary.

You could use our [boilerplate](https://github.com/langleyfoxall/laravel-boilerplate), but it is more geared towards larger
projects, and is yet to be updated to Laravel 6.0.

## The Vision 

> Note: This is entirely fictional and none of the results from the test will be used by Langley Foxall.

Our client would like a site developed that allows for retrieval of weather forecasts along with an email subscription 
to weekly weather breakdowns. 

They're looking to launch the site as a free tool that - once they've launched it and have a good amount of traffic - 
creates profit through advertisements. It will be hosted under the domain **myweather.co.uk**.

There would be further phases of development to introduce this, but the client would like an MVP for an initial release.

Support for future languages would be in a future phase.

The client envisions that they will have 120,000 subscribed users in the first three months with their marketing plan.

The client is aware that they have a tight budget, and we should prioritise the backlog in order to deliver as much of a
product as we can in the small timeline. The client does however insist that the mail subscription is vital to the products
launch.

The client has no specific requirements in terms of design.

## The MVP / Phase 1

- Be able to sign up to the site.
  - Collect users preferred location.
- Be able to log in to the site.
- Once logged in, pull and display weather forecasts from the [Open Weather API](https://openweathermap.org/api) for the 
week in the users preferred location. (This has been recently updated from Dark Sky, since they were purchased by Apple)
  - Be able to select a single day in order to display more information for that day.
  - Be able to change the location
- Every Sunday morning - send an email to all users for an overview of weather in their preferred location for the week.

## Submission
The resulting repository can either be submitted via GitHub (Invite the person who sent you the test's GitHub Account to 
a private repository), or via WeTransfer (without the dependency directories).

## Questions / Improvements
Have any questions/improvements for the test? Submit a GitHub issue against this repository and we will get back to you.
