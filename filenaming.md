---
layout: page
title: File Naming & Organization
menu: true
order: 2
---

### Best Practices

Well-organized structures and file names make it easier to keep track of your data. When naming and organizing files, you should be consistent and descriptive to make it possible to find specific data and know what the files contain and what their status is. Set up a clear directory structure that includes information like the project title, a date, and some type of unique identifier. Individual directories may be set up by date, researcher, experimental run, or whatever categories make the most sense for you and your research needs.

### Structuring Data

Think carefully about how best to structure your data from the very earliest stages of your project. This is particularly important when you have a number of collaborators, or are planning on sharing your data. Think about whether you need a deep or shallow hierarchy.

Some examples of data structures include organization by:

* types of data (text, images, sound files, etc.)
* research activities (interviews, surveys, focus groups, etc.)
* material (data, documentation, publication, etc.)

File names should allow you to identify data with precision from the name. Choose a format for naming your files and use it consistently. Include in the name the information that will allow you to distinguish your files from one another. Some of the elements to consider including:

* Project or experiment name or acronym
* Location/spatial coordinates
* Researcher name/initials
* Date or date range of experiment
* Type of data
* Conditions
* Version number of file
* Status information
* Three-letter file extension for application-specific files

### File Names

* All special characters such as `~ ! @ - # $ % ^ & * ( ) ; < > ? , [ ] { } ' " |` should be avoided. Stick to numbers, roman letters (preferably lower case), and underscores `_`.
* Do not use spaces or dashes. Some software will not recognize file names with spaces, and file names with spaces must be enclosed in quotes when using the command line.
* Alternatives to spaces include:
  * Underscores, e.g. `file_name.xxx`
  * No separation, e.g. `filename.xxx`
  * Camel case, where the first letter of each section of text is capitalized, e.g. `fileName.xxx`
* A good format for date designations is `YYYYMMDD` or `YYMMDD`. This format makes sure all of your files stay in chronological order, even over the span of many years.
* Try not to make filenames too long, since long file names do not work well with all types of software. Include only the information that is necessary to find and make sense of the file. Aim to be meaningful and brief. Remember: the filename is not the place to record metadata!
* When using a sequential numbering system, use an adequate number leading zeros for clarity and to make sure files sort in sequential order. For example, use `0001, 0002, ...0010, 0011 ... 0100, 0101, `etc. instead of `1, 2, ...10, 11 ... 100, 101, ` etc.

### Other Tips

Include in the directory a `README.txt` file that explains your naming format along with any abbreviations or codes you have used. This documentation will be helpful both during the project or experiment, and also in the future