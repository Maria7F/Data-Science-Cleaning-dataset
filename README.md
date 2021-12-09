# NYC Restaurant Inspections
#### Question/need:
* What was the most borough got inpected
* What is the most repeatedly violation that got the restaurant to be inspected?
* what is the flow of critical and not critical over the years?
* what is the most violation is repeated?
* Can you predict restaurant closings?


#### Data Description:
* Restaurant inspections for permitted food establishments in NYC. Restaurants are graded on A-F scale with regular visits by city health department.
Dataset includes address, cuisine description, inspection date, type, action, violation code and description(s).Data covers all of NYC and starts Jan 1, 2010-Aug 29, 2017.
* Data was collected by the NYC Department of Health.

| Syntax                  | Description |
| ----------------------- | ----------- |
| CAMIS                   | This is an unique identifier for the entity (restaurant); 10-digit integer, static per restaurant permit        |
| DBA                     | This field represents the name (doing business as) of the entity (restaurant); Public business name, may change at discretion of restaurant owner        |
| BORO                    | Borough in which the entity (restaurant) is located.;• 1 = MANHATTAN • 2 = BRONX • 3 = BROOKLYN • 4 = QUEENS • 5 = STATEN ISLAND • Missing; NOTE: There may be discrepancies between zip code and listed boro due to differences in an establishment's mailing address and physical location       |
| BUILDING                | Building number for establishment (restaurant) location        |
| STREET                  | Street name for establishment (restaurant) location       |
| ZIPCODE                 | Zip code of establishment (restaurant) location        |
| PHONE                   | Phone Number; Phone number provided by restaurant owner/manager       |
| CUISINE DESCRIPTION     | This field describes the entity (restaurant) cuisine. ; Optional field provided by provided by restaurant owner/manager        |
| INSPECTION DATE         | This field represents the date of inspection; NOTE: Inspection dates of 1/1/1900 mean an establishment has not yet had an inspection       |
| ACTION                  | This field represents the actions that is associated with each restaurant inspection. ; • Violations were cited in the following area(s). • No violations were recorded at the time of this inspection. • Establishment re-opened by DOHMH • Establishment re-closed by DOHMH • Establishment Closed by DOHMH. Violations were cited in the following area(s) and those requiring immediate action were addressed. • "Missing" = not yet inspected;        |
| VIOLATION CODE          | Violation code associated with an establishment (restaurant) inspection       |
| VIOLATION DESCRIPTION   | Violation description associated with an establishment (restaurant) inspection        |
| CRITICAL FLAG           | Indicator of critical violation; "• Critical • Not Critical • Not Applicable"; Critical violations are those most likely to contribute to food-borne illness        |
| SCORE                   | Total score for a particular inspection; Scores are updated based on adjudication results       |
| GRADE                   | Grade associated with the inspection; • N = Not Yet Graded• A = Grade A• B = Grade B• C = Grade C• Z = Grade Pending• P= Grade Pending issued on re-opening following an initial inspection that resulted in a closure        |
| GRADE DATE              | The date when the current grade was issued to the entity (restaurant)       |
| RECORD DATE             | The date when the extract was run to produce this data set        |
| INSPECTION TYPE         | A combination of the inspection program and the type of inspection performed; See Data Dictionary for full list of expected values        |

#### Tools:
* Pandas
* Plotly
* Seaborn
* Matplotlib
* Sklearn 
* Numpy 

#### Dataset Link:
[NYC Restaurant Inspections](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j)
