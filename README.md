# Project Title

FizzBuzz Sample Website

## Description

Website home page has a form that accepts the following input: 

* Name
* Gender
* Marital Status
* Date of Birth
* An Arbitrary Integer

After form submission, input is stored in a session variable and the user is redirected to a results page. All form submissions in current session are visible on results page.  Submissions are grouped according to 'integer' input: 

* 'fizz' table contains all submissions where 'integer' is divisible by 3
* 'buzz' table contains all submissions where 'integer' is divisible by 5
* 'fizzbuzz' table contains all submissions where 'integer' is divisible by 3 and 5
* 'ungrouped' table contains all submissions that are not divisible by 3 or 5

There is a counter in the header that shows the count for each category.

### Installing

* Download zipped folder from this GitHub project
* Unzip folder and place on local drive on any computer

### Executing program

* Open index.html file in any browser
* Fill out form and hit submit (all fields are required, 'integer' field needs to be a number)
* View results on results.html page where you will be redirected after form submission
* Click on 'add' button or logo in header to get back to the home page to fill out another form

### Test cases

Case #1 (FIZZ)
* Name: Joe Smith
* Gender: Male
* Marital Status: Married
* Date of Birth: 02/17/2002
* An Arbitrary Integer: 9

Case #2 (FIZZ)
* Name: Mary Smith
* Gender: Female
* Marital Status: Single
* Date of Birth: 05/08/1984
* An Arbitrary Integer: 6

Case #3 (BUZZ)
* Name: Alvin Smith
* Gender: Male
* Marital Status: Widowed
* Date of Birth: 04/15/2000
* An Arbitrary Integer: 10

Case #4 (BUZZ)
* Name: Tammi Smith
* Gender: Female
* Marital Status: Married
* Date of Birth: 08/18/1995
* An Arbitrary Integer: 25

Case #5 (FIZZBUZZ)
* Name: Robert Smith
* Gender: Male
* Marital Status: Divorced
* Date of Birth: 05/04/1990
* An Arbitrary Integer: 30

Case #6 (FIZZBUZZ)
* Name: Holly Smith
* Gender: Female
* Marital Status: Married
* Date of Birth: 12/05/1989
* An Arbitrary Integer: 15

Case #7 (UNGROUPED)
* Name: David Smith
* Gender: Male
* Marital Status: Separated
* Date of Birth: 11/15/1999
* An Arbitrary Integer: 13

Case #8 (UNGROUPED)
* Name: Barb Smith
* Gender: Female
* Marital Status: Married
* Date of Birth: 01/20/1987
* An Arbitrary Integer: 17

## Help
  
All fields are currently required and a number is required for the 'integer' field.  
Form will not submit unless these requirements are met.
Error messages will be added in a future release.

## Authors

Sara Eames (https://www.linkedin.com/in/sara-eames-sweeney)

## Version History

* 0.2
    * Added bee animation to index.html page
    * Removed redundant javascript 

* 0.1
    * Initial Release

## License

Background image is from https://www.istockphoto.com and licensed for use to WebGen LLC - see the LICENSE.md file for details

