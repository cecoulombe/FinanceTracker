# Website Documentation

This README file is specifically for the Finance Tracker website hosted through GitHub Pages.

## Contents
- [Access Instructions](#Access-Instructions)
- [TODO List](#To-Do-List-for-Website)
- [Version History](#Version-History)

## Access Instructions
The most up-to-date version of the Finance Tracker website is available [here](https://cecoulombe.github.io/FinanceTracker/)
- https://cecoulombe.github.io/FinanceTracker/

## To-Do List for Website

- [ ] Change method of converting currency. Currently, the app will change from currency A to currency B, then from currency B to currency C; however, this leads to an inaccurate representation of actual net worth
  - Intended solution: choose one "home currency" in which all values will be stored in, and only convert from that currency to the new currency, preventing loss or gain of funds.
- [ ] Increase the number of options for currency and add formatting that changes with the currency.
- [ ] Create an API that calls out to the third party conversion rates site so that it is not done directly through the web application.
- [ ] Learn AWS so that it can be used to host the site.

## Version History

- **v1.0**: Initial launch of the website with basic features written in Javascript and HTML.
  - [Link to the Webpage (OLD)](https://cecoulombe.github.io/FinanceTracker/tracker_HTML)
- **v1.1**: Website redesigned and implemented using React. New version control through a different repository as it is hosted via GitHub Pages rather than GitHub.io.
  - [Link to the Webpage](https://cecoulombe.github.io/FinanceTracker/)
