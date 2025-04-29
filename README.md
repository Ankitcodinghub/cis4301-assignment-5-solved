# cis4301-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [CIS4301 Assignment 5 Solved](https://www.ankitcodinghub.com/product/cis4301-alin-dobra-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110095&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIS4301 Assignment 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
For this assignment, you will be asked to create an interface to query and edit data for a SQLite database. You will use the database maintained by the imaginary Southern Sierra Wildflower Club (SSWC), an organization whose members are interested in observing wildflowers in their native habitat in the southern part of the Sierra Nevada mountains of California. This is the same database as assignment 4.

The database maintained by the club has three tables:

SIGHTINGS (NAME, PERSON, LOCATION, SIGHTED)

FEATURES (LOCATION, CLASS, LATITUDE, LONGITUDE, MAP, ELEV)

FLOWERS (GENUS, SPECIES, COMNAME)

The database tables have the following semantics:

• SIGHTINGS gives information that describes every time that a member of the club observes one of the wildflowers described in the table FLOWERS. NAME tells the name of the flower observed, PERSON describes who saw the flower, LOCATION tells the name of a nearby geographical feature where the flower was seen, and SIGHTED tells the day when the flower was seen.

• FEATURES lists the various locations where flowers have been observed. LOCATION is the name of the place, CLASS is the type of place. There are several types such as Summit, Mine, Locale, etc. LATITUDE and LONGITUDE describe where on the surface of the earth the locations are found. MAP tells the name of the topographic map where the feature can be found and ELEV tells the height of the feature.

• FLOWERS lists all of the flowers that the members of the SSWC try to find. GENUS and SPECIES give the scientific name for the flower, and COMNAME gives the non-scientific name (SIGHTING.NAME is a foreign key into FLOWER.COMNAME).

The database with the schema and initial data is attached to this assignment.

The Task (100 pts)

Create an interface that provides the following functionality:

• Update – Allow a user to select and update flower information.

• Insert – Allow a user to insert a new sighting of a flower.

Note 1 You are not limited to any technology. You can use Python, PHP, etc as long as you meet the requirements outlined above.

Note 2 You must write the queries in SQL as opposed to using any ORM (object relational model) as supported by various web frameworks. You also need to use SQLite3 as the database.

Group work You can work in groups of 2 for this assignment. Form groups using Canvas.

Extra Credit (100 pts)

1) Well Designed Web Interface (50 pts)

• 10 pts – Aesthetically pleasing

• 10 pts – User login

• 10 pts – Allows creation, update, and delete through a graphical interface

• 15 pts -Pictures of flowers are displayed with queries that return flower names

• 5 pts – Sanitize any user generated query to prevent SQL injection

2) Back End (50 pts)

• 5 pts – Create an index for each attribute in table SIGHTINGS

• 15 pts – Create a trigger to log insertions, updates, and deletions from all tables

• 5 pts – Have at least one user initiated input done as a transaction

• 25 pts – Find a way to analyze your database’s performance; measure performance with and without triggers and indexes

If you attempt an extra credit item it must be documented in your video or write-up in order to receive credit.
