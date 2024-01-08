<h1>Health Tracker</h1>

<p>To help those suffering chronic illnesses track their health data to help manage those illnesses. Can also be used as a general health tracker.</p>
## Data to store

* Heart rate
  * number of bpm
  * date/time
  * active/at rest
  * notes field
* Blood pressure
  * systolic - number
  * diastolic - number
  * date/time
  * notes field
* Period
  * start
    * date/time
    * notes field
  * end
    * date/time
    * notes field
  * more details
    * cramps/no cramps
    * color
    * amount
    * notes field
* food
  * date/time
  * notes field
* pain points on drawing
  * x/y coordinates on image
  * date/time
  * duration - amount of time
  * pain range 1-10
  * quality - dull, sharp, etc
  * notes field
* sleep
  * start
  * end
  * quality
  * dream
  * notes field
* weight
  * amount
  * date/time
* Exercise
  * type
  * duration
  * date/time
  * quality - vigourus, relaxed, just for funsies
## Prioritization


### Need to have

* Auth the current user (Prefably OAuth or something)
* Store data in a database
* Retrieve data in UI
* Navigation
  * Food
  * Pain chart
* Food
  * What you ate
  * date/time
  * notes field
* Pain chart - Picture of a human with pain points drawn
  * Pain range 1-10
  * Date/time
  * Notes


### Want to have

* Navigation
  * Heart Rate
  * Blood Pressure
  * Exercise
  * Summaries
  * Sleep
  * Calendar
  * Period
  * Weight
* Pain chart - Picture of a human with pain points drawn
  * Picture is a choice (male, female, skinny, fat, etc)
  * Can add multiple red dots
    * Each with their own dots
    * Pain range 1-10
    * duration of pain
    * Quality - dull, sharp, stabbing, squeezing
    * Notes
* Heart Rate
  * number field for bpm
  * date/time
  * active/at rest
  * notes field
 Blood Pressure
  * systolic - number
  * diastolic - number
  * date/time
  * notes field
* Weight
  * amount
  * date/time
* Exercise
  * type - long boarding, running, yoga, stretching, etc
  * duration
  * date/time
  * quality - vigourus, relaxed, just for funsies
* Summaries
  * One pager to print and give to doctor
* Sleep
  * start - date/time
  * end - date/time
  * quality - like a rock, up all night, restless, off and on
  * Do you remember dreaming - boolean
  * notes field
* Calendar view of all data (since it all has date/time)
  * Month/Week/Day view
  * Color coated
    * Red - Pain
    * Pink/Pastel - Period
    * Yellow - Exercise
    * Dark Green - Food
    * Light Green - Weight
    * Blue - Sleep
    * Purple - Heart Rate
    * Violet -Blood Pressure
* Period
  * start
    * date/time
    * notes field
  * end
    * date/time
    * notes field
  * more details
    * cramps/no cramps
    * color
    * amount
    * notes field


### Nice to have

* Any instructions
* Calendar view
  * Filter for different date types (pain, heart rate, etc)
* Heart Rate
