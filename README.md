# HIVE-RefData
![Deploy](https://github.com/Blade2021/HIVE-RefData/workflows/Deploy/badge.svg)

# How to contribute?
Wanna help contribute to a short database of useful commands for HIVE?  Check out the example.json included with this repo.  This will give you the json object template that will be used for each definition.  Now its time to "fill in the blanks", setup your definition using the data structure below.  Then submit a PR (pull request) for review.  Please remember that all submissions **MUST** to conform to the data structure to be accepted.

## Data Structure
#### Installation
Try to include information on requirements, skills required, or maybe a library?
#### Links
The links section is an array object.  So include any links in array format ( ["link.com","link.org","link.net"] )
#### Description
This is the meat of the defintion.  What is the defintion?  What does it do?  How does it help?  Details are key.  (Just remember we do have a character limit so no 10 page essays please.
#### Category
Pick a category from below or suggest a new one.  We are trying to generalize everything for easy access so try to be generic.  The category is also an array object so you can use more then one!
#### Alias (Optional)
Does your definition fit more then just one reference?  No problem, just add any aliases here.

## Acceptable Categories
- infastructure
- switching-applications
- lights
- applications
- utilities
- monitoring
- graphs
- bridge
- microcontroller

(More as required)

# Example Object
```json
{
  "Example": {
    "installation": "To install this example you need to pull the repo or example.json",
    "links": ["https://github.com/Blade2021/HIVE-RefData","https://hivedev.roots.systems"],
    "description": "This is just an example description of what this file is used for and how to set it up for collaboration",
    "category": ["utilities"]
  },
}
```
# REGEX
The following will be replaced automatically:  
**{prefix}** - Replaced with HIVE's current prefix, This keeps from having to hardcode the prefix.
  
# Automatic Deployment
All commits to the master are validated and deployed upon successful validation.  After deployment, HIVE bot may be reloaded by any member of staff to reload the reference library. 
