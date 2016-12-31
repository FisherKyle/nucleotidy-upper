## **Nucleotidy-upper**

#### // Epicodus Advanced Drupal Independent Project 12.19.2016

by [Kyle Fisher](https://github.com/fisherkyle)


----
### **Description**

This application utilizes Drupal 7.x, Ajax, two custom modules, and the use of functional and unit module testing. First, Ajax is used to display new biology terms without reloading the page; a custom module handles the ajax calls and loads content. Second, users can input a nucleotide sequence ('ACTG...') into a form and see the complementary sequence displayed. A custom module is used to create the form, validate input, and present the result to the user. Test Driven Development [through unit testing] was completed prior to writing the module logic. Once all unit tests were passing, the module was written, and then a functional test was run to make sure the entire user interface was working as expected.

----
### **Specifications**
| _Behavior_ | _Input_ | _Output_ |
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
|  "A" | "T" |
|  "G" | "C" |
|  "T" | "A" |
|  "C" | "G" |
|  "AG" | "TC" |

___
### **Setup/Installation Requirements**

* Clone this repository: https://github.com/LisaMacCarrigan/double-helix-drupal.git
* Set document root to the top level directory of the repository
* Import the database, called "dna", found in `sites/db-backup`
* Create a user for the database: username = "dna", password = "dna"
* Point browser to localhost
* Site maintenance account info: username = "dna", password = "dna"
* Open project folder ('double-helix-drupal') in Code Editor of choice

___

### ~~**Known Bugs**~~


___
### **Support and contact details**

For comments or questions, please email kyle@kylefisher.com
___
### **Technologies Used**
* Drupal
* PHP
* MAMP Version
* MySQL Server
* phpMyAdmin Version
#
#
___
### **License**

*MIT license*

___
*Copyright (c) 2016 [Kyle Fisher](https://github.com/fisherkyle)*
