# Talgat Iskindir
**Email**: talgat.iskindir@gmail.com

**Phone**: +77077807477

### Summary
I am an experienced software developer and I am planning to learn the front-end development and, especially, the React framework more thoroughly.

### Skills
**Programming languages**: C/C++, Python, Javascript

**Frameworks**: Django, Bootstrap

### Code examples
###### Leetcode Problem #1032
```javascript
/* Constructor, init the data structure with the given words. */
var StreamChecker = function(words) {
    this._words = words
    this._query = '';
};

/* returns true if and only if for some k >= 1, the last k characters queried (in order from oldest to newest, including this letter just queried) spell one of the words in the given list. */
StreamChecker.prototype.query = function(letter) {
    this._query += letter;
    return this._words.some((word) => this._query.endsWith(word));
};
```

### Experience
I am a software development engineer with about four years of experience. During the first three years, I was programming in C/C++ and was building programs related to computer networks and distributed systems; some of the projects required me to develop a proxy server, a load balancer, a torrent-like application, a VPN desktop client and a Linux-kernel VPN module. I was dealing with these projects during my university days and while I was working in a company which focuses on development of hardware and software that allows computer systems in government agencies and banks to be secure.

One year ago, I became interested in web development, so I started learning different front-end, back-end and UI frameworks; however, I enjoyed and spent most of the time with the Bootstrap framework and the Django framework. When I built and deployed a website with the help of these frameworks, I started looking for an opportunity to learn something new.

Currently, I am going towards learning the React framework and the front-end development in general. Fortunately, I got to know about the course from the RS School and I am very happy to learn new skills from that course.

### Education
2013-2017 | Korea Advanced Institute of Science and Technology

### English
**B2** (Upper-intermediate)
