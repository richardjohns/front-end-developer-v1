![BNZ Careers](./bnz-logo.jpg)

# Candidate screen: Front-end Developer

![PRs Welcome](./prs-welcome.svg) ![Coverage: 100%](./coverage-100.svg) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

Hello, potential BNZ Front-end Developer!

The purpose of this candidate screen is to determine whether a job applicant has the potential to succeed as a front-end developer at BNZ Digital. This is _not_ a test. It's a _filter_. We want to match the right people to the right jobs.

A review of your code will be used to decide whether to invite you to an initial interview, or to further refine our understanding of your skills. This is only one step in the hiring process, but it will help us to get a feel for where you might fit.

## Instructions

_Please read these instructions carefully!_

Reread them before you begin, if necessary, and check them whenever you need to.

1. **You are welcome to use any resources you have available.** You'll have them available on the job, so why not here? This isn't a test of your ability to memorize! Using resources well is a good thing, so please add a comment in your code listing any resources you used.
1. We want to see how you **work through the feature request we provide below**. You don't need to be an expert at the types of code you'll find here: just show us how you'd go about solving it. If you _are_ an expert, then do your best to impress us. If not, then show us how you would bring yourself up to speed.
1. Choose a time when **you can work for two hours uninterrupted and without distractions**. We'll check the timestamps on your commits to get a feel for how long things took. If you get interrupted, that will throw your times way off. So please try to work steadily for two hours.
1. You can put in more time if you want to, but **two hours ought to be enough**. That said, _you don't have to finish the feature_. Is anything ever really finished? Get as far as you can in the time you have available and don't worry about it.
1. Do the best work you can. **It's not just about the code.** We'll be looking at the big picture: How do you think? Do you pay attention to detail? Can you work well with others? And more.
1. **Document! Document! Document!** Use comments in the code to explain your thinking: What made you choose this way? What kinds of things are you looking out for? Did you consider any other approaches? If so, what made you reject them? Help us to get to know the real you. In an interview, these are the sorts of issues that we may follow up on.

**Note:** Using resources is wise; copying and pasting large amounts of code or having someone else do the work for you will only waste your time and ours: it will become quickly evident what happened when you get to the first interview. In other words, don't try to game the system; just do your best work. This isn't a test! It's a matchmaker. **We're looking for a good match.**

## The idea

**Add a feature to the CountryCodeTable.** You could make the columns sortable in one or both directions. You could add a search feature, or a filter that filters by rows. What about pagination? It's up to you, but try to choose something that you can **make reasonable progress on** in two hours' time. **Note: _we don't expect you to finish the feature_**. Don't go crazy, just give us some idea what you can do. Unless you happen to already know this code, the suggestions here will take most developers significantly longer than two hours. You don't need to finish. Really.

## Requirements

You'll need a recent version of **[node.js](https://nodejs.org/en/download/)**, a good text editor (**[Atom](https://atom.io/)**, **[Visual Studio Code](https://code.visualstudio.com/)**, etc.), and a recent browser (**[Chrome](https://www.google.com/chrome/browser/desktop/index.html)**, **[Firefox](https://www.mozilla.org/en-US/firefox/new/)**, etc.). Optionally, you can install **[yarn](https://yarnpkg.com/en/)**, but **[npm](https://www.npmjs.com/)** will work as well. If you're working in Chrome, consider installing the [Redux DevTools](http://extension.remotedev.io/) extension. It will really help. [React DevTools](https://github.com/facebook/react-devtools) can also be useful. But don't spend too much time on this.

## Procedure

1. Fork this repository.
2. `cd` into the project directory and install the dependencies with `yarn` or `npm install`.
3. Run the tests with `yarn coverage` or `npm run coverage`. You should see all green and 100% coverage. If not, let us know.
4. Run the app. **Important:** You'll need to run both the **app** and the **API server**.
    * In one terminal window/tab, use `yarn server` or `npm run server` to start the server.
    * In another terminal window/tab, use `yarn start` or `npm start` to start the app.
    * A browser should open pointing to [http://localhost:4000/](http://localhost:4000/). If not, open one yourself. You should see a table listing calling codes by country.
    * You can make sure the server is running by opening [http://localhost:4001/externalData](http://localhost:4001/externalData) in a browser. You should see a JSON array of country calling code objects.
5. Commence work on the problem, paying attention to the instructions above.
6. **Make frequent commits! Make frequent commits! Make frequent commits!** We want to see how your code develops and how much time you spent on each part.
7. **Document your thinking!** (Use comments in the code, preferably). Help us to understand why you went the route you did.
8. After a couple of hours work, give or take, find a point where you can stop&mdash;don't worry if you haven't finished the feature&mdash;and do a final commit.
9. _Did we mention documenting your reasoning for your decisions?_ Make sure you've documented it well.
10. When you're sure you're ready, zip your code up and send it to us (don't include the _node_modules_ folder, please), or put it in dropbox for us, or put it on your GitHub account and send us the link&mdash;in short, get the code to us somehow. In your email, tell us what you did and why. Include anything you want us to consider when reviewing your code.

## Resources

This application was created initially with [create-react-app](https://github.com/facebookincubator/create-react-app): create React apps with no build configuration. It has been [ejected](https://github.com/facebookincubator/create-react-app#converting-to-a-custom-setup).

If you want more information on the libraries included here, read the [resources list](./RESOURCES.md).

## What's next?

When we see your code we'll acknowledge receipt, then we'll review it. If we determine that you might be a good fit for the job, then we'll contact you to set up a first interview. If we think the job is not for you, we'll still consider you for any other positions that you might fit. Any way you cut it, we won't leave you hanging. We'll tell you the outcome either way.

Have fun! We look forward to seeing your work.
