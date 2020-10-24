## Premier_league_competitions

Includes some scripts to retrieve match scores, wins/loses, and club names at a given Premier Leauge season between 2000 and 2018.

This project is not completed yet but since it is a fun-based project, I will try to improve and make it more readable as long as I've found time to work on it.

The data retrived from the [link](https://datahub.io/sports-data/english-premier-league)

### To download the main folder using Python:
'''
from datapackage import Package

package = Package('https://datahub.io/sports-data/english-premier-league/datapackage.json')

# print list of all resources:
print(package.resource_names)

# print processed tabular data (if exists any)
for resource in package.resources:
    if resource.descriptor['datahub']['type'] == 'derived/csv':
        print(resource.read())
'''

### If download through weblink manually:

You can directly follow the script.
