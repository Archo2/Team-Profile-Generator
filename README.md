# Team Profile Generator

A Node.js command-line app that asks about your software team and generates an HTML page with a card for each team member.

**Demo video:** https://watch.screencastify.com/v/32Awb8D2NmqCE2Gvh0xr

## Features

- Prompts for a **Manager**, then lets you add any number of **Engineers** and **Interns**
- Collects name, ID and email for everyone, plus:
  - Manager: office number
  - Engineer: GitHub username (links to their profile)
  - Intern: school
- Writes a styled team page to `output/team.html`
- Built with object-oriented classes (`Employee`, `Manager`, `Engineer`, `Intern`) with Jest unit tests

## Built With

Node.js · Inquirer · Jest · HTML · CSS

## Getting Started

**Prerequisites:** Node.js

```bash
git clone https://github.com/Archils/Team-Profile-Generator.git
cd Team-Profile-Generator
npm install
npm start
```

Answer the prompts, then open `output/team.html` in your browser.

## Tests

The unit tests are in the `_test_` folder:

```bash
npx jest _test_
```

## Screenshots

![Screenshot](mock-Up.jpeg)

## Author

**Archils Oburu**
- GitHub: [@Archils](https://github.com/Archils)
- Email: oburuarchils@gmail.com
# Team-Profile-GeneratorS A manager
https://watch.screencastify.com/v/32Awb8D2NmqCE2Gvh0xr

This app was created using Object-Oriented Programming concepts, namely using classes and constructors to create "team" objects based on information entered by the user. The app is run using Node.js, and uses the "Inquirer" and "FS" node modules. Files for different objects are also stored in separate .js files and passed among one another using module.exports and require.


![](mock-Up.jpeg)
