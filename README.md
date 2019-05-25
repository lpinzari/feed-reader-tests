# Feed Reader Testing with Jasmine

In this project we'll use the framework [Jasmine](http://jasmine.github.io/) to write a number of tests for a pre-existing RSS Feed reader application. The Udacity's developers have already included *Jasmine* and started writing a test. We'll use *TDD* (**test driven development**) techniques and *JQuery* to write the remaining tests. For the specification of the tests, development strategy and starter code please refer to the following link [Project Requirements](https://github.com/udacity/frontend-nanodegree-feedreader).

## Table of Contents

* [Project Design](#project-design)
* [How to Run](#how-to-run)
* [How to Use the Application](#how-to-use-the-application)
* [Technologies Used](#technologies-used)
* [Acknowledgement](#acknowledgement)
* [Author](#author)
* [License](#license)

### Project Design

The application includes four **tests suite**. Each **test suite** contains one or more `specs` (tests):

1. **RSS Feeds**
    * `feeds are defined and not empty` (pre-existing test)
    * `urls are defined and not empty`
    * `names are defined and not empty`
2. **The menu**
    * `it is hidden by default`
    * `it displays when clicked and hides when clicked again`
3. **Initial Entries**
    * `loaded one or more entries within the feed container`
4. **New Feed Selection**
    * `selected feed loaded`

All the tests are implemented in the `feedreader.js` file.

### How to Run

- **Run:** If you want to run the application *locally* on your computer,you can download the files from this repository or clone them.
    - **Download**: Click the <code>Clone or download</code> green button and you'll get the *Project Zip* file. When your download finishes, unzip the file and open the <code>index.html</code> on your browser.
    - **Clone**: type into your terminal the following <code> $ git clone https://github.com/lpinzari/feed-reader-tests.git</code>. When it finishes cloning, open the <code>index.html</code> file on your browser.

### How to Use the Application

Once the <code>index.html</code> is opened on your browser, scroll down to the bottom of the page and click on the **test suite** (i.e set of tests) or `spec` to run. You can also choose to run all tests at once.

### Technologies Used

- **Jasmine** | **JQuery** | **HTML** | **CSS**

### Acknowledgement

I'd like to thank the Udacity's mentors and instructors for the useful advices.

### Author

Ludovico Pinzari

### License

This application is licensed under the MIT. See the [LICENSE](./LICENSE) file for more details.
